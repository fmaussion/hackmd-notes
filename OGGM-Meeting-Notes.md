# OGGM Open Meeting Notes

About the format:
- **Flash updates**: quick round of short updates (~2 minutes), request of additional agenda items for longer discussions
- **Group agenda points**: longer, open discussion points of the day. Could be something that needs input from all participants, a discussion about model choices, or a prepared presentation from one of the members. Note that **our goal is to keep "Flash updates" + "Open agenda" under one hour** in order to keep a dynamic meeting.
- **Specific discussion:** more technical items that may not be of interest to everyone (e.g. about a specific problem, master thesis, etc.). These will take place after the official part.
- **Action items**: what needs to be done after the meeting and by who
- **Move to next meeting**: items that couldn't be discussed this time

## Next call: 2019-08-21

Hello and welcome to the team meeting!

### Participants 

Please sign in below so we know who was here:

Name / Institution / @GitHub handle (optional)

- Fabien Maussion / University of Innsbruck / @fmaussion
- Jenna Sutherland / University of Leeds / @gyjls
- Anouk Vlug / University of Bremen / @anoukvlug 
- Matthias Dusch / University of Innsbruck / @matthiasdusch
- Ben Marzeion / University of Bremen / @bmarzeion
- Beatriz Recinos / University of Bremen / @recinos

### Flash updates

- Fabien:
    - recent PRs: https://github.com/OGGM/oggm/pull/852, https://github.com/OGGM/oggm/pull/853
    - Main motivation for these PRs: 
        - get started on a calving param with Lizz (https://github.com/ehultee/chakra)
        - better diagnostics (e.g. flux, velocity) for OGGM-Edu and apps (e.g. https://github.com/pat-schmitt/glacier_simulator)
- Jenna: 
    - Running with BISICLES, not OGGM lately
    - has some questions about OGGM or hub: don't hesitate to ask on Slack!
- Matthias:
    - Continue to work on metrics to check model performance for length
    - Cluster runs: poster for IMC - with multiple parameters from OGGM
- Anouk:
    - new simulations to expend on sensitivity test of the initial conditions
    - back in Bremen - writing second paper
- Ben:
    - New cluster proposal: questions from DFG from reviewer 
    - Include Jan Henrik on slack (will join as PhD student October 1st)
- Beatriz:
    - velocities from OGGM compare with Greenland
    - paper reviews are good - maybe ready in two weeks


### Group agenda

- Fabien: short discussion about the mass-balance t* calibration with other data like CERA-20C (https://fabienmaussion.info/2019/08/19/cera-20c/).
- Fabien: new diagnostics in OGGM and how to get them


## 2019-08-07 call

### Participants 

Please sign in below so we know who was here:
Name / Institution / @GitHub handle

- Fabien Maussion / University of Innsbruck / @fmaussion
- Jenna Sutherland / University of Leeds / @gyjls
- Matteo Castellani / University of Innsbruck / @MatCast
- Anouk Vlug / University of Bremen / @anoukvlug
- Patrick Schmitt / University of Innsbruck / @Patrick
- Moritz Oberrauch / University of Innsbruck / [@oberrauch](https://github.com/oberrauch)
- Matthias Dusch / University of Innsbruck / @matthiasdusch
- Timo Rothenpieler / University of Bremen / @TimoRoth

### Flash updates

- Fabien
    - wrote a 3 pages "pre-proposal" with Ben for a "Sustainable software development" call at DFG - if succesful (unlikely) we'll have a post-doc salary for two years
    - worked on long overdue maintenance PRs: https://github.com/OGGM/oggm/pulls?q=is%3Apr+is%3Aclosed (discovered quite a bad bug in OGGM with numpy 1.17)
    - also played around again with "cloud-ready" containers. e.g. https://discourse.jupyter.org/t/reproducible-binder-environments-with-repo2docker-dockerhub-and-nbgitpuller/1823 
    - https://twitter.com/LizzUltee/status/1154350500315316226
- Jenna:
    - Question about WD on https://hub.oggm.org: `/home/jovyan/`  
    - Model intercomparison OGGM - Bicycles
    - INQUA conference: talk on progress 
- Patrick:
    - App update: put on Binder? -> YES
    - Technicalities -> on chat
- Moritz:
    - finished the equilibrium runs with the VAS model.
    - started to look into linearity of the VAS model.
- Matthias
    - tested a possible precipitation gradient but probably reject the idea
- Matteo:
    - Analyzed the feature importance (i.e. what variables are important)
    - mass-balance above point, slope, are most important to explain thickness
- Anouk:
    - Sensitivity to initial conditions
    - Still in Utrecht 
    - CESM data mess: OGGM doesn't allow for time before Julian day 1. You can create such a climate file. However when using it as forcing you get an error. 
- Timo:
    - Still problems with Bokeh - ended up working without explanation!

### Agenda

- What statistical measures do you use to compare two (or more) time series? In particular comparing observed glacier length change with modeled one. (Matthias)
    - OGGM small funcs in [utils](https://github.com/OGGM/oggm/blob/2058f993a56403d14bfba05096c3ca367e395e65/oggm/utils/_funcs.py#L298-L328) can be extended!
    - Idea: moving (rolling) statistics (rmsd / r2 / etc as timeseries)
    - Statistics in atmospheric sciences book
- Question on the flowlines from Jenna 
    - How to start from spin-up: look on the docs and ask on slack
- Discuss the results of the ACF and PSD analysis of the modeled VAS glacier length changes (Moritz).
    - PSD of flowline model shows a low pass behaviour (constant power for frequencies above 0.05/year). PSD of VAS model decreases constantly on the logarithmic scale (energy cascade, low pass filter?)
    - The VAS model shows less auto correlation at shorter lag times (< 200 years) than the flowline model, indicating more high frequency variability.
    - ToDo's: Compute ACF and PSD for climate signal, to better relate the forcing to the output. Additionally, get rid of spinup period for both analysis.
    
- Matteo plots
    - Showed how the volume changes between different training samples: 1% deviation
    - Showed how the score changes with different training samples: weird values for some runs: maybe some glaciers are completly left out?
    - Feature importance seems reasonable.
    - TODOS: 
        - Leave one glacier out from the training sample
        - Check how random is sklearn cross validation to find out how come some scores are much lower
        - Run oggm ice thickness for one glacier and compare it with the machine learning model.
- Anouk plot:
    - nice to see that glaciers end up at the correct volume
    - still questions about why it takes so long to merge together
    - TODO: investigations as to which glaciers are responsible


### Action items

- Rediscuss with Matthias about gradient and re-calibration 
- Long term CESM data on Github (Issue #818)

### Move to next meeting


## 2019-07-24 call

Hello and welcome to the team meeting!

### Participants 

Please sign in below so we know who was here:
Name / Institution / @GitHub handle

- Fabien Maussion / University of Innsbruck / @fmaussion
- Matteo Castellani / University of Innsbruck / @MatCast
- Julia Eis/ University of Bremen / @juliaeis
- Matthias Dusch / University of Innsbruck / @matthiasdusch
- Moritz Oberrauch / University of Innsbruck / [@oberrauch](https://github.com/oberrauch)
- Zora Schirmeister / University of Innsbruck / @zschirmeister

### Flash updates

- Fabien
    - gave a talk at IUGG 2019: https://fabienmaussion.info/2019/07/24/IUGG2019
    - a lot of feedback from the conference: OGGM highly visible, but concrete adoption (i.e. doing stuff with the model or develop) still slow. Hints of change with new users recently
    - Lizz using OGGM-Edu for a 1-week lecture in Peru: https://github.com/ehultee/CdeC-glaciologia. We set-up a dedicated JupyterHub for the class.
- Matteo:
    - Update about running the machine learning model for all the glaciers in the Alps
    - Do you know [nteract Data Explorer](https://github.com/nteract/nteract/tree/master/packages/data-explorer)
- Julia:
    - Experiments with real world glaciers
    - link to TC discussion: https://www.the-cryosphere-discuss.net/tc-2019-68
- Matthias:
    - PR about merging glacier done: https://github.com/OGGM/oggm/pull/827
- Zora:
    - working with Patrick about the app
    - problems with the Bokeh server on edu.oggm.org: https://github.com/OGGM/oggm-edu/issues/66
    - we need a concept for the bokeh applications in Bremen
- Moritz:
    - Further work on the equilibrium runs, comparing the volume/area scaling model with the flowline mode
    - Made progress about spectral analysis: nice plots

### Agenda

- Format of these calls
    - Fabien explained it but need for some explanation text maybe
- Twitter
- thoughts on a PolynomialProfilemMassBalance model?
    - need for more realisic MB profiles
    - Please open a point on github
    - diverged to having a PeriodicMassBalanceModel
    - diverged to PeriodicMassBalanceScenario
- Need for discussion about Julia's revisions
    - Matthias, Julia and Fabien had a longer conversation about how to deal with the reviews


### Action items

- talk to Timo about bokeh when back from holiday
- Twitter contributor meeting next week
- Preformance problems about Hackmd integration in website: not much we can do here

### Move to next meeting

- Push for JupyterHub in the upcoming cluster in Bremen
- Matteo: discussion about the score
- RGI group

## 2019-07-03 call

First regular call. No notes taken.

### Participants 

Please sign in below so we know who was here:
Name / Institution / @GitHub handle

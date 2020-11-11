# OGGM Open Meeting 

###### tags: `oggm` `meeting notes`

About the format:
- **Flash updates**: quick round of short updates (~2 minutes), request of additional agenda items for longer discussions
- **Group agenda points**: longer, open discussion points of the day. Could be something that needs input from all participants, a discussion about model choices, or a prepared presentation from one of the members. Note that **our goal is to keep "Flash updates" + "Open agenda" under one hour** in order to keep a dynamic meeting.
- **Specific discussion:** more technical items that may not be of interest to everyone (e.g. about a specific problem, master thesis, etc.). These will take place after the official part.
- **Action items**: what needs to be done after the meeting and by who
- **Move to next meeting**: items that couldn't be discussed this time

# Call: 2020-11-11

### Participants 

Please sign in below so we know who was here:

Name / Institution / @GitHub handle (optional)
- Anouk Vlug / University of Innsbruck / @anoukvlug
- Nicolas Champollion / Institut des Géosciences de l'Environnement / @nchampollion
- Larissa van der Laan / University of Hannover / @lvdlaan
- Julia Eis / University of Bremen/@juliaeis
- Fabien Maussion / University of Innsbruck/ @fmaussion 
- 


### Flash updates
- Anouk
    - Why can my single forced SMB test simulations not be added up for the Arctic in recent times?
- Larissa
    - Non-OGGM related paper, CMIP5 decadal runs
- Fabien:
    - still fighting with inversion related problems, good interactions with David Rounce
    - Glacio Hack tomorrow and Friday: https://github.com/GlacioHack 


### Group Agenda Points

- Is HackMD laggy somehow? I put the very old notes in another doc
- Meeting time for US OGGM friends?

### Action items



# Call: 2020-10-28

### Participants 

Please sign in below so we know who was here:

Name / Institution / @GitHub handle (optional)
- Anouk Vlug / University of Innsbruck / @anoukvlug
- Larissa van der Laan / University of Hannover / @lvdlaan
- Madlene Pfeiffer / University of Bremen / @mpfeiffer
- Julia Eis/ University of Bremen/ @juliaeis 
- Hamid Mojtabavi / University of Bremen/ @Hamid Mojtabavi 
- Jan-Hendrik Malles / University of Bremen / @jmalles 
- Lilian Schuster / University of Innsbruck / @lilianschuster
- Li Fei / ITP-CAS / @Keeptg 
- Melissa Mengert / University of Bremen / @Melissa 
- Beatriz Recinos / NOC / @bearecinos

### Flash updates
- Short introduction round of everyone.
- Anouk:
    - New approach to checking if my single forced results add up to the fully forced results, in the test simulations
- Larissa:
    - CMIP5 decadal forecasts to force OGGM
- Julia:
    - preparing my Phd defense
- Jan
    - submitting paper this week, then back to OGGM :-)
- Lilian
    - I am working on including a kind of "daily" melt model by using monthly mean and daily standard deviation and assuming a gaussian temperature distibution
    - however, at the moment I am working again on the revision of a non-OGGM related manuscript 
- Li Fei:
    - still effort on the paper text, nothing new to share
- Bea:
    - saying hello. Greenland paper update.


# Call: 2020-10-14

### Participants 

Please sign in below so we know who was here:

Name / Institution / @GitHub handle (optional)
- Anouk Vlug / University of Innsbruck / @anoukvlug
- Julia Eis/ University of Bremen/ @juliaeis 
- Jan-Hendrik Malles / University of Bremen / @jmalles 
- Lilian Schuster / University of Innsbruck / @lilianschuster
- Moritz Oberrauch / University of Innsbruck / [@oberrauch](https://github.com/oberrauch)
- Fabien Maussion / University of Innsbruck/ @fmaussion 


### Flash updates
- Anouk Vlug:
    - Testing single forced simulations
    - Simulations with prescribed geometry
- Julia: 
    - SAVE THE DATE: 26.11.2020, 12:00- 14:00 will take place my PhD defence (hybrid: in person and online)
    - still working on CO2 response functions with BernSCM (a simple climate model)
    - plan to do many equilibrium runs with OGGM (not yet started)
- Jan:
    - still nothing new concerning OGGM...
- Lilian: 
    - nothing new just trying to think Bayesian 
    - I am working on implementing the Bayesian framework into OGGM, starting first with Hintereisferner and only using mustar as free parameter 
- Moritz:
    - ACF, PACF and PSD for time series analysis
- Fabi:
    - Text on Matthias 
    - Working on update of pre-processed directories
    - found a way to connect jupyter remotely on the cluster




# Call: 2020-09-30

### Participants 

Please sign in below so we know who was here:

Name / Institution / @GitHub handle (optional)
- Matthias Dusch / University of Innsbruck / @matthiasdusch
- Anouk Vlug / University of Innsbruck / @anoukvlug
- Jan-Hendrik Malles / University of Bremen / @jmalles
- Julia Eis/University of Bremen/ @juliaeis
- Li Fei / ITP-CAS / @Keeptg  
- Lilian Schuster / University of Innsbruck / @lilianschuster
- Fabien Maussion / University of Innsbruck/ @fmaussion 


### Flash updates

- Matthias: Struggling with preindustrial climate simulations
- Anouk: 
    - I started doing simulations on the cluster to test some things. This included checking the effect in using the ensemble climatology instead of the ensemble member its climatology when aplying the anomaly method for a selection of glaciers. 
- Jan: nothing new concerning OGGM
- Julia: nothing new regarding oggm
- Li Fei: 
    - Simulated the glacier change with different temperature and precipitation bias (A cooperative work)
    - Calibrating inversion thickness model in Tian Shan
    - Training about filed work and glacier rescue
- Lilian: nothing really new, but started to introduce myself a bit more into Machine Learning and Bayesian Methods
    - e.g. went through this illustrative jupyter-notebook "book": https://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/ 
      (they use the same package 'pymc' as in David Rounce' PyGEM Bayesian approach)
- Fabien:
    - new laptop, unravelled a couple of maintenance tasks for OGGM


# Call: 2020-09-16

### Participants 

Please sign in below so we know who was here:

Name / Institution / @GitHub handle (optional)
- Matthias Dusch / University of Innsbruck / @matthiasdusch
- Anouk Vlug / University of Innsbruck / @anoukvlug
- Li Fei / ITP-CAS / @Keeptg 
- Lilian Schuster / University of Innsbruck / @lilianschuster
- Julia Eis/ University of Bremen / @juliaeis 


### Flash updates

- Matthias:
    - Back from vacation
    - New OGGM office mates
- Anouk:
    - Started in Innsbruck
    - Played for the first time with the Bremen cluster
    - Did some simulations forced with the CESM-LME starting in 1850 CE
- Li Fei:
    - Tried simulating ice thickness by using exponential MB profile
    - Paper text
- Lilian:
    - PhD proposal submitted last saturday together with Fabien 
    - thinking about which courses I could take  
- Julia: 
    - code cleaning/example writing of initialization module
    - slowly starting the "new" project
    
    
# Call: 2020-09-01

### Participants 

Please sign in below so we know who was here:

Name / Institution / @GitHub handle (optional)
- Fabien Maussion / University of Innsbruck/ @fmaussion 
- Lilian Schuster / University of Innsbruck / @lilianschuster
- Julia Eis/ University of Bremen/ @juliaeis 
- Anouk Vlug / University of Innsbruck / @anoukvlug
- Jan-Hendrik Malles / University of Bremen / @jmalles 
- Li Fei / ITP-CAS

### Flash updates

- Fabien:
    - Lilian PhD project final round
    - UIBK part of EU H2020 proposal submitted yesterday 
- Lilian:
    - PhD officially started by university fellowship
    - finalising PhD project proposal for ÖAW-DOC fellowship 
- Julia: 
    - submitted the comparison paper to Frontiers in Earth Science
    - finally submitted the thesis (defense will most probably take place mid/end November)
- Jan
    - working on code
- Li Fei
    - (DEM - COPDEM) Glacier change from topo data 
- Anouk
    - Arrived in Innsbruck
    
### Group Agenda Points

- Code within or outside of OGGM


### Action items

# Call: 2020-08-19

### Participants 

Please sign in below so we know who was here:

Name / Institution / @GitHub handle (optional)
- Matthias Dusch / University of Innsbruck / @matthiasdusch
- Moritz Oberrauch / University of Innsbruck / [@oberrauch](https://github.com/oberrauch)
- Patrick Schmitt / University of Innsbruck / [@pat-schmitt](https://github.com/pat-schmitt)
- Fabien Maussion / University of Innsbruck/ @fmaussion 


### Flash updates

- Matthias:
    - see below
- Fabien:
    - High school student Josie had a look at OGGM-Edu
    - Lilian PhD project
- Moritz:
    - Alpine runs on Cluster comparing the volume/area scaling model to the flowline model; scaling underestimates volume change in response to +/- 0.5°C step change; normalized volume change +/-20% with scaling and +60%/-40% with flowline.
    
### Group Agenda Points
- Matthias: presentation of ensemble results: HISTALP reconstructions since LIA, commitment runs and projections

### Action items


# Call: 2020-08-05

### Participants 

Please sign in below so we know who was here:

Name / Institution / @GitHub handle (optional)
- Matthias Dusch / University of Innsbruck / @matthiasdusch
- Julia Eis/ University of Bremen / @juliaeis 
- Jan-Hendrik Malles / University of Bremen / @jmalles
- Fabien Maussion / University of Innsbruck/ @fmaussion 
- Lilian Schuster / University of Innsbruck / @lilianschuster

### Flash updates

- Matthias:
    - back from holidays, no updates
- Julia: 
    - will submit the paper hopefully latest by beginning of next week
- Jan:
    - changed some things in my frontal ablation implementation
    - but on hold due to going back to reconstruction paper
- Fabien:
    - testing the new cluster
    - changes in OGGM inversion are now in: expect changes in the model output
- Lilian:
    - nothing really new 
### Group Agenda Points
- Julia: presentation of the new paper (Reconstruction of past glacier changes using a glacier model: validation with observations) 

### Action items



# Call: 2020-07-22

### Participants 

Please sign in below so we know who was here:

Name / Institution / @GitHub handle (optional)
- Matthias Dusch / University of Innsbruck / @matthiasdusch
- Fabien Maussion / University of Innsbruck/ @fmaussion 
- Bob McNabb / Ulster University  / @iamdonovan
- Julia Eis / University of Bremen /@juliaeis
- Anouk Vlug / University of Bremen / @anoukvlug

### Flash updates

- Matthias:
    - work on calibration paper, holidays next week, update/results probably in the meeting after the next one
- Fabien:
    - some work on the ice thickness inversion in the pipeline
    - interesting call last week on a PyGEM / OGGM paper in preparation
- Julia: 
    - Comparison paper almost done (just need to revise the conclusion and abstract)

### Group Agenda Points

- OGGM and LIA

### Action items

- Matthias presentation in 4 weeks (19.08)


# Call: 2020-07-08 (brainstorm session on surface mass-balance processes)

### Participants 

Please sign in below so we know who was here:

Name / Institution / @GitHub handle (optional)
- Matthias Dusch / University of Innsbruck / @matthiasdusch
- David Rounce / Carnegie Mellon University
- Anouk Vlug / University of Bremen / @anoukvlug
- Larissa van der Laan / Hannover University / @lvdlaan
- Julia Eis/ University of Bremen / @juliaeis 
- Melissa Mengert/ University of Bremen
- Jan-Hendrik Malles / University of Bremen / @jmalles 
- Fabien Maussion / University of Innsbruck/ @fmaussion 
- Jon Mackay / British Geological Survey / @hydrojon 

### Brainstorming session - mass balance modelling

- a lot of good discussions! Thanks all for joining. 



# Call: 2020-06-24

### Participants 

Please sign in below so we know who was here:

Name / Institution / @GitHub handle (optional)
- Matthias Dusch / University of Innsbruck / @matthiasdusch
- Anouk Vlug / University of Bremen / @anoukvlug
- Julia Eis / University of Bremen / @juliaeis 
- Jan-Hendrik Malles / University of Bremen / @jmalles 
- Fabien Maussion / University of Innsbruck/ @fmaussion 
- Lilian Schuster / University of Innsbruck / @lilianschuster
- Jon Mackay / British Geological Survey / @hydrojon


### Flash updates

- Matthias:
    - work on calibration paper
- Jan:
    - working on frontal ablation
- Julia: 
    - corrections of paper draft (Bens comments)
- Fabien:
    - "Frontal ablation week" with Lizz
    - still working on OGGM MB calib
- Lilian: 
    - working on PhD proposal (trying to understand better bias correction and downscaling)

### Group Agenda Points


### Action items

- next MB workshop?




# Call: 2020-06-17

### Participants 

Please sign in below so we know who was here:

Name / Institution / @GitHub handle (optional)
- Matthias Dusch / University of Innsbruck / @matthiasdusch
- Anouk Vlug / University of Bremen / @anoukvlug
- Julia Eis/University of Bremen / @juliaeis 
- Jan-Hendrik Malles / University of Bremen / @jmalles 
- Lilian Schuster / University of Innsbruck / @lilianschuster
- Fabien Maussion / University of Innsbruck/ @fmaussion 


### Flash updates

- Matthias:
    - crossvalidation with ERA5
    - work on calibration paper
- Anouk:
    - Update on the volcanic single forced simulations.
- Julia: 
    - nothing to report (just back from home-holidays)
- Jan:
    - presentation of my work on frontal ablation
- Lilian:
    - working on PhD-proposal 
- Li Fei:
    - doing runs on cluster 
- Fabien:
    - stuff with climate: ERA5 + ERA5L
    - also working with Lizz for one week remotely

### Group Agenda Points

- time mismatch between dynamics and MB Mod (https://github.com/OGGM/oggm/issues/1020)
- Jan (calving)

### Action items

- in 2 weeks Lilian proposal

# Call: 2020-05-27

### Participants 

Please sign in below so we know who was here:

Name / Institution / @GitHub handle (optional)
- Matthias Dusch / University of Innsbruck / @matthiasdusch
- Anouk Vlug / University of Bremen / @anoukvlug
- Jan-Hendrik Malles / University of Bremen / @jmalles
- Fabien Maussion / University of Innsbruck/ @fmaussion 
- Lilian Schuster / University of Innsbruck / @lilianschuster


### Flash updates

- Matthias:
    - some unfinished work on the ERA5 crossvalidation
- Anouk:
    - (Still working on my thesis)
- Jan:
    - Working on how exactly to implement the ocean data algorithm 
- Fabien:
    - proposal submitted by Regine Hock (PyGEM + OGGM component).
    - Dave Rounce submitted debris paper to Nat Geo 
    - Journey for a better OGGM going good - some attempts at inversion + init_present_glaciers not great
    - OGGM-Edu apps + video for talk next week (invite on Slack)
- Lilian:
    - doing some literature research for PhD proposal

### Action items

- Jan and Li Fei have ideas for presentations next time!
- Organize breakout workshops


# Call: 2020-05-13

### Participants 

Please sign in below so we know who was here:

Name / Institution / @GitHub handle (optional)
- Matthias Dusch / University of Innsbruck / @matthiasdusch
- Anouk Vlug / University of Bremen / @anoukvlug
- Jan-Hendrik Malles / University of Bremen / @jmalles 
- Julia Eis / University of Bremen/ @juliaeis 
- Fabien Maussion / University of Innsbruck/ @fmaussion 
- Lilian Schuster / University of Innsbruck / @lilianschuster

### Flash updates

- Matthias: 
    - EGU2020: https://meetingorganizer.copernicus.org/EGU2020/EGU2020-9589.html
- Jan:
    - This time I will be there and tell you a little about my messing with Bea's calving function...
- Julia: 
    - getting rid of temp. bias for the real-world cases, will change the paper draft (where 5 different temp. biases were tested and compared to observation, we now only keep temp. bias=0K) to make the "new" method easier to understand.
- Fabien:
    - EGU week: Session + RGI meeting: https://github.com/GLIMS-RGI/rgidocs 
    - Work with ERA5 finally in a draft stage: https://github.com/OGGM/oggm/pull/1015
    - Further changes include moving of certain climate tasks to the shop
- Anouk: 
    - A little update on the single forced simulations for the Canadian Arctic.
- Lilian:
    - nothing specific
    - PhD proposal mass-balance modelling
- Li Fei:
    - working on first paper with some OGGM results inside (but not only)

### Group agenda points

- Online substitution to Workshop?


### Action items




# Call: 2020-04-29

### Participants 

Please sign in below so we know who was here:

Name / Institution / @GitHub handle (optional)
- Larissa van der Laan / University of Hannover / larissavdlaan
- Jan-Hendrik Malles / University of Bremen / @jmalles
- Jon Mackay / British Geological Survey / @hydrojon 
- Julia Eis/ University of Bremen /@juliaeis
- Anouk Vlug / University of Bremen / @anoukvlug
- Fabien Maussion / University of Innsbruck/ @fmaussion 
- Lilian Schuster / University of Innsbruck / @lilianschuster

### Flash updates

- Jan: 
    - starting to mess around with Bea's calving function...
- Julia:
    - Code cleaning of initialization module 
    - partitioning module could be updated to python3 (using Pyshed package) 
- Anouk:
    - I'm am still writting my thesis.
    - (For those that are intrested I can tell a bit about the figure I uploaded last week in the surface mass balance channel.)
- Fabien:
    - Adding climate data -> some changes happening
    - Training last week went well
    - Two master theses went very well 
    - Preparing next week's EGU events
- Lilian:
    - had my defensio last Friday
    - preparing now display for EGU (project not related to OGGM) 
- Larissa:
    - cleaning up init code as well
    - CMIP5 issues
- Jon:
    - Britisch Geological Survey - Hydrologist 
    - NERC in Peru - 21st glacier retreat

    
### Group agenda points

- Figure (Anouk)

### Action items

- Workshop about MB models in OGGM



# Call: 2020-04-15

### Participants 

Please sign in below so we know who was here:

Name / Institution / @GitHub handle (optional)
- Matthias Dusch / University of Innsbruck / @matthiasdusch
- Anouk Vlug / University of Bremen / @anoukvlug
- Julia Eis/University of Bremen/ @juliaeis 
- Fabien Maussion / University of Innsbruck/ @fmaussion 
- Lilian Schuster / University of Innsbruck / @lilianschuster

### Flash updates

- Matthias: Randomized ensemble selection - a good idea?
- Anouk: Like 2 weeks ago, I am still writing my thesis.
- Julia: same as Anouk :). Only the conclusion is missing! 
- Fabien: working on OGGM again
    - OGGM Shop first steps
    - In the process of updating WGMS data: @matthias maybe some monitoring for crossval
- Lilian: nothing new
-
### Group agenda points

 


# Call: 2020-04-01

### Participants 

Please sign in below so we know who was here:

Name / Institution / @GitHub handle (optional)
- Anouk Vlug / University of Bremen / @anoukvlug
- Lilian Schuster / University of Innsbruck / @lilianschuster
- Julia Eis / University of Bremen/ @juliaeis 
- Beatriz Recinos / University of Bremen / @bearecinos
- Jan-Hendrik Malles / University of Bremen / @jmalles 
- Fabien Maussion / University of Innsbruck/ @fmaussion 

### Flash updates

- Anouk: Home office and thesis writing (not a lot to give an update on)
- Lilian: Finally managed to submit Master thesis online. I will present some results after the flash updates.
- Julia: same as Anouk: home office and writing up the thesis
- Bea: quick updates ... probably my last meeting .. some results
- Jan: learning how to perform oggm runs on cluster...
- Fabien: 
    - back to programming! feels good
    - thinking about offering an online OGGM tutorial soon
    - OGGM workshop perspectives are looking bad

### Group agenda points

- Lilian: Presentation of some results of Master Thesis 
  "Response time of glaciers using the Open Global Glacier Model from idealised experiments to an estimate for Alpine glaciers"
 

# Call: 2020-03-18

### Participants 

Please sign in below so we know who was here:

Name / Institution / @GitHub handle (optional)
- Matthias Dusch / University of Innsbruck / @matthiasdusch
- Anouk Vlug / University of Bremen / @anoukvlug
- Julia Eis / University of Bremen / @juliaeis 
- Beatriz Recinos / University of Bremen / @bearecinos
- Jan-Hendrik Malles / University of Bremen / @jmalles
- Fabien Maussion / University of Innsbruck/ @fmaussion 
- Lilian Schuster / University of Innsbruck / @lilianschuster
 
### Flash updates

- Julia : finished the paper draft, now finishing the thesis until (hopefully end of april)
- Bea: working on the paper draft and figures
- Jan: short presentation of paper draft(?), starting to work with OGGM on glacier-ocean interactions
- Fabien: 
    - a lot a lot of co-author work and student theses to read. Not the most productive time right now
- Lilian: correcting Master's Thesis
- Matthias: Some work on DEMs.
 

# Call: 2020-03-04

### Participants 

Please sign in below so we know who was here:

Name / Institution / @GitHub handle (optional)
- Matthias Dusch / University of Innsbruck / @matthiasdusch
- Larissa van der Laan/ University of Hannover/ @larissavdlaan
- Fabien Maussion / University of Innsbruck/ @fmaussion
- Beatriz Recinos /University of Bremen/ @bearecinos (just came from 3 weeks break)


### Flash updates

- Larissa:
    - paper with Julia - almost ready for co-authors 
    - starting work with Adam Scaife (Met Office) on decadal re-forecasts with CMIP5 multimodel ensemble
- Matthias: 
    - Two new DEMs in OGGM: Alaska and Copernicus DEM
    - https://rgitools.readthedocs.io/en/latest/dems.html
- Fabien:
    - some pre-processing work for David Rounce's debris thickness project 
    - small proposal sent for financial support for Lizz visit


### Action items 


# Call: 2020-02-19

### Participants 

Please sign in below so we know who was here:

Name / Institution / @GitHub handle (optional)
- Matthias Dusch / University of Innsbruck / @matthiasdusch
- Anouk Vlug / University of Bremen / @anoukvlug
- Julia Eis / University of Bremen / @juliaeis
- Fabien Maussion / University of Innsbruck/ @fmaussion
- Jan-Hendrik Malles / University of Bremen / @jmalles
- Lilian Schuster / University of Innsbruck / @lilianschuster
- Li Fei / Institute of Tibetan Plateau Research 

### Flash updates

- Matthias: LIA reconstructions using model-ensemble
- Julia: back from Kick-off of new project (Allocating Responsibility for regional glacier-related see-level change(RespOnSe))
- Fabien:
    - Work with David Rounce quite succesful - https://github.com/drounce/PyGEM - some implications for OGGM
    - Calving PR is merged: https://oggm.org/2020/02/16/calving-param/
    - Proposal sent to H2020 about overshoots
- Lilian:
    - Finishing master's thesis and thinking about the future of response time
- Li Fei:
    - PhD Student from [ITP](http://english.itpcas.cas.cn/). Staying for one year in Innsbruck with a grant from Chinese Academy of Science. We will work on ice thickness estimates in HMA.
- Jan: 
    - Finished paper draft - starting to work with OGGM


### Action items 

Jan will present in two weeks


##  Call: 2020-02-05

### Participants 

Please sign in below so we know who was here:

Name / Institution / @GitHub handle (optional)
- Matthias Dusch / University of Innsbruck / @matthiasdusch
- Anouk Vlug / University of Bremen / @anoukvlug
- Julia Eis/University of Bremen/ @juliaeis
- Beatriz Recinos/University of Bremen/ @bearecinos
- Fabien Maussion / University of Innsbruck/ @fmaussion
- Lilian Schuster / University of Innsbruck / @lilianschuster
- Zora Schirmeister / University of Innsbruck / @zschirmeister

### Flash updates

- Anouk
    - RACMO OGGM comparison for the CAA
- Julia
    - preparing a presentation about the new project (Allocating Responsibility for Regional Glacier-Related Sea-Level change) for the project meeting next week
- Bea
    - updates about the calving law calibration in Greenland.
- Fabien
    - David Rounce is here, plenty of ideas and possible developments for OGGM: [PyGEM](https://github.com/drounce/PyGEM) ([paper 1](https://www.frontiersin.org/articles/10.3389/feart.2019.00331/full) and [paper 2](https://www.cambridge.org/core/journals/journal-of-glaciology/article/quantifying-parameter-uncertainty-in-a-largescale-glacier-evolution-model-using-bayesian-inference-application-to-high-mountain-asia/61D8956E9A6C27CC1A5AEBFCDADC0432))
    - We went to IASC arctic glaciology meeting
    - Updates to time stepping scheme are finally merged: https://oggm.org/2020/01/18/stability-analysis/, https://github.com/OGGM/oggm/pull/931
    - Some discussions with Timo on Hardware about multiproc
- Matthias: No real updates. Working on PhD-concept, wondering about 'Dynamic Calibration'
- Lilian: writing master thesis
- Zora: template for map with plot

### Action items 

- Matthias is testing the new time stepping scheme 
- Long term: adapt Zora's template to the crossval webpage

### Agenda




## Call: 2020-01-22

### Participants 

Please sign in below so we know who was here:

Name / Institution / @GitHub handle (optional)
- Matthias Dusch / University of Innsbruck / @matthiasdusch
- Beatriz Recinos / University of Bremen / @bearecinos
- Anouk Vlug / University of Bremen / @anoukvlug
- Fabien Maussion / University of Innsbruck/ @fmaussion
- Julia Eis/ University of Bremen /@
- Lilian Schuster / University of Innsbruck / @lilianschuster

### Flash updates

- Matthias:
   - RGI meeting in Zürich
   - RGI-TOPO dataset: https://rgitools.readthedocs.io/en/latest/dems.html
- Bea:
    - advances with the RACMO data and the k parameter calibration: https://gist.github.com/bearecinos/972b5680aa2e7e8b3d1f3aea64b63dbd
- Anouk:
    - OGGM compared to RACMO SMB for the Canadian Arctic Archipelago
    - Forcing OGGM with ERA datasets https://github.com/OGGM/oggm/pull/932
- Fabien:
    - settled on a numerical time step: https://oggm.org/2020/01/18/stability-analysis/ (much better than before)
    - Experiments with a new concept to replace t*: b* (!!!). Not super effective so far
    - Visit David Rounce beginning of February 
- Julia: 
    - nothing to tell, still writing up the 3rd paper
- Lilian:
    - nothing to tell, writing master thesis and struggling with statistics

### Action items 

- "OGGM Webinars?" idea to follow 


### Agenda




## Call: 2020-01-08

### Participants 

Please sign in below so we know who was here:

Name / Institution / @GitHub handle (optional)
- Matthias Dusch / University of Innsbruck / @matthiasdusch
- Beatriz Recinos / University of Bremen / @bearecinos
- Anouk Vlug / University of Bremen / @anoukvlug
- Julia Eis/ University of Bremen/ @juliaeis
- Fabien Maussion / University of Innsbruck/ @fmaussion
- Lilian Schuster / University of Innsbruck / @lilianschuster


### Flash updates

- Matthias:
    - Going to EGU and AGM
- Bea:
    - New year's resolutions with OGGM :smiley: 
- Anouk:
    - Currently working on ArcTrain fellowship proposal
- Julia:
    - finding tidewater glaciers that are not anymore today, but could have been in the past
- Fabien:
    - did the numerical runs Alex asked for, results look good
    - RGI Meeting with Matthias tomorrow
- Lilian:
    - working on writing my Master Thesis
    - found large differences in the response time estimates for CRU and HISTALP


### Agenda

- Share organisation of OGGM metting between Bremen and Innsbruck? Maybe later this year?
- Running OGGM with ERA data 
- Current backwards incompatible developments in OGGM

## Call: 2019-12-18

### Participants 

Please sign in below so we know who was here:

Name / Institution / @GitHub handle (optional)
- Matthias Dusch / University of Innsbruck / @matthiasdusch
- Anouk Vlug / University of Bremen / @anoukvlug
- Julia Eis / University of Bremen/ @juliaeis
- Fabien Maussion / University of Innsbruck/ @fmaussion


### Flash updates

- Matthias:
    - had a presentation to the climate seminar last week
- Fabien:
    - MIT proposal with Lizz not funded: alternative will be an EGU trip for her followed by research stay in Innsbruck
    - Numerics run are done, not analyzed yet because no time
    - Hopefully a big push in OGGM over the next weeks, important because David Rounce is coming for two weeks in February
- Anouk:
    - Extention for revised version of the manuscript to March 1st.
- Julia: 
    - Paper is published
    - working on 2nd paper draft

### Agenda

- OGGM at EGU: who presents what and where? Mind our new session: https://meetingorganizer.copernicus.org/EGU2020/session/34742 
- Question from Anouk for Fabien about the scheduled updates in OGGM
- Discuss a (semi-)open slack channel for general support (leftover from two weeks ago)
- Next meeting on January 8th!

## Call: 2019-12-04

Hello and welcome to the team meeting!

### Participants 

Please sign in below so we know who was here:

Name / Institution / @GitHub handle (optional)
- Matthias Dusch / University of Innsbruck / @matthiasdusch
- Anouk Vlug (until 14:45) / University of Bremen / @anoukvlug 
- Fabien Maussion / University of Innsbruck / @fmaussion
- Beatriz Recinos / University of Bremen / @bearecinos
- Julia Eis (until 14:45) /University of Bremen /@juliaeis
- Larissa van der Laan/ University of Hannover/ @larissavdlaan
- Jan-Hendrik Malles (until 14:45) / University of Bremen / @Jan
- Zora Schirmeister / University of Innsbruck / @zschirmeister
- Lilian Schuster / University of Innsbruck / @lilianschuster


### Flash updates

- Matthias:
    - some DEM statistics
    - 1500 runs of glacier length change
- Anouk:
    - manuscript 1 update
- Fabien:
    - discussion about numerics with Alex: https://github.com/OGGM/oggm/issues/909
- Bea:
    - updates on Greenland paper.
- Julia: 
    - comparison of reconstructions with WGMS data
- Larissa:
    - SMB bias correlations, continuous runs for WGMS glaciers
- Jan: 
    - new WGMS reference data
- Zora:
    - App-Demo
- Lilian:
    - bedrock depression at the terminus can have a large influence on current response time of a glacier
    - OGGM glacier length definition:
https://github.com/OGGM/oggm/issues/914

### Agenda

- Questions by Anouk
    - Precip: https://cluster.klima.uni-bremen.de/~github/crossval/1.1.2.dev41+g137bd57/cru_extended.html
- Update by Bea
- Discuss a (semi-)open slack channel for general support

### Action items

- Bea modifications to salem in order to read RACMO's Greenland grid.

## No call on 2019-11-30 (Glaciology position hearings in Innsbruck)


## Call: 2019-11-13

Hello and welcome to the team meeting!

### Participants 

Please sign in below so we know who was here:

Name / Institution / @GitHub handle (optional)
- Fabien Maussion / University of Innsbruck / @fmaussion
- Anouk Vlug / University of Bremen / @anoukvlug 
- Julia Eis / University of Bremen/ @juliaeis
- Melissa Mengert / University of Bremen
- Jan-Hendrik Malles / University of Bremen / @Jan
- Larissa van der Laan / University of Hannover / @larissavdlaan
- Zora Schirmeister/ University of Innsbruck / @zschirmeister
- Lilian Schuster / University of Innsbruck / @lilianschuster
- Matthias Dusch / University of Innsbruck / @matthiasdusch
- Patrick Schmitt / University of Innsbruck / @pat-schmitt

### Flash updates

- Fabien:
    - DFG proposal submitted
    - Ben's intercomparison paper looks cool! 
    - Start thinking about the climate data set-up
    - Going to https://nag.iasc.info/workshop
- Julia:
    - reconstructing WGMS glaciers for comparison with SMB data
    - busy cluster the next week 
- Melissa:
    - preparation of R-tutorials (Methods in Climatology)
    - translation of "Data Analysis"-Course from R into Python 
    - slowly getting started with OGGM
- Anouk:
    - Putting recent mass loss in the Canadian Arctic in perspective
    - Netherlands Polar Program Symposium is next week https://www.nwo.nl/en/research-and-results/programmes/alw/netherlands-polar-programme/symposium-2019.html
- Larissa:
    - working on the crossvalidation with SMB bias from Julia's   reconstruction
- Lilian:
    - started to calculate response times for alpine glaciers 
      (so far: for one time point)
    - thinking about how to describe response time statistically
- Jan:
    - not available
- Matthias:
    - All global DEMs in working
- Zora:
    - second App almost done
- Patrick:
    - Simulater app

### General agenda

https://cluster.klima.uni-bremen.de/~github/crossval/1.1.2.dev41+g137bd57/cru_extended.html

### Specific agenda points

- Bokeh Apps task force:
    - problems between `.show()` and `.servable()`
    - problems with the explorer app
    - TODOs

### Action items
OGGM version 2 meeting one day?

Anouk may present results in two weeks?

Zora demo in two weeks

## Call: 2019-10-29

Hello and welcome to the team meeting!

### Participants 

Please sign in below so we know who was here:

Name / Institution / @GitHub handle (optional)

- Fabien Maussion / University of Innsbruck / @fmaussion
- Anouk Vlug (if good enough internet connection) / University of Bremen / @anoukvlug
- Jan-Hendrik Malles / University of Bremen / @Jan
- Julia Eis / University of Bremen / @juliaeis
- Lilian Schuster / University of Innsbruck / @lilianschuster

### Flash updates

- Fabien:
    - DFG proposal advancing well (deadline Nov 6)
    - Three (!) support letters for submitted project proposals this week
    - Not much news on the codebase (unfortunately), but progress by Matthias on the DEM issue
- Julia:
    - still writing the following up study 
    - will not defend on 28th Nov. 
    - started a global run on the ZARM-cluster (10 nodes, at Uni Bremen)
    - Larissa van der Laan will visit us next week
- Jan:
    - Updating WGMS MB reference data
- Lilian:
    - analysed response time of glaciers with some idealized glacier experiments 
    - started on response time of real glaciers with first a case study of Hintereisferner 
    - is now thinking about what to do next!

### Agenda

- Short Hackathon report
- Time for a new blog post
- Things have stalled a little on GitHub and Slack -> what's the reason?
- Possible student from Canada?

## Call: 2019-10-16

No call this week


## OGGM-Edu roadmap call: 2019-10-04

- Fabien Maussion / University of Innsbruck 
- Lizz Ultee / MIT
- Zora Schirmeister / University of Innsbruck
- Patrick 
- Daniel

### Updates

- retour Peru workshop Lizz
    - Spanish notebooks: https://github.com/ehultee/CdeC-glaciologia
    - Recommendation for OGGM-Edu: more guidance on OGGM-Edu website on how to start a repo and add helper functions.
- apps Zora:
    - Update on the new glacier explorer app -> made great progress with the new data, but the app needs some re-arrangement in screen
    - The other app needs filling
- apps Patrick
    - showed the app with new tabs serving various purposes (e.g. advanced mode, advanced plots). Main change is the time-series plots (called "logger plots") which are allowing to see changes in volume. The app is great and almost reading to be served. Performance is going to be a key issue for online use.
- retour development process Daniel (last two notebooks) and associated questions
    - three notebooks developped: temperature-index models, mass-balance, glacier advance and retreat
    - noticed difficulties in deciding what to do next, and overlap with OGGM tutorial notebooks 

### Agenda

General discussion about state and fate of OGGM-Edu. Mainly we are happy with the state of the project:
- **the apps** are uncontroversial and can continue development. The technical issue will be how to serve them online. For local application, either an executable or, better, a container based workflow
- there is work to do on the documentation of the project. What do we try to achieve? Who is the main audience? Once we have sorted out these questions the future work is going to be easier.
- we discussed the possibility to simplify the modelling workflow with dedicated, more specialized objects which are easier to work with and build upon. It remains open whether this is a good idea or not... 

### Specific action items 

- use notebook 7 from Lizz' class and translate it back in OGGM-Edu
- continue app development and facilitate deployment (key actor here: Timo + ourselves for the local deploy)
- brainstorm about a new "OGGM-Edu" with simpler objects and simpler workflows

## Call: 2019-10-02

Hello and welcome to the team meeting!

### Participants 

Please sign in below so we know who was here:

Name / Institution / @GitHub handle (optional)

- Fabien Maussion / University of Innsbruck / @fmaussion
- Beatriz Recinos / University of Bremen / @bearecinos
- Anouk Vlug / University of Bremen / @anoukvlug
- Julia Eis/ University of Bremen /@juliaeis
- Lilian Schuster/ University of Innsbruck/ @lilianschuster
- Matthias Dusch / UIBK / @matthiasdusch
- Jan-Hendrik Malles / University of Bremen / @jmalles
- Melissa Mengert / University of Bremen / @mmengert

### Flash updates

- Fabien:
    - [Minor changes](https://github.com/OGGM/oggm/pull/873) in numpy's clip lead to [performance gain](https://cluster.klima.uni-bremen.de/~github/asv/#/)
    - Made a new OGGM tag version (v1.1.2) to accomodate for Bea's paper
    - Disk space issue in hub.oggm.org
    - Working on DFG and RGI proposals
- Bea:
    - Paper update (Status: Copy-Editing (TC))
    - Update on calving in Greenland. Wrote a simple [notebook](https://gist.github.com/bearecinos/870e325c62aabbdda298a819ac5362e1) about the methods to follow.
    - Trying to make RACMO data fit to each glacier grid.
- Matthias:
    - Just some plots about glacier length change in the last 150yrs
    - Explained Multiobjective optimisation as per: https://www.the-cryosphere.net/13/469/2019/
- Julia: 
    - revised manuscript for the TCD paper
    - starting writing-up the next paper (Comparisons with Leclercq)
- Anouk:
    - back from Canada (ArcTrain Meeting) 
    - first paper still under review (editor had to look for new reviewers)
    - consider applying to ArcTrain fellowship to write a follow-up proposal. (The ArcTrain fellowship is a 6-month contract starting after the defense that can be used to finish manuscripts and write a research proposal.)
- Lilian
    - Hello! 
    - Master thesis in ACINN about the response time of glaciers.
    - First results coming soon.
- Jan
    - Hello!
    - PhD student in Bremen with ArcTrain - coupling with ocean model
    - Started yesterday
    - Background: master thesis with Ben in Bremen
- Melissa
    - Hello!
    - PhD student in Bremen - seasonal water availability with OGGM
    - On university money (like Bea) so also some teaching to do
    - Background: master thesis at AWI Bremerhaven under supervision of Olaf Eisen on surface mass balance changes in DML, East Antarctica

### Agenda

- Future licence change
- Strategy for IPCC AR6 deadline: end of 2019
- Hacktoberfest 2019!
- Bea's notebook

### Specific group discussion

- Fabien with Matthias about RGI job
- Fabien with Moritz about Grindelwald project report 

## No call on 2019-09-18 (field work)

## Call: 2019-09-04

Hello and welcome to the team meeting!

### Participants 

Please sign in below so we know who was here:

Name / Institution / @GitHub handle (optional)

- Fabien Maussion / University of Innsbruck / @fmaussion
- Anouk Vlug / University of Bremen / @anoukvlug 
- Julia Eis/ University of Bremen /@juliaeis
- Zora Schirmeister/ University of Innsbruck / @zschirmeister
- Matthias Dusch / University of Innsbruck / @matthiasdusch
- Timo Rothenpieler / University of Bremen / @TimoRoth
- Beatriz Recinos / University of Bremen / @bearecinos

### Flash updates

- Fabien:
    - Played around with ERA5: https://fabienmaussion.info/2019/08/29/era5/
    - Added thesis topics to issues: https://github.com/OGGM/oggm/issues?q=is%3Aissue+is%3Aopen+label%3A%22thesis+topic%22
    - Big rush before IMC2019
- Julia:
    - authors response for discussion paper: https://www.the-cryosphere-discuss.net/tc-2019-68/
    - Real-world applications: comparisons with Leclercq Database 
    - Writing-up the thesis (¡defense (probably) 28th November 10'am!)
- Zora: 
    - Status glacier app -> the technical bits are solved, now we need to decide content 
    - https://github.com/zschirmeister/glacier-explorer
- Anouk:
    - Update on the runs forced with the CESM-LME single forced simulations and the plan to make an ensemble of control runs based on the 1 CESM-LME control simulation.
- Timo:
    - errors on node 01 probably related to RAM errors
    - new issues with conda
- David:
    - since Grenoble: draft last millenium multiple climate models papers (global analog to climpast paper from Hugues)
    - will send the draft when ready
- Matthias:
    - working on updates on the poster for IMC
    - holidays last week ;-)

### Agenda

- the OGGM license (Fabien): https://github.com/OGGM/oggm/issues/858
- the stability issue encountered by Julia (Fabien): https://github.com/OGGM/oggm/issues/860
- Question on Leclerc Dataset - MERGE it this afternoon! https://github.com/OGGM/oggm-sample-data/pull/3
- Glacier app from Zora: discussion about what will be the goals of the app and synergy with cross-val website 
    - -> open an issue on github to specify the goals of the app

### Items for next time

- Julia has some results (WIP)


## Call: 2019-08-21

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

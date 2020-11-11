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

- Is HackMD laggy somehow? I put the very old notes in [another doc](https://github.com/fmaussion/hackmd-notes/blob/master/OGGM-Notes-Legacy.md)
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

## Older notes 

See https://github.com/fmaussion/hackmd-notes/blob/master/OGGM-Notes-Legacy.md

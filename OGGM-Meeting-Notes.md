# OGGM Open Meeting 

###### tags: `oggm` `meeting notes`

About the format:
- **Flash updates**: quick round of short updates (~2 minutes), request of additional agenda items for longer discussions
- **Group agenda points**: longer, open discussion points of the day. Could be something that needs input from all participants, a discussion about model choices, or a prepared presentation from one of the members. Note that **our goal is to keep "Flash updates" + "Open agenda" under one hour** in order to keep a dynamic meeting.
- **Specific discussion:** more technical items that may not be of interest to everyone (e.g. about a specific problem, master thesis, etc.). These will take place after the official part.
- **Action items**: what needs to be done after the meeting and by who
- **Move to next meeting**: items that couldn't be discussed this time

# Call: 2021-11-17

### Participants 

Please sign in below so we know who will be/was here:

Name / Institution / @GitHub handle (optional)
- Anouk Vlug / University of Innsbruck / @anoukvlug
- Jan-Hendrik Malles / University of Bremen / @jmalles 
- Romain Hugonnet / ETH Zürich & University of Toulouse / @rhugonnet
- Niklas Richter / University of Innsbruck/ @Richteny
- Samar Minallah / University of Michigan Ann Arbor
- Muhammad Shafeeque / University of Bremen
- Hamid Mojtabavi / University of Bremen /@Hamid Mojtabavi
- Fabien Maussion / University of Innsbruck/ @fmaussion 
- Patrick Schmitt / University of Innsbruck / @pat-schmitt

### Flash updates
- Anouk
    - ELA diagnostics: https://github.com/OGGM/oggm/pull/1333
- Jan
    - Working on bringing Romain's and Will's data together for frontal ablation calibration/projection
    - Start writing Methods section for a corresponding paper
- Lilian Schuster / University of Innsbruck / @lilianschuster
    - PhD concept almost ready to "submit" it to Fabien 
    - will work on documenting the different quality check and temperature bias correction methods of OGGM and on generalising error analysis workflows, any comments are welcome
    - happy to hear Romain's uncertainty propagation talk
- Fabien
    - Managed to delegate some work to Lily and Patrick
    - Not much new code on OGGM, mosty docs and fixes. New release soon.
- Patrick
    - new app now on the server in bremen (bokeh.oggm.org), release on OGGM-Edu website coming soon
    - start working on an dynamic spinup function for the initialisation of OGGM runs
    - programming work on COMBINE


### Group Agenda Points
- Presentation by Romain on *How to propagate uncertainties from local to regional scales?*

### Action items


# Call: 2021-11-03

### Participants 

Please sign in below so we know who will be/was here:

Name / Institution / @GitHub handle (optional)
- Anouk Vlug / University of Innsbruck / @anoukvlug
- Muhammad Shafeeque / University of Bremen
- Samar Minallah / University of Michigan
- Hamid Mojtabavi / University of Bremen /@Hamid Mojtabavi
- Larissa van der Laan / University of Hannover / @Lvdlaan
- Patrick Schmitt / University of Innsbruck / @pat-schmitt
- Jan-Hendrik Malles / University of Bremen / @jmalles 
- Lilian Schuster / University of Innsbruck / @lilianschuster
- Fabien Maussion / University of Innsbruck/ @fmaussion 
- Lizz Ultee / Middlebury College / @ehultee


### Flash updates
- Anouk: 
    - I have started to use the new flowline diagnostics, so I will be able to prescribe the geometry of the LMR simulations during the simulations forced with the CESM-LME. 
    - I started working on getting the ELA back as diagnostic variable in OGGM. It will become a variable that can seperately be computed (it won't be a standard model run output). 
- Patrick:
    - working on final steps for the release of the new OGGM-Edu App
    - continue connecting COMBINE with OGGM GlacierDirectory
- Lilian:
    - worked last week together with Sarah that she can use the massbalance-sandbox with the hydro-model
    - writing phd concept ...
- Fabien:
    - some changes to OGGM: https://github.com/OGGM/oggm/commits/master
- Samar:
    - Trying to set up an ice sheet model (CISM) for mountain glaciers and GlacierMIP
    - Still trying to finish OGGM work for Karakoram (presenting at AGU)
    - Applying for postdoc positions 

- Lizz:
    - Supporting student working on hydro simulations of Olivares Alfa, Chile

### Group Agenda Points
- Presentations by Jan and Larissa

### Action items
- Presentation by Romain November 17th

# Call: 2021-10-20

### Participants 

Please sign in below so we know who will be/was here:

Name / Institution / @GitHub handle (optional)
- Anouk Vlug / University of Innsbruck / @anoukvlug
- Jan-Hendrik Malles / University of Bremen / @jmalles
- Muhammad Shafeeque / University of Bremen
- Jakob Steiner / ICIMOD, Uni Utrecht / @fidelsteiner
- Julia Eis/ University of Bremen / @juliaeis
- Larissa van der Laan / University/ @Lvdlaan
- Melissa Mengert / University of Bremen/ @Melissa 
- Hamid Mojtabavi / University of Bremen /@Hamid Mojtabavi
- Patrick Schmitt / University of Innsbruck /@pat-schmitt
- Lilian Schuster / University of Innsbruck / @lilianschuster
- Sarah Hanus / University of Zurich / @sarah-hanus
- Fabien Maussion / University of Innsbruck/ @fmaussion
- Samar Minallah / University of Michigan/ @minallah

### Flash updates
- Anouk:
    - I'm currently working on global simulations over the period 0-2000 CE, forced with the Last Millenium Reanalysis. I'm in the phase of calibrating the simulations. In the end this experiment will serve as base simulation for the mass balance attribution to different climate forcings over the last millenium.
- Jan:
    - Did some calibrated projections w/ and wo/ frontal ablation
    - Can show some plots soon
- Julia:
    - Coming to an end with my digression on carbon-cycle climate modeling 
    --> I would be happy to present some results about it (not OGGM related, but it is the prehistory and closely related to my following work with OGGM)
    - will start global equilibrium runs with OGGM soon
- Larissa:
    - Decision: recalibrating to Hugonnet for 2000 onward decades?
    - Finishing all decades: can show plots next meeting?
- Patrick:
    - Not much new, still working on connecting COMBINE with GlacierDirectories for testing the method on real glaciers
- Lilian:
    - writing PhD concept, but got stuck in details when comparing method implementations between models :-)
- Sarah: 
    - trying to downscale coarse climate data, however it is very slow
- Fabien:
    - did some tests simulations for glacierMIP3
    - new stop criterion for OGGM simulations
    - Geodetic calibration now happening on calendar years (also in the preprocessed directories) and also works on multiple flowlines on demand (not recommended) 
    - As always: recent commits on gitub: https://github.com/OGGM/oggm/commits/master
- Hamid
    - Working on projections with MBdebris (mass balance with debri covers)
- Samar    
    - Doing some runs in Himalaya-Karakoram region with ERA5-L atm data - preparing for AGU FM presentation
- Muhammad 
    - Recently started in Bremen and going to work on Greenland Peripheral glaciers with OGGM.
- Melissa
    - Working on a poster
    - Received comments on the sun changing colors in the graphics

### Group Agenda Points
- Day light saving time will end here on October 31st (read the clock will go 1 hour backwards). If that is not the case where you are, please keep in mind for the next meeting that the time shifts ;) 
- Journal club
- Showing some first results of the LMR simulations
- Velocity

## Older notes 

See https://github.com/fmaussion/hackmd-notes/blob/master/OGGM-Notes-Legacy.md

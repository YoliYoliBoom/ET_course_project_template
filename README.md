# **Course project:** Light versus Dark: Interactive effects of backgrounds and cues in visual search

**Authors:** *Candy Adusei*, *Sanjana Scaria Mannanal*, *Erisa Hoxha* & *Chenyue Zhou*

**Course:** *Acquisition and analysis of eye-tracking data*

**Semester:** *Summer semester 2023*

## Project Description
This project is a reproduction with extension of Kugler et al.'s experiment. The main goal of the study is to explore the interaction between background colors (especially in dark-themed interfaces) and cue types, and to determine their combined effect on the speed, accuracy, and efficiency of visual search. This research provides valuable insights for UI and UX design professionals.

## Instruction for a new student
### Environment Preparation ###
   
Ensure that your computational environment is compatible with all the necessary packages and libraries. The specifications are delineated in *requirements.txt*.

### Stimuli Generation ###

Execute *Stimuli_script.ipynb*, which is located within the *Stimuli* sub-directory of the *src* directory. This step will generate all requisite stimuli.

### Experiment Execution ###
Launch the experiments using OpenSesame.\
For the variant with a white background, utilize *Whiteexperiment.osexp*.\
For the dark-themed variant, employ *Blackexperiment.osexp*.

### Data Collection and Organization ###
Accumulate the raw eye-tracking and OpenSesame data. This should be stored in the *raw* directory.\
For each participant, construct a designated subfolder to maintain organized data collection.

### Data Preprocessing ###
Refine the raw data employing the following scripts found within the scripts directory:\
*OpenSesameDataTreatment.Rmd*\
*EyeTrackingDataTreatmentAndPlots.ipynb*\
Archive the cleansed data within the *preprocessed* sub-directory, which can be located under the primary *data* directory.

### Analysis Visualization ###
Store graphical representations of your analysis within the designated *plots* folder.

# Detecting-autism-from-reading-data-using-eye-tracking-and-machine-learning

The repository contains the following data from adult readers with and without autism: 1) gaze data from reading passages, 2) answers to reading comprehension questions, 3) the texts and questions used as stimuli, as well as any questionnaires and forms and 4) results for machine-learning classifiers aiming to detect if a person belongs to the ASD or control groups. The data was collected in three rounds corresponding to Experiments 1, 2 and 3. Additional documents include the texts used as stimuli for the experiments and the forms and questionnaires used in the study. 

For additional details on the data collection see: Yaneva, V. 2017. Text and Web Accessibility for People with Autism Spectrum Disorder. PhD Thesis, University of Wolverhampton, UK.

For details on the autism detection experiments see: Yaneva et. al. (title to be confirmed) (book chapter in preparation for Autism Spectrum Disorder: Diagnosis and Treatment)

1) Gaze data

There are altogether 6 files representing the gaze data. Three of these files correspond to the three cycles of data collection for the ASD group ("Experiment 1 ASD gaze data per participant", "Experiment 2 ASD gaze data per participant" , "Experiment 3 ASD gaze data per participant" ) and the other three contain the gaze data for the control group ("Experiment 1 Control gaze data per participant", "Experiment 2 Control gaze data per participant" , "Experiment 3 Control gaze data per participant"). Each file contains 5 gaze features and the individual word that they correspond to for each participant.

2) Preprocessed data

This folder contains the preprocessed data as input files for the experiments described in the paper.

3) Answers to the comprehension questions

Another 6 files contain the answers of each participant to three reading comprehension questions per text. The files corresponding to the answers to the comprehension questions for the ASD group are "Answers Experiment 1 ASD", "Answers Experiment 2 ASD", "Answers Experiment 3 ASD". The files corresponding to the answers to the comprehension questions for the Control group are "Answers Experiment 1 Control", "Answers Experiment 2 Control", and "Answers Experiment 3 Control". Each correct answer is represented as 1 and each incorrect answer is represented as 0.

4) Stimuli

There are 20 texts used as stimuli for the data collection, nine of which were used in Experiment 1 (1 - 9), eight in Experiment 2 (10 - 17) and three in Experiment 3 (17 - 20).

Task Descriptions, Forms and Questionnaires

This folder contains the consent form which had to be signed by each particiant, a copy of the demographic questionnaire and an easy-to-read version of the task description. The participant information sheet and the PDF file containing the formal ethical approval are not included in order to preserve anonymity.

5) Code

This folder contains the code used for the classification experiments

6) Classification results

The Results folder contains the full results for several classifiers and a full set of feature combinations for the task of autism detection.

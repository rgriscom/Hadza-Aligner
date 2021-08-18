# Hadza-Aligner
This is a speech recognition model for the [Hadza](https://en.wikipedia.org/wiki/Hadza_language) language which can be used to align phone-level transcriptions, created using the [Prosodylab-Aligner](https://github.com/prosodylab/Prosodylab-Aligner) forced alignment software (which itself is based on [HTK](https://htk.eng.cam.ac.uk/)). The model is still in development and currently only includes data from three speakers, sourced from the [Hadza ELAR collection](https://www.elararchive.org/dk05970618/). 

# Data Organization
The original labels can be found in the Labels folder (click [here](https://www.dropbox.com/sh/gch66za7cxaor8n/AAD6ytvjvcQMCxswbTs4-LSLa?dl=0) for accompanying audio recordings), and the aligned output labels can be found in the TextGrid_Output folder. The individual .TextGrid files can be used with the input audio recordings, or the .Collection files can be used with [chained audio files](https://www.dropbox.com/sh/n0r4n84m3q0ta42/AADHN30vytp0d5J_-CLhRVqna?dl=0).The .yaml file is the model itself, which can be used with Prosodylab-Aligner, and the .dict file contains a list of all words and their corresponding phones.




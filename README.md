# Predicting-NDE-score-from-EEG-PSD
In this project our group tries to train the models that were chosen on the brain waves on the EEG descriptors after DMT use. We decided to do this topic because how often we hear DMT experiences being connected to NEar Death experiences. This is based on the NDE questionaire that is a stable for explaining the similar experiences to a near death experience. We wanted to see if its possible to predict if the  participants had a low nde or high nde based only on eeg descriptors. 


Instructions

The datasets were combined to have the NDE score in them so in case of new datasets I would suggest to adjust the format of them
In "Models" its the whole pipeline(RF, LR, MLP, DM)
After the files are generated, you need to arrange the format of the csv files to fit the format of the code
The rf_feauture_importance_reformated are adjusted to the format for the second snippetfiles that work for the code "Converting to NIfTI" and provide proper results
It is possible to do the same for the mean SHAP values from logistic regression (didnt include the mean SHAP files but u can do the same as the feature importance files) 
After the creation of NIfTI files, you can open them on MRIcroGL



Notes:
The AAL.nii and AAL.xml are required for NIfTI creation code.
In case you want to visualize our results on MRIcroGL,download "Converting to NIfTI.ipynb" and the csv files that contain in the name reformatted.

Contributors: Gerard Marku, Ivaylo Mihaylov, Nikolay Nikolov, Laura Laurens

Acknowledgments
We would like to to thank proffesor Federico Zamberlan for the help and support throughout this project. The datasets were provided from him and without his help this project wouldnt have been posssible.

## Abdominal injury detection and classification
Submission notebook to the Radiological Society of North America competition hosted on kaggle. 
Ended up in the 90th percentile.
Attempted to improve the score with organ segmentation but so far unsuccesfull, hoping to get time for it in summer

rsna-make-tfrec.ipynb - misleading name since i first attempted to load the nifti data into .tfrec format but eventually decided for simple .png format

segmentation-nifti.ipynb - creating segmentation masks for each organ to improve the submissions score

rsna-train.ipynb - training the model

rsna-inference.ipynb - the actual inference of the predictions

# Code book

## Files description

Every data set has been split in separate files, one for observations of each variable, 
one for identifying the activity every subject was doing and one file that identifies 
every subject in the data set 
So for train data set we have 
- subject_train.txt : id of subject for each observation
- y_train.txt : activity 
- X_train.txt : data set. it measures 561 variables described in features.txt 

## Common files description 
features.txt : it has the labels for each variable measured 
activity_labels.txt : it has the labels for each type of activity 

The test data set is similar, so there's no need to explain it.

## Measurement 
We need to extract only the measurements of the mean and std for each variable
for each activity and each subject.

We will name the data set columns with the labels given in files 'features.txt' and
'activity_labels.txt'
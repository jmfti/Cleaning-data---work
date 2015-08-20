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

## Format of the output data newtidy.csv
it is a table with the following columns 
- x 
- activity 
- subject 
- tBodyAcc-mean()-X 
- tBodyAcc-mean()-Y 
- tBodyAcc-mean()-Z 
- tBodyAcc-std()-X 
- tBodyAcc-std()-Y 
- tBodyAcc-std()-Z 
- tGravityAcc-mean()-X 
- tGravityAcc-mean()-Y 
- tGravityAcc-mean()-Z 
- tGravityAcc-std()-X 
- tGravityAcc-std()-Y 
- tGravityAcc-std()-Z 
- tBodyAccJerk-mean()-X 
- tBodyAccJerk-mean()-Y 
- tBodyAccJerk-mean()-Z 
- tBodyAccJerk-std()-X 
- tBodyAccJerk-std()-Y 
- tBodyAccJerk-std()-Z 
- tBodyGyro-mean()-X 
- tBodyGyro-mean()-Y 
- tBodyGyro-mean()-Z 
- tBodyGyro-std()-X 
- tBodyGyro-std()-Y 
- tBodyGyro-std()-Z 
- tBodyGyroJerk-mean()-X 
- tBodyGyroJerk-mean()-Y 
- tBodyGyroJerk-mean()-Z 
- tBodyGyroJerk-std()-X 
- tBodyGyroJerk-std()-Y 
- tBodyGyroJerk-std()-Z 
- tBodyAccMag-mean() 
- tBodyAccMag-std() 
- tGravityAccMag-mean() 
- tGravityAccMag-std() 
- tBodyAccJerkMag-mean() 
- tBodyAccJerkMag-std() 
- tBodyGyroMag-mean() 
- tBodyGyroMag-std() 
- tBodyGyroJerkMag-mean() 
- tBodyGyroJerkMag-std() 
- fBodyAcc-mean()-X 
- fBodyAcc-mean()-Y 
- fBodyAcc-mean()-Z 
- fBodyAcc-std()-X 
- fBodyAcc-std()-Y 
- fBodyAcc-std()-Z 
- fBodyAccJerk-mean()-X 
- fBodyAccJerk-mean()-Y 
- fBodyAccJerk-mean()-Z 
- fBodyAccJerk-std()-X 
- fBodyAccJerk-std()-Y 
- fBodyAccJerk-std()-Z 
- fBodyGyro-mean()-X 
- fBodyGyro-mean()-Y 
- fBodyGyro-mean()-Z 
- fBodyGyro-std()-X 
- fBodyGyro-std()-Y 
- fBodyGyro-std()-Z 
- fBodyAccMag-mean() 
- fBodyAccMag-std() 
- fBodyBodyAccJerkMag-mean() 
- fBodyBodyAccJerkMag-std() 
- fBodyBodyGyroMag-mean() 
- fBodyBodyGyroMag-std() 
- fBodyBodyGyroJerkMag-mean() 
- fBodyBodyGyroJerkMag-std() 
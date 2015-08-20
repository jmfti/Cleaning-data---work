
This script will work only under this assumptions
- An existing folder in the current working directory named 'data' exists 
- Data has been extracted in the current working directory

How the script works : 
- read 2 datasets, xtrain and xtest 
- read features (features.txt) and activities (activity_labels.txt)
- merge xtrain and xtest to one data frame 
- get only the columns we are interested for (those which has mean() and std())
- read subjects and activities for each data sets (train and test, y and subjects)
- read activities and subjects for both test and train and merge them 
- do a left join of activities observations (ytrayn . ytest) with activities (activity_labels) 
so we get the activity labels for each observation 
- add activities and subjects to original data set
- write to a txt file
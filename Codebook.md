# Codebook
This is a codebook file for Human Activity Recognition Using Smartphones Dataset

Raw data was obtained from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

## Below are the list of datasets used:

/train/X_train.txt
/train/subject_train.txt
/train/y_train.txt
/test/X_test.txt
/test/subject_test.txt
/test/y_test.txt
features.txt

## Measurement units:

All the features in the data are normalized and bounded within [-1,1].

## Data reshaping:

- The 'subject' files and the 'X' files have been appended with the proper subject to their corresponding accelerometer data.

- The values in the activities column in the data set have been modified to descriptive activity names.

- A new rolled up tidy dataset ('Subject_Activity_Averages.txt') at subject and activity level.

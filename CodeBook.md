This file describes the variables, the data, and any transformations or work that I have performed to clean up the data.

The site where the data was obtained:
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
The data for the project:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
The run_analysis.R script performs the following steps to clean the data:
Read X_train.txt, y_train.txt and subject_train.txt from the "train" folder
Read X_test.txt, y_test.txt and subject_test.txt from the "test" folder

Merges the training and the test sets to create one data set

Read the features.txt file from the "/" folder and store the data in a variable called features. We only extract the measurements on the mean and standard deviation.

Uses descriptive activity names to name the activities in the data set

Appropriately labels the data set with descriptive variable names.

Creates a second, independent tidy data set with the average of each variable for each activity and each subject.
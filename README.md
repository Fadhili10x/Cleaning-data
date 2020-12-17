# Cleaning-data
The data files are related as follows:
Values of Varible Activity consist of data from “Y_train.txt” and “Y_test.txt”
values of Varible Subject consist of data from “subject_train.txt” and subject_test.txt"
Values of Varibles Features consist of data from “X_train.txt” and “X_test.txt”
Names of Varibles Features come from “features.txt”
levels of Varible Activity come from “activity_labels.txt”
So we will use Activity, Subject and Features as part of descriptive variable names for data in data frame.

Description of run_analysis.R
Firtly it downlaods and unzips the data
Then reads the activity files, subject files and features files
It then merges the test and training data sets to create one data set
Next, it extracts the mean and standard deviation for each measurement
It labels the data set with descriptive variable names
Creates a second independent tidy dataset and outputs it

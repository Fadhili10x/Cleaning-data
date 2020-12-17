# Cleaning-data
1.The data files are related as follows:
2.Values of Varible Activity consist of data from “Y_train.txt” and “Y_test.txt”
3.values of Varible Subject consist of data from “subject_train.txt” and subject_test.txt"
4.Values of Varibles Features consist of data from “X_train.txt” and “X_test.txt”
5.Names of Varibles Features come from “features.txt”
6.levels of Varible Activity come from “activity_labels.txt”
7.So we will use Activity, Subject and Features as part of descriptive variable names for data in data frame.

8.Description of run_analysis.R
9.Firtly it downlaods and unzips the data
10.Then reads the activity files, subject files and features files
11.It then merges the test and training data sets to create one data set
12.Next, it extracts the mean and standard deviation for each measurement
13.It labels the data set with descriptive variable names
14.Creates a second independent tidy dataset and outputs it

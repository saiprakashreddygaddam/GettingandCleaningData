# Getting and Cleaning Data Course Project

The run_analysis.R script does the following:

1. Downloads the dataset if it does not exist in the working directory
2. Load the activity and feature information from the respective files
3. Loads both the training and test datasets with either mean or standard deviation columns 
4. Loads the activity and subject data for each dataset, and merges those columns with the dataset
5. Merges the two datasets
6. Converts the activity and subject columns into factors
7. Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.

The end result is shown in the file tidy.txt file

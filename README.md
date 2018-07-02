# Getting_and_Cleaning_Data_Course_Project

This is the course project for the Getting and Cleaning Data Coursera course. The R script, run_analysis.R, does the following:

Step1: Download the dataset if it does not already exist in the working directory

Step2: Load the activity and feature info

Step3: Loads both the training and test datasets, keeping only those columns which reflect a mean or standard deviation

Step4: Loads the activity and subject data for each dataset, and merges those columns with the dataset

Step5: Merges the two datasets

Step6: Converts the activity and subject columns into factors

Step7: Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.

Final Result: The end result is shown in the file tidy.txt.

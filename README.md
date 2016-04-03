
# Coursera: getting and cleaning data project
Course project for Coursera "Getting and Cleaning Data" MMB.
Repo for the submission of the course project for the Johns Hopkins Getting and Cleaning Data course.
### @mmblanes
### Seville, Spain

# Overview

This project complies with the idea of getting a tidy data set that can be used for subsequent analysis.

# Making Modifications to This Script

Once you have obtained and unzipped the source files, you will need to make one modification to the R file before you can process the data. Note that on line 26 of run_analysis.R, you will set the path of the working directory to relect the location of the source files in your own directory.

# Project Summary

The following is a summary description of the project instructions included in the R script, `run_analysis.R`:

You should create one R script called run_analysis.R that does the following.
* 1. Merges the training and the test sets to create one data set.
* 2. Extracts only the measurements on the mean and standard deviation for each measurement.
* 3. Uses descriptive activity names to name the activities in the data set 
* 4. Appropriately labels the data set with descriptive activity names. 
* 5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject. (The end result is shown in the file `tidy.txt`.)



 *  Download the dataset if it does not already exist in the working directory
  
 *  Load the activity and feature info
  
 *  Loads both the training and test datasets, keeping only those columns which reflect a mean or standard deviation
  
 *  Loads the activity and subject data for each dataset, and merges those columns with the dataset
  
 *  Merges the two datasets
  
 *  Converts the activity and subject columns into factors
  
 *  Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.
  
 *  The end result is shown in the file `tidy.txt`.


# Additional Information

You can find additional information about the variables, data and transformations in the CodeBook.MD file.

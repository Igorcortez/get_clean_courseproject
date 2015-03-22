# Getting and Cleaning Data Course Project
Project of Getting and Cleaning Data on Coursera - March - 2015
##Project Description:
The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. You will be required to submit: 
1) a tidy data set as described below, 
2) a link to a Github repository with your script for performing the analysis, and 
3) a code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md. 
You should also include a README.md in the repo with your scripts. This repo explains how all of the scripts work and how they are connected.  

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

Here are the data for the project: 

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

 You should create one R script called run_analysis.R that does the following. 
  1)Merges the training and the test sets to create one data set.
  2)Extracts only the measurements on the mean and standard deviation for each measurement. 
  3)Uses descriptive activity names to name the activities in the data set
  4)Appropriately labels the data set with descriptive variable names. 
  5)From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
  
  ### What you`ll find in this repository:
  
  CodeBook.md : information about raw and tidy data set and elaboration made to transform.
  README.md: this file. 
  run_analysis.R: R script to transform raw data set in a tidy one. 
  
  ### How to create the tidy data set:
  1) download compressed raw data
  2) unzip the raw data and copy the directory UCI HAR DATASET to the cloned repository root directory
  3)Open the R Console and set working directory to the repository root using setwd() command
  4) source run_analysis.R script (it requires de plyr package): source(`run_analysis.R`)
  
In the repository root directory you`ll find the file sensor_avg_by_act_sub.txt with the tidy data set. 

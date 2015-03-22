# Getting and Cleaning data

This is repository for Course Project Codebook

## Codebook

Source (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) into a folder on your local drive

Original description: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

The attached R script (run_analysis.R) performs the following to clean up the data:

    * Merges the training and test sets to create one data set, the result of which is data frame.

    * Reads features.txt and extracts only the measurements on the mean and standard deviation for each measurement. The result is a  data frame

    * Reads activity_labels.txt and applies descriptive activity names to name the activities in the data set

    * The script also appropriately labels the data set with descriptive names

    * Last Step is to create 2nd, independent tidy data set with the average of each measurement for each activity and each subject. The result is saved as data_set_with_the_averages.txt.

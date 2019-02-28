# Project - Cleaning Data

The R script, run_analysis.R, has the following step:

* Downloads the dataset. Checks if the file already exists
* Load the activity and feature info
* Selects all column names that reflect mean or standard deviation
* Loads both the training and test datasets, selecting only above columns
* Loads the activity and subject data for each dataset, and merges those columns with the dataset
* Merges the two datasets. Train and Test
* Converts the activity and subject columns into factors
* Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.
* The end result is shown in the file tidy.txt.

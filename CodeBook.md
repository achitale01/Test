# Getting and Cleaning Data- Course Project CodeBook

## Data Sources
The data set for this project can be obtained at the following URL: 
[UCI HAR Dataset](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)

Prerequisites for the run_analysis.R script:
* the UCI HAR Dataset must be downloaded and extracted
* the UCI HAR Dataset must be availble in a directory called "UCI HAR Dataset"

Refer to the README.txt and features_info.txt files in the UCI HAR Dataset directory for details on the contents of the data set.

## run_analysis.R
The script does the following:
* Read the data sets, labels and subjects for training and testing
* Merge the two x\_, y\_ and subject data sets together for training and testing
* Identify and select only the columns that have mean or standard deviation data
* Add descriptive activity names
* Bind the x\_, y\_ and subjects into one single data set
* compute the mean values
* Write a Tidy\_UCI\_HAR.csv data file with the header and data
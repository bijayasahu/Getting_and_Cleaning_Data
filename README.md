# Getting_and_Cleaning_Data
This folder contains the output for the course project work

## Course Project
(find all project-related materials in the Dataset directory, however, the source code and the output files have been put into this main directory)

* Unzip the source (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) into a folder on your local drive, say C:\Users\yourname\Documents\R\

* Put run_analysis.R into C:\Users\yourname\Documents\R\Dataset\

* In RStudio: setwd("C:\\\\Users\\\\yourname\\\\Documents\\\\R\\\\Dataset\\\\"), followed by: source("run_analysis.R")

* Use data <- read.table("data_set_with_the_averages.txt") to read the data. It is 180x68 because there are 30 subjects and 6 activities, thus "for each activity and each subject" means 30 * 6 = 180 rows. Note that the provided R script has no assumptions on numbers of records, only on locations of files.

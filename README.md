This repository contains the R script run_analysis.R that performs the analysis outlined in the instructions. The goal is to show the ability to collect, work with, and clean a dataset for analysis. The data that was used in this project was collected from accelerometers of Samsung Galaxy S smartphone.

Files in Repository

1. run_analysis.R: This script performs the following:
  
     a. Merges training and test sets to create one data set.
   
     b. Extracts the measurements on the mean and standard deviation for each measurement
   
     c. The use of descriptive activity names to name the activities in the data set

     d. Labels the data set with descriptive variable names.

     e. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

2. CodeBook.md: This file descrives the variables, data, and any transformations or work that was done to clean up the data.

3. tidy_data.txt: This files contains the final tidy data set with the average of each variable for each activity and each subject.

Running the Script

1. Download the Data: Download the data from the following link:  
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

2. Run the script: Open R or RStudio and run the run_analysis.R script. This will read the data, perform the necessary transformations, and generate the tidy_data.txt file with the tidy data set.



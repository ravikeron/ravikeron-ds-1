# ravikeron-ds-1
Data scientist work 1
# Get_Clean_data
##For Getting and Cleaning data assignment 

### Project Description

The purpose of this project is to demonstrate ones ability to collect, work with, and clean a data set. 
The repository consists of the following files
1.run_analysis.R
2.README.md
3.CodeBook.md  - describes the variables, the data, and any transformations/work that was performed to clean up the data.   

Here are the data for the project: 
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

Clone a localcopy of this repository
Download the compressed data from the URL given above
Unzip the raw dataand copy the directory UCI HAR Dataset to the closed repository root directory 
Open R Console and set the working directory to the repository root directory mentioned above
Install plyr package
Source run_analysis.R script
The R script run_analysis.R does the following. 
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject

In the root directory the file sensor_avg_by_act_sub.txt with tidy data set is created.

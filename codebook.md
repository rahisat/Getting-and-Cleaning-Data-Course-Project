About R script

File run_analysis.R has the R script for this assignment.  

In this script, path to the data is hardcoded and it assumes the data file names are static.  So, in case the file names or folder structure in the source data changes, this script will not properly.

File with R code "run_analysis.R" perform 5 following steps (in accordance assigned task of course work):

1. Merging the training and the test sets to create one data set.
  1.1 Reading files

  1.2 Assigning column names

  1.3 Merging all data in one set

2. Extracting only the measurements on the mean and standard deviation for each measurement
  2.1 Reading column names

  2.2 Create vector for defining ID, mean and standard deviation

  2.3 Making nessesary subset from setAllInOne

3. Using descriptive activity names to name the activities in the data set

4. Appropriately labeling the data set with descriptive variable names.  This step was completed in step 1 and 2. 

5. Creating a second, independent tidy data set with the average of each variable for each activity and each subject

  5.1 Making second tidy data set

  5.2 Writing second tidy data set in txt file

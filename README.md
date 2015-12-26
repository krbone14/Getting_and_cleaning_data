# Getting_and_cleaning_data
Course project for the coursera "Getting and Cleaning Data":

The script `run_analysis.R`performs the 5 steps described in the course project's definition.

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

The script use the "plyr package" to use ddply
The end result is shown in the file `tidy_data.txt`.

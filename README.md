# Getting_and_cleaning_data
Course project for the coursera "Getting and Cleaning Data":

The dataset being used is: [Human Activity Recognition Using Smartphones](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)

The script `run_analysis.R`performs the 5 steps described in the course project's definition. The script need to be launch directly in the dataset directory (containing train ans test directory)

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

The script use the "plyr package" to use ddply.

The end result is shown in the file `tidy_data.txt`.

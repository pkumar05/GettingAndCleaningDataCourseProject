## Getting and Cleaning Data


## Task to be done

1. Merging the training and the test sets to create one data set.
2. Extracting only the measurements on the mean and standard deviation for each measurement. 
3. Using descriptive activity names to name the activities in the data set
4. Appropriately labeling the data set with descriptive activity names. 
5. From the data set in step 4,create a second, independent tidy data set with the average of each variable for each activity and each subject. 

## R script
File with R code "run_analysis.R" perform 5 steps

## variables:   
* `x_train`, `y_train`, `x_test`, `y_test`, `subject_train` and `subject_test` contain the data from the downloaded files.
* `x_data`, `y_data` and `subject_data` merge the previous datasets to further analysis.
* `features` contains the correct names for the `x_data` dataset, which are applied to the column names stored in
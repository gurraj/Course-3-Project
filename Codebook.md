

## Getting and Cleaning Data - peer assessment project (Course 3)


## The original data was transformed in the following manner

1. Merged the training and the test data sets to create a single data set.
2. Extracted only the measurements on the mean and standard deviation for each measurement. 
3. Used descriptive activity names to label the activities in the data set
4. Created a second, independent tidy data set with the average value for each of the variables in each activity and each subject. 



Since the majority of the features in the original dataset were derived or estimated to the 2nd or 3rd order from the original dataset, focus was placed on the measurements most closely related to the original data collected by the accelerometer and gyroscope - *tBodyAcc* and *tBodyGyro*. 

As a result, the variables remaining are just the calculated means and standard deviations of these sets of data - one each for the X, Y and Z dimensions:

- tBodyAcc-X
- tBodyAcc-Y
- tBodyAcc-Z
- tBodyGyro-X
- tBodyGyro-Y
- tBodyGyro-Z

Each of these has a mean and standard deviation version. Examples:

- tBodyAcc-mean()-X: Mean of base body acceleration data in the X dimension
- tBodyGyro-std()-Y: Standard deviation of base body gyroscope measurement in the Y dimension
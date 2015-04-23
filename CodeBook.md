#Study Design
The data was collected from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip then unzipped and processed by run_analysis.R. The following files were used to generate the final data set (we assume that the data was under *getdata-projectfiles-UCI HAR Dataset/UCI HAR Dataset*):

* *activity_labels.txt* - the mapping between an activity name and its code
* *features.txt* - the features names or column names for the data files *test/X_test.txt* and *train/X_train.txt*
* *test/X_test.txt* - the test data
* *test/subject_test.txt* - the test subject identification numbers
* *test/y_test.txt* - the test activity codes for rows in *test/X_test.txt*
* *train/X_train.txt* - the train data
* *train/subject_train.txt* - the tarin subject identification numbers
* *train/y_train.txt* - the train activity codes for rows in *train/X_train.txt*

#Code Book
The following columns are in the final data.frame returned by run_analysis.R (names starting with t are related to time and these starting with f are related to frequency [Hz]):
* subject - the subject identification
* activity - the subject activity
* tBodyAccmeanX
* tBodyAccmeanY
* tBodyAccmeanZ
* tBodyAccstdX
* tBodyAccstdY
* tBodyAccstdZ
* tGravityAccmeanX
* tGravityAccmeanY
* tGravityAccmeanZ
* tGravityAccstdX
* tGravityAccstdY
* tGravityAccstdZ
* tBodyAccJerkmeanX
* tBodyAccJerkmeanY
* tBodyAccJerkmeanZ
* tBodyAccJerkstdX
* tBodyAccJerkstdY
* tBodyAccJerkstdZ
* tBodyGyromeanX
* tBodyGyromeanY
* tBodyGyromeanZ
* tBodyGyrostdX
* tBodyGyrostdY
* tBodyGyrostdZ
* tBodyGyroJerkmeanX
* tBodyGyroJerkmeanY
* tBodyGyroJerkmeanZ
* tBodyGyroJerkstdX
* tBodyGyroJerkstdY
* tBodyGyroJerkstdZ
* tBodyAccMagmean
* tBodyAccMagstd
* tGravityAccMagmean
* tGravityAccMagstd
* tBodyAccJerkMagmean
* tBodyAccJerkMagstd
* tBodyGyroMagmean
* tBodyGyroMagstd
* tBodyGyroJerkMagmean
* tBodyGyroJerkMagstd
* fBodyAccmeanX
* fBodyAccmeanY
* fBodyAccmeanZ
* fBodyAccstdX
* fBodyAccstdY
* fBodyAccstdZ
* fBodyAccmeanFreqX
* fBodyAccmeanFreqY
* fBodyAccmeanFreqZ
* fBodyAccJerkmeanX
* fBodyAccJerkmeanY
* fBodyAccJerkmeanZ
* fBodyAccJerkstdX
* fBodyAccJerkstdY
* fBodyAccJerkstdZ
* fBodyAccJerkmeanFreqX
* fBodyAccJerkmeanFreqY
* fBodyAccJerkmeanFreqZ
* fBodyGyromeanX
* fBodyGyromeanY
* fBodyGyromeanZ
* fBodyGyrostdX
* fBodyGyrostdY
* fBodyGyrostdZ
* fBodyGyromeanFreqX
* fBodyGyromeanFreqY
* fBodyGyromeanFreqZ
* fBodyAccMagmean
* fBodyAccMagstd
* fBodyAccMagmeanFreq
* fBodyBodyAccJerkMagmean
* fBodyBodyAccJerkMagstd
* fBodyBodyAccJerkMagmeanFreq
* fBodyBodyGyroMagmean
* fBodyBodyGyroMagstd
* fBodyBodyGyroMagmeanFreq
* fBodyBodyGyroJerkMagmean
* fBodyBodyGyroJerkMagstd
* fBodyBodyGyroJerkMagmeanFreq
* angletBodyAccMeangravity
* angletBodyAccJerkMeangravityMean
* angletBodyGyroMeangravityMean
* angletBodyGyroJerkMeangravityMean
* angleXgravityMean
* angleYgravityMean
* angleZgravityMean

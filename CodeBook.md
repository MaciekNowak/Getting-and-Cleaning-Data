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
* tBodyAccmeanX  -  time body linear acceleration mean X
* tBodyAccmeanY  -  time body linear acceleration mean Y
* tBodyAccmeanZ  -  time body linear acceleration mean Z
* tBodyAccstdX  -  time body linear acceleration std X
* tBodyAccstdY  -  time body linear acceleration std Y
* tBodyAccstdZ  -  time body linear acceleration std Z
* tGravityAccmeanX  -  time gravity acceleration magnitude mean X
* tGravityAccmeanY  -  time gravity acceleration magnitude mean Y
* tGravityAccmeanZ  -  time gravity acceleration magnitude mean Z
* tGravityAccstdX  -  time gravity acceleration magnitude std X
* tGravityAccstdY  -  time gravity acceleration magnitude std Y
* tGravityAccstdZ  -  time gravity acceleration magnitude std Z
* tBodyAccJerkmeanX  -  time body linear acceleration jerk mean X
* tBodyAccJerkmeanY  -  time body linear acceleration jerk mean Y
* tBodyAccJerkmeanZ  -  time body linear acceleration jerk mean Z
* tBodyAccJerkstdX  -  time body linear acceleration jerk std X
* tBodyAccJerkstdY  -  time body linear acceleration jerk std Y
* tBodyAccJerkstdZ  -  time body linear acceleration jerk std Z
* tBodyGyromeanX  -  time body angular velocity mean X
* tBodyGyromeanY  -  time body angular velocity mean Y
* tBodyGyromeanZ  -  time body angular velocity mean Z
* tBodyGyrostdX  -  time body angular velocity std X
* tBodyGyrostdY  -  time body angular velocity std Y
* tBodyGyrostdZ  -  time body angular velocity std Z
* tBodyGyroJerkmeanX  -  time body angular velocity jerk mean X
* tBodyGyroJerkmeanY  -  time body angular velocity jerk mean Y
* tBodyGyroJerkmeanZ  -  time body angular velocity jerk mean Z
* tBodyGyroJerkstdX  -  time body angular velocity jerk std X
* tBodyGyroJerkstdY  -  time body angular velocity jerk std Y
* tBodyGyroJerkstdZ  -  time body angular velocity jerk std Z
* tBodyAccMagmean  -  time body linear acceleration magnitude mean
* tBodyAccMagstd  -  time body linear acceleration magnitude std
* tGravityAccMagmean  -  time gravity acceleration mean
* tGravityAccMagstd  -  time gravity acceleration std
* tBodyAccJerkMagmean  -  time body linear acceleration jerk magnitude mean
* tBodyAccJerkMagstd  -  time body linear acceleration jerk magnitude std
* tBodyGyroMagmean  -  time body angular velocity magnitude mean
* tBodyGyroMagstd  -  time body angular velocity magnitude std
* tBodyGyroJerkMagmean  -  time body angular velocity jerk magnitude mean
* tBodyGyroJerkMagstd  -  time body angular velocity jerk magnitude std
* fBodyAccmeanX  -  frequency body linear acceleration mean X
* fBodyAccmeanY  -  frequency body linear acceleration mean Y
* fBodyAccmeanZ  -  frequency body linear acceleration mean Z
* fBodyAccstdX  -  frequency body linear acceleration std X
* fBodyAccstdY  -  frequency body linear acceleration std Y
* fBodyAccstdZ  -  frequency body linear acceleration std Z
* fBodyAccmeanFreqX  -  frequency body linear acceleration mean frequency X
* fBodyAccmeanFreqY  -  frequency body linear acceleration mean frequency Y
* fBodyAccmeanFreqZ  -  frequency body linear acceleration mean frequency Z
* fBodyAccJerkmeanX  -  frequency body linear acceleration jerk mean X
* fBodyAccJerkmeanY  -  frequency body linear acceleration jerk mean Y
* fBodyAccJerkmeanZ  -  frequency body linear acceleration jerk mean Z
* fBodyAccJerkstdX  -  frequency body linear acceleration jerk std X
* fBodyAccJerkstdY  -  frequency body linear acceleration jerk std Y
* fBodyAccJerkstdZ  -  frequency body linear acceleration jerk std Z
* fBodyAccJerkmeanFreqX  -  frequency body linear acceleration jerk mean frequency X
* fBodyAccJerkmeanFreqY  -  frequency body linear acceleration jerk mean frequency Y
* fBodyAccJerkmeanFreqZ  -  frequency body linear acceleration jerk mean frequency Z
* fBodyGyromeanX  -  frequency body angular velocity mean X
* fBodyGyromeanY  -  frequency body angular velocity mean Y
* fBodyGyromeanZ  -  frequency body angular velocity mean Z
* fBodyGyrostdX  -  frequency body angular velocity std X
* fBodyGyrostdY  -  frequency body angular velocity std Y
* fBodyGyrostdZ  -  frequency body angular velocity std Z
* fBodyGyromeanFreqX  -  frequency body angular velocity mean frequency X
* fBodyGyromeanFreqY  -  frequency body angular velocity mean frequency Y
* fBodyGyromeanFreqZ  -  frequency body angular velocity mean frequency Z
* fBodyAccMagmean  -  frequency body linear acceleration magnitude mean
* fBodyAccMagstd  -  frequency body linear acceleration magnitude std
* fBodyAccMagmeanFreq  -  frequency body linear acceleration magnitude mean frequency
* fBodyBodyAccJerkMagmean  -  frequency body linear acceleration jerk magnitude mean
* fBodyBodyAccJerkMagstd  -  frequency body linear acceleration jerk magnitude std
* fBodyBodyAccJerkMagmeanFreq  -  frequency body linear acceleration jerk magnitude mean frequency
* fBodyBodyGyroMagmean  -  frequency body angular velocity magnitude mean
* fBodyBodyGyroMagstd  -  frequency body angular velocity magnitude std
* fBodyBodyGyroMagmeanFreq  -  frequency body angular velocity magnitude mean frequency
* fBodyBodyGyroJerkMagmean  -  frequency body angular velocity jerk magnitude mean
* fBodyBodyGyroJerkMagstd  -  frequency body angular velocity jerk magnitude std
* fBodyBodyGyroJerkMagmeanFreq  -  frequency body angular velocity jerk magnitude mean frequency
* angletBodyAccMeangravity  -  angle tbody linear acceleration Mean gravity
* angletBodyAccJerkMeangravityMean  -  angle tbody linear acceleration jerk gravity mean      
* angletBodyGyroMeangravityMean  -  angle tbody angular velocity mean gravity mean
* angletBodyGyroJerkMeangravityMean  -  angle tbody angular velocity jerk Mean gravityMean
* angleXgravityMean  -  angle X gravityMean
* angleYgravityMean  -  angle Y gravityMean
* angleZgravityMean  -  angle Z gravityMean

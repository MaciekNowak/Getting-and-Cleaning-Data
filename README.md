Getting-and-Cleaning-Data
=========================

The script run_analysis.R expects that the directory getdata-projectfiles-UCI HAR Dataset/UCI HAR Dataset exists and it consists of the data extracted from the zip file provided in the assigment. 

The script performs the following tasks:
1.  Reads (function `loadActivityLabels()`) *getdata-projectfiles-UCI HAR Dataset/UCI HAR Dataset/activity_labels.txt* that maps activities like WALKING with their codes and keeps this mapping in the `activityLabels` data.frame.
2.  Loads (function `loadFeatures()`) *getdata-projectfiles-UCI HAR Dataset/UCI HAR Dataset/features.txt* with features names to a character vector (`features`).
3.  Filters the features related to the mean and standard deviation, the filtering string is defined in `featurePattern` character string. The filtering creates two vectors, one with the selected feature indexes (`featureIdx`) and second with selected features names(`featureNames`).
4.  Loads the testing and training data (function `loadData()`) into the `testData` and `trainData` data.frames respectively. By loading the data I understand loading the actual data from *getdata-projectfiles-UCI HAR Dataset/UCI HAR Dataset/test/X_test.txt|X_train.txt*, the subject data from *getdata-projectfiles-UCI HAR Dataset/UCI HAR Dataset/test/subject_test.txt|subject_train.txt* and the activity codes from *getdata-projectfiles-UCI HAR Dataset/UCI HAR Dataset/test/y_test.txt|y_train.txt* and then merging the three set together.
5.  The `testData` and `trainData` data.frames are merged into the `allData` date.frame.
6.  The `cleanColumnNames()` function creates a clean column names and assignes them to `allData`.
7.  The data is aggregated (using the `aggregate()` R function) and assigned to the `finalResult` data.frame.
8.  `finalResult` is written to *run_analysis.txt* that will be uploaded to the Coursera web site.
9.  `finalResult` is returned as requested.




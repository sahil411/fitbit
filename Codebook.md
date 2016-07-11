
# THIS CODEBOOK IS FOR THE GETTING AND CLEANING THE DATA COURSE PROJECT.
CREATED BY SAHIL JAGDALE.


#PROCESSING:

The "run_analysis.R" file performs the given instructions on data and process the number of steps for the final clean data output.
Some steps performed in this R file are listed below.

1) test and train detasets are processed and mearged into one dataset.

2) Names for the data column are given according to "features.txt" file.

3) columns those having mean and standard deviation value are selected for the datasets and other values excluded for analysis.

4) Activity identifiers are replaced with the names labels given in "activity_labels.txt" file.

5) Invalid characters and duplicate names or variables are removed while doing cleaning of data.

6) After subject and activity the mean is calculated for the column variables.

7) the output dataset is written to a file "run_output.txt"


#COLUMNS IN THE OUTPUT FILE:

Columns used for output files are listed below.


subject_id   :- ID of the participant
activity_labels :- name of the activity

    tBodyAcc_mean_X
    tBodyAcc_mean_Y
    tBodyAcc_mean_Z
    tGravityAcc_mean_X
    tGravityAcc_mean_Y
    tGravityAcc_mean_Z
    tBodyAccJerk_mean_X
    tBodyAccJerk_mean_Y
    tBodyAccJerk_mean_Z
    tBodyGyro_mean_X
    tBodyGyro_mean_Y
    tBodyGyro_mean_Z
    tBodyGyroJerk_mean_X
    tBodyGyroJerk_mean_Y
    tBodyGyroJerk_mean_Z
    tBodyAccMag_mean
    tGravityAccMag_mean
    tBodyAccJerkMag_mean
    tBodyGyroMag_mean
    tBodyGyroJerkMag_mean
    fBodyAcc_mean_X
    fBodyAcc_mean_Y
    fBodyAcc_mean_Z
    fBodyAccJerk_mean_X
    fBodyAccJerk_mean_Y
    fBodyAccJerk_mean_Z
    fBodyGyro_mean_X
    fBodyGyro_mean_Y
    fBodyGyro_mean_Z
    fBodyAccMag_mean
    fBodyAccJerkMag_mean
    fBodyGyroMag_mean
    fBodyGyroJerkMag_mean
    tBodyAcc_std_X
    tBodyAcc_std_Y
    tBodyAcc_std_Z
    tGravityAcc_std_X
    tGravityAcc_std_Y
    tGravityAcc_std_Z
    tBodyAccJerk_std_X
    tBodyAccJerk_std_Y
    tBodyAccJerk_std_Z
    tBodyGyro_std_X
    tBodyGyro_std_Y
    tBodyGyro_std_Z
    tBodyGyroJerk_std_X
    tBodyGyroJerk_std_Y
    tBodyGyroJerk_std_Z
    tBodyAccMag_std
    tGravityAccMag_std
    tBodyAccJerkMag_std
    tBodyGyroMag_std
    tBodyGyroJerkMag_std
    fBodyAcc_std_X
    fBodyAcc_std_Y
    fBodyAcc_std_Z
    fBodyAccJerk_std_X
    fBodyAccJerk_std_Y
    fBodyAccJerk_std_Z
    fBodyGyro_std_X
    fBodyGyro_std_Y
    fBodyGyro_std_Z
    fBodyAccMag_std
    fBodyAccJerkMag_std
    fBodyGyroMag_std
    fBodyGyroJerkMag_std

    MORE INFORMATION ABOUT THE VARIABLE NAMES ARE GIVEN IN  : "features_info.txt" file.

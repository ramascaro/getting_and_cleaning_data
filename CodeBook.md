## Code Book

This code book will describe the data files and variables used to get the new tidy dataset.

### Overview

The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

### Source Files

* `features.txt`: Names of the 561 features.
* `activity_labels.txt`: Names and IDs for each of the 6 activities.
* `X_train.txt`: 7352 observations of the 561 features, for 21 of the 30 volunteers.
* `subject_train.txt`: A vector of 7352 integers, denoting the ID of the volunteer related to each of the observations in `X_train.txt`.
* `y_train.txt`: A vector of 7352 integers, denoting the ID of the activity related to each of the observations in `X_train.txt`.
* `X_test.txt`: 2947 observations of the 561 features, for 9 of the 30 volunteers.
* `subject_test.txt`: A vector of 2947 integers, denoting the ID of the volunteer related to each of the observations in `X_test.txt`.
* `y_test.txt`: A vector of 2947 integers, denoting the ID of the activity related to each of the observations in `X_test.txt`.

Information about the files is available in `README.txt`.

Information about the features is available in `features_info.txt`.

### Variables
* `subject_train`: contains column names from `subject_train.txt`
* `subject_test`: contains column names from `subject_train.txt`
* `X_train`: contains column names from `X_train.txt`
* `X_test`: contains column names from `X_test.txt`
* `y_train`: contains column names from `y_train.txt`
* `y_test`: contains column names from `y_test.txt`
* `names`: contains column names.
* `featureNames`: contains column names from `features.txt`.
* `train`: data set with 'trains' info combined.
* `test`: data set with 'test' info combined.
* `combined`: data set with 'trains' and 'test' info combined.
* `meanstdcols`: contains "mean()" or "std()" (the other column names were removed).
* `tidy`: final tidy data set that is written to a csv file.

### Output File
* [tidy_dataset.csv](tidy_dataset.csv): Output file containing the tidy data set.

### Author
* `Raúl Mascaró (ramascaro@gmail.com)`:

Merge the data with rbind()
Columns with mean and standard deviation are taken from the whole data set. Correct names are given after extraction from features.txt
Activity data is addressed with values 1:6. Take the activity names and ID from activity_labels.txt and they are substituted in dataset
Columns with different column names are corrected on whole dataset
Generate a new dataset with all average measures for each subject and activity type. Output file is called averages_data.txt

Variables:
x_train, y_train, x_test, y_test, subject_train and subject_test - data from files
x_data, y_data and subject_data - merge previous data sets
features -> correct names for x_data dataset which are applied to the column names stored in mean_and_std_features
activities -> activity names for dataset
all_data merges x_data, y_data and subject_data
averages_data -> relevant averages from plyr package 

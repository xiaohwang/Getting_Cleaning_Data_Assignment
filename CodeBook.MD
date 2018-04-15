I. Purpose



One of the most exciting areas in all of data science right now is wearable computing - see for 
example this article . Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most 
advanced algorithms to attract new users. The data linked to from the course website represent 
data collected from the accelerometers from the Samsung Galaxy S smartphone. 

II. Steps

To achieve project programing and analysis goals, the steps are outlined as follows:

#-------------------------------------------------------------------------------
# 1. Merge the training and the test sets to create one data set

## step 1: download data file from website and save to subdirectory (/Data) in working directory

## step 2: load data into R

## step 3: merge training and test data

#-------------------------------------------------------------------------------
# 2. Extract only the measurements on the mean and std for each measurement

## step 1: load feature name into R

## step 2:  extract mean and std of each measurements

#-------------------------------------------------------------------------------
# 3. Uses descriptive activity names to name the activities in the data set

## step 1: load activity data into R

## step 2: replace 1 to 6 with activity names

#-------------------------------------------------------------------------------
# 4. Appropriately labels the data set with descriptive variable names

#-------------------------------------------------------------------------------
# 5. From the data set in step 4, creates a second, independent tidy data set 
# with the average of each variable for each activity and each subject

III. Variables

The output file "Tidy_data.txt" is saved in current working directory. It includes variables:

"subjects", "activity", and other numeric variables corresping the to mean values.


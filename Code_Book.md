# This file explains the steps in run_analysis.R file.

### The pre requisites to perform the data extraction and provide a tidy data set is done.
### It uses dplyr package. The file is downloaded from the URL using Download.file and Unzipped.

### The data table is assigned to the below variables
  * features
  * activities
  * subject_test
  *  x_test
  *  y_test 
  *  subject_train 
  *  x_train y_train 
    
### Merges the training and the test sets to create one data set
 * Use variables A to bind X data set row wise and B to bind Y data set row wise
 * Subject data is merged row wise
 * Finally column wise merge is done using c bind to merge all the above.
    
### Extracts only the measurements on the mean and standard deviation for each measurement.
 * use Pipe operator to pass the output of merged data set and filter based on mean and std 
    
### Uses descriptive activity names to name the activities in the data
 * Code is replaced with the second column

### Appropriately labels the data set with descriptive variable names
 * use meaningful names to replace the variable names.  Example t and f are replaced with time and frequency.
    
### From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

 *  NewData.txt is the final extracted for each activity and subject


    
    




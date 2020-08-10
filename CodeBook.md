Code Book: 

Prepare for the project by downloading the data set 

Assign variable names 
    features = features.txt
    activities = activity_labels.txt
    subject_test = test/subject_test.txt
    x_test = test/X_test.txt
    y_test = test/y_test.txt
    subject_train = test/subject_train.txt
    x_train = test/X_train.txt
    y_train = test/y_train.txt 


Create a combined data set 
    x = x train data + x test data
    y = y train data + y test data
    subject = subject train data + subject test data

Obtain the mean and std 
    Tidy data using subject, mean and std columns

Name data set variables needed 
    code=activities
    Acc=accelerator
    gyro=gyroscope
    Bodybody=body
    Mag=magnitude

Create a tidy data set with required data
    Export final data

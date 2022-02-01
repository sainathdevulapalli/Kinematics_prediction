# Kinematics_prediction
Predicting Kinematics based on acceleration and gycoscope

### Description:
Smartphones are getting intelligent day by day to assist Human's to aid in their day to day activites. A new feature has emerged popular in the fitness comunity that keeps an account of one's daily footsteps.

More advanced versions include differentiating between detecting the difference between walking & run. This is achieved with the help of Sensors. Several such Sensorory data is recorded with IOS device & labelled as walking or running as 0 or 1.

Currently, the dataset contains a single file which represents 88588 sensor data samples collected from accelerometer and gyroscope from iPhone 5c in 10 seconds interval and ~5.4/second frequency. This data is represented by following columns (each column contains sensor data for one of the sensor's axes):

acceleration_x
acceleration_y
acceleration_z
gyro_x
gyro_y
gyro_z
There is an activity type represented by "activity" column which acts as label and reflects following activities:

"0": walking
"1": running
Apart of that, the dataset contains "wrist" column which represents the wrist where the device was placed to collect a sample on:

"0": left wrist
"1": right wrist
Additionally, the dataset contains "date", "time" and "username" columns which provide information about the exact date, time and user which collected these measurements.

Can you build a strong classifier model to detect these so that it can be incorporated in the IOS device?

### Acknowledgements:
This dataset has been referred from Kaggle.
It complements https://github.com/vmalyi/run-or-walk project which aims to detect whether the person is running or walking based on deep neural network and sensor data collected from iOS device.

This dataset has been accumulated with help of "Data Collection" iOS app specially developed for this purpose: https://github.com/vmalyi/run-or-walk/tree/master/ios_app_data_collection.

### Objective:
Understand the Dataset & cleanup (if required).
Build classification models to predict the type of Kinematic Motion.
Also fine-tune the hyperparameters & compare the evaluation metrics of various classification algorithms.

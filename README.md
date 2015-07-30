# ActivityRecognition
This project analyzes csv files generated by its sister project (https://github.com/JoshuaJB/pebble-accel-log). The project trains a classifier to classify physical activities based on accelerometer data. The example CSV files whose names start with "Original" are the original files generated by the Anroid app. The example CSV files whose anems start with "Edited" were manually edited. Some of the readings at the beggining and end were removed, becasue they were motions related to the starting and stopping of logging. The "runExample" only uses the edited files as training data. The program will try to predict the activities respesented by the acceolormeter data in CSV files beginning with "Test".

To understand how this thing works, I reccommend stepping through the "runExample" file. To run this program, you need MATLAB R2015a and the Statistics and Machine Learning Toolbox.

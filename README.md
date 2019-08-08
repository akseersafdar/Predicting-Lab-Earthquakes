# Overview and Background
Every year many precious lives are lost and billions of dollars worth of infastructure is demaged in earth quakes.
If some how we can timely predict these life threatening earth quakes and save lives of countless humans. This is a project 
which is basically a kaggle challenge where we are required to predict the time remaining in a laboratory earthquake using the 
real-time seismic data.

This challenge was hosted by Los Alamos National Laboratory which enhances national security by ensuring the safety of the U.S. nuclear stockpile, developing technologies to reduce threats from weapons of mass destruction, and solving problems related to energy, environment, infrastructure, health, and global security concerns.


# Data Description

The goal of this competition is to use seismic signals to predict the timing of laboratory earthquakes. The data comes from a well-known experimental set-up used to study earthquake physics. The acoustic_data input signal is used to predict the time remaining before the next laboratory earthquake (time_to_failure).

The training data is a single, continuous segment of experimental data. The test data consists of a folder containing many small segments. The data within each test file is continuous, but the test files do not represent a continuous segment of the experiment; thus, the predictions cannot be assumed to follow the same regular pattern seen in the training file.

For each seg_id in the test folder, you should predict a single time_to_failure corresponding to the time between the last row of the segment and the next laboratory earthquake.

# Code + Models used

I have used various model including SVM/ Catboost / Neural Networks Sequential Model / Xgboost to solve this problem
Final submission to Kaggle has been made xgboost with hyper paramter tuning.

The attached iPython notebook contains the detailed explanation Plus the code.

Also see the below kaggle kernel for the same.

https://www.kaggle.com/akseersafdar/earth-quake-pred-using-catboost-svm-nn-xgboost

# ANN-CDC-Diabetes-Case-Study-IMB
This is an Artificial Neural Network Classification Model to predict whether a patient has Diabetes, Pre-Diabetes or Neither.

## Dataset
The Behavioral Risk Factor Surveillance System (BRFSS) is a health-related telephone survey that is collected annually by the CDC. This original dataset contains responses from 441,455 individuals and has 330 features.  
The dataset used in this Case Study is a dataset of 253,680 survey responses to the CDC's BRFSS2015 with 21 feature variables. The target variable Diabetes_012 has 3 classes:  
* 0 is for no diabetes or only during pregnancy
* 1 is for prediabetes
* 2 is for diabetes.  
There is class imbalance in this dataset.
The dataset was retrieved from:
https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset

## Implementation
I made use of a python notebook (.ipynb) to implement and train this ANN model. The model was made using the Tensorflow 2.0 library in Python.

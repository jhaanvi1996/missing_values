# How to Handle Missing Data with Python

Handling missing data is important as many machine learning algorithms do not support data with missing values.

In this Project, i practised how to handle missing data for machine learning with Python.

specifically, In this project i have -                                        
 - Marked invalid or corrupt values as missing in the dataset.                       
 - Removed rows with missing data from the dataset.                                          
 - Impute missing values with mean values in the dataset.                                      

Note: The examples assume that you have Python 2 or 3 with Pandas, NumPy and Scikit-Learn installed, specifically 
scikit-learn version 0.18 or higher.                
                     
# Overview

This project is divided into 5 parts:                                                     
                 
 - Pima Indians Diabetes Dataset: looking at a dataset that has known missing values.                           
 - Mark Missing Values:  marking missing values in a dataset.                                                           
 - Missing Values Causes Problems: machine learning algorithms can fail when it contains missing values.          
 - Remove Rows With Missing Values: removing rows that contain missing values.                         
 - Impute Missing Values: replacing missing values with sensible values.                          

# About the dataset
The Pima Indians Diabetes Dataset involves predicting the onset of diabetes within 5 years in Pima Indians given medical details.

It is a binary (2-class) classification problem. The number of observations for each class is not balanced. There are 768
observations with 8 input variables and 1 output variable. The variable names are as follows:

0. Number of times pregnant.
1. Plasma glucose concentration a 2 hours in an oral glucose tolerance test.
2. Diastolic blood pressure (mm Hg).
3. Triceps skinfold thickness (mm).
4. 2-Hour serum insulin (mu U/ml).
5. Body mass index (weight in kg/(height in m)^2).
6. Diabetes pedigree function.
7. Age (years).
8. Class variable (0 or 1).

The baseline performance of predicting the most prevalent class is a classification accuracy of approximately 65%. 
Top results achieve a classification accuracy of approximately 77%.

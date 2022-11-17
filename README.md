# LogistictRegression


This repository contains custom logistic regression model using the following dataset.

The data is sourced from study of Abalone in Tasmania. It can be found at the UCI Machine Learning Repository Links to an external site

The dataset contains 4,141 observations and 10 variables.  
SEX = M (male), F (female), I (infant)  
LENGTH = Longest shell length in mm  
DIAM = Diameter perpendicular to length in mm  
HEIGHT = Height perpendicular to length and diameter in mm  
WHOLE = Whole weight of abalone in grams  
SHUCK = Shucked weight of meat in grams  
VISCERA = Viscera weight in grams  
SHELL = Shell weight after drying in grams  
RINGS = Age (+1.5 gives the age in years)  
CLASS = Age classification from 1 to 6 (A1= youngest,..., A6=oldest)  

Problem statement :-

Split the dataset into training and test dataset 80:20  
Custom logistic regression model should be in python class format (Should have init(), predict(), train() methods) and train the model using training dataset  
Predict the age category using test dataset, and provide some insights  
Show the predicted output, and loss function output plots, and explain the outcome  
Calculate the Confusion matrix and explain the model accuracy  
Show top 3 of the PCA component output  
Plot the PCA 1, PCA 2 , and PCA2 components  
Could you use PCA component for logistic regression?

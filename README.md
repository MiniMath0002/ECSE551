# ECSE551 - Assignment 1

## Working process
We worked on the assignment using github and then we adapted our code at the end to work on Colab.

## Mounting
When running the Google drive mount cell, you must allow acces to your google drive account. Before loading the data, make sure to either change the path variable to the CKD and Battery data sets or move them inside a folder called "data" inside the Colab Notebooks folder.

## Statistical Analysis
When running the Statistical Analysis cell, the files will be save in the workspace however there is no need to run this cell as they can be found under CKD_distribution or Battery_distribution folders in this directory

## Model
The model cell is the class that we use to normalize data, cross-validation, fit and predict.

# Partion Data
We partition the data to create a test set for later uses.

# Testing models
We test 5 different models and compare their error value.

# Final testing
We test the data with the model with the lowest error for each data set.
# Drug-Classification

This is a simple machine learning project about choosing the type of drug that is needed for specific age and health conditions. This project used SVM and Decision Tree and compared them to determine which method is better for this dataset

The dataset is from Kaggle: 
https://www.kaggle.com/datasets/ibrahimbahbah/drug200

## Pre modeling
1. Import the necessary libraries
2. Read the CSV file for the dataset to see the data in tables
3. Prepare the data for training by changing the data types for Blood Pressure, Cholesterol, and Sex Variables
4. Change the decimal for NA_to_K to 0
5. Split the data by 7:3 and scale it by using the StandardScaler library

## SVM
1. Import the SVC and GridSearchCV libraries
2. Cross Validation of SVC by using grid search with the train set to find the best parameter for SVM
3. Calculate the accuracy, precision, recall, and F1 score of the result

## Decision Tree
1. Import DecisionTreeClassifier library
2. cross validation of decision tree by using grid search with the train set to find the best parameter for Decision Tree
3. Calculate the accuracy, precision, recall, and F1 score of the result

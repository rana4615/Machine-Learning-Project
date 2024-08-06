# Machine-Learning-Project

Sure, here's a README file for your GitHub profile based on the provided code:

Housing Prices Prediction
This project uses various machine learning techniques to predict housing prices. The dataset used in this project is the Boston Housing dataset.

Table of Contents
Overview
Data
Requirements
Usage
Model Training
Evaluation
Predicting New Data
Overview
The goal of this project is to predict the median value of owner-occupied homes in the Boston area using different regression techniques. We utilize a variety of models, including Linear Regression, Decision Trees, and Random Forests. 


Data
The dataset contains information collected by the U.S Census Service concerning housing in the area of Boston Mass. It contains 13 attributes and 1 target variable MEDV which represents the Median value of owner-occupied homes in $1000s.


Model Training
The training script performs the following steps:

Loads the dataset and displays basic information.
Splits the dataset into training and test sets using train_test_split.
Performs stratified sampling to ensure the test set is representative.
Visualizes correlations between features and the target variable.
Prepares the data using pipelines for imputation and scaling.
Trains multiple regression models:
Linear Regression
Decision Tree Regressor
Random Forest Regressor
Evaluation
The script evaluates the models using cross-validation and calculates the mean squared error (MSE) and root mean squared error (RMSE) for the predictions. The results are printed for comparison.


Acknowledgments
This project was inspired by the "Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow" book by Aurélien Géron.


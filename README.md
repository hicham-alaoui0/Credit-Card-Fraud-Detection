# Credit-Card-Fraud-Detection
Credit Card Fraud Detection with Machine Learning
# Introduction

This repository contains Python code for analyzing and predicting fraudulent transactions in credit card data using machine learning techniques. The code utilizes various models such as Logistic Regression, Decision Tree, Random Forest, and K-Nearest Neighbors to classify transactions as either fraudulent or legitimate.

# Data Description

The dataset used in this analysis is the creditcard.csv file, which contains information about credit card transactions, including:

Time: Transaction timestamp
V1: Feature 1
V2: Feature 2
...: Features 28 to 33
Amount: Transaction amount
Class: Transaction class (0 for legitimate, 1 for fraudulent)
Data Analysis and Exploration

# Descriptive Statistics
The code calculates descriptive statistics (mean, median, standard deviation, etc.) for each numerical feature to understand the distribution of the data.

# Normality Check
It checks whether the numerical features follow a normal distribution using Shapiro-Wilk's test.

# Bivariate Analysis
The code explores the relationship between the Amount feature and the Class (fraudulent or legitimate) using a scatter plot.

# T-test
It performs a t-test to compare the mean Amount between fraudulent and legitimate transactions.

# Model Training and Evaluation

# Data Preprocessing
The code handles missing values and categorical features.

# Over-sampling
Since the dataset is imbalanced (more legitimate transactions than fraudulent ones), it oversamples the minority class (fraudulent transactions) using RandomOverSampler to address the class imbalance issue.

# Model Training
The code trains four machine learning models: Logistic Regression, Decision Tree, Random Forest, and K-Nearest Neighbors.

# Model Evaluation
It evaluates the performance of each model using metrics such as classification report, confusion matrix, accuracy score, and ROC curve.

# Results and Discussion

Model Performance
The evaluation results indicate that Random Forest Classifier outperforms the other models in terms of overall accuracy and fraud detection capabilities.

# Over-sampling Impact
Over-sampling the minority class (fraudulent transactions) improves the performance of all models, especially for metrics related to fraud detection (precision and recall).

# Conclusion

This analysis demonstrates the application of machine learning techniques to identify fraudulent transactions in credit card data. The Random Forest Classifier emerged as the most effective model for this task, highlighting the importance of careful data preparation and model selection for fraud detection systems.

# Further Considerations

Feature Engineering
Exploring and creating new features from the existing data could potentially improve model performance.

Hyperparameter Tuning
Optimizing the hyperparameters of each model could further enhance their predictive capabilities.

Model Ensembles
Combining the predictions of multiple models using ensemble methods might lead to even better results.

# Contributing

Feel free to fork this repository, experiment with different models and techniques, and share your improvements!

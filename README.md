# Machine learning assignment

This repository contains a project focused on predicting the likelihood of diabetes onset using logistic regression. The project involves careful feature selection to identify the most significant predictors and employs cross-validation to ensure the model's reliability.

# Dataset
Source: https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database
Description: The dataset includes health-related attributes such as glucose levels, blood pressure, BMI, age, etc. Feature selection was applied to identify the most relevant predictors, and the data was split into training and testing sets for cross-validation.

# EDA Process
Data Cleaning:

Addressed missing values and outliers.
Standardized and normalized numerical features.
Feature Selection:

Applied techniques such as Recursive Feature Elimination (RFE) to select the most impactful features.
Data Visualization:

Used various plots to explore the relationships between features and the target variable (diabetes outcome).

# Modeling
Logistic Regression:
Built a logistic regression model to predict diabetes onset.
Performed cross-validation to assess the model’s performance and generalization ability.
Evaluated the model using accuracy, precision, recall, and ROC-AUC score.

Diabetes Prediction Project
Overview
This project predicts diabetes using the Diab_Pred.ipynb notebook, which preprocesses data, engineers features, and compares machine learning models (Naive Bayes, Logistic Regression, QDA, KNN, SVM, XGBoost) on a dataset of health-related features.
Dataset
The diabetes_dataset.csv contains 10,000 entries with 21 features (e.g., Age, BMI, HbA1c, Smoking Status). The Outcome variable indicates diabetes based on HbA1c (≥6.5) or Fasting Blood Glucose (≥126).
Preprocessing

Load data with pandas.
Create Outcome and encode categorical variables (e.g., Sex, Smoking_Status).
Bin Age into groups (Young, Middle-Aged, Older, Senior).
Drop Unnamed: 0, Ethnicity; fill missing Alcohol_Consumption with mode.
Visualize model accuracies with a bar plot.

Models

Evaluated models:
Naive Bayes
Logistic Regression
QDA
KNN
SVM
XGBoost


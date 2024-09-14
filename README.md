# Insurance-Claims-Prediction-Using-Machine-Learning

This project involves building a machine learning pipeline to predict insurance claims using logistic regression and random forest classifiers. The dataset includes features such as age, BMI, smoking status, and region. The analysis involves data preprocessing steps like one-hot encoding for categorical variables and standardization for numerical features. The model's performance is evaluated using accuracy metrics, and feature importances are analyzed to understand the contribution of each feature to the prediction.

**Detailed Explanation for README File**

This Jupyter notebook demonstrates a comprehensive approach to predicting insurance claims using machine learning techniques. The analysis includes the following steps:

**Data Loading and Preparation:**

The dataset is loaded and the target variable, insurance_claim, is converted to a binary format.
Features are split into categorical and numerical types for appropriate preprocessing.

**Data Preprocessing:**

Categorical features (sex, smoker, region) are transformed using one-hot encoding.
Numerical features (age, bmi, steps, children) are standardized using StandardScaler.

**Model Building:**

A logistic regression model is constructed using a pipeline that integrates preprocessing steps.
A random forest classifier is also built to compare performance.

**Model Evaluation:**

The models are trained and tested on a split dataset, and their accuracy is calculated.
Feature importances from the random forest model are printed to understand the impact of each feature.

**Results:**
The logistic regression model achieved an accuracy of 87.78%.
The random forest model's accuracy and feature importances are also evaluated.
This project provides a clear example of how to implement and evaluate machine learning models for binary classification tasks in Python using libraries such as pandas, scikit-learn, and numpy.

Bank Marketing Campaign Analysis and Model Comparison

Project Overview

This project focuses on predicting whether a client will subscribe to a term deposit based on demographic information, past interactions, 
and economic indicators. The dataset, obtained from a Portuguese banking institution, includes details from multiple marketing campaigns. 

The primary goal is to develop and compare the performance of several machine learning models, including Logistic Regression, 
K-Nearest Neighbors (KNN), Decision Tree, and Support Vector Machine (SVM), to identify the best approach for this classification problem.

The dataset used in this project comes from the UCI Machine Learning Repository. It consists of 41,188 records with 20 input variables 
and one output variable:

Input Variables: Age, job, marital status, education, default, housing, loan, contact, month, day_of_week, duration, campaign, pdays, 
previous, poutcome, emp.var.rate, cons.price.idx, cons.conf.idx, euribor3m, nr.employed

Output Variable: y - Binary variable indicating whether the client subscribed to a term deposit ('yes' or 'no').

Project Steps

1. Data Understanding
Objective: Gain a better understanding of the dataset, its features, and the target variable.
Actions:
Explore the dataset to identify missing values and data types.
Review the distribution of categorical and continuous features.
Understand the business objective: Predicting term deposit subscription.
2. Data Preparation
Objective: Prepare the data for modeling by encoding categorical variables and scaling numerical features.
Actions:
One-Hot Encoding of categorical variables.
Standardization of continuous variables.
Train/Test Split: Split the dataset into training and testing sets to evaluate model performance.
3. Baseline Model
Objective: Establish a baseline model for comparison.
Actions:
Calculate the baseline accuracy by predicting the majority class.
Implement a simple Logistic Regression model to set a benchmark for model performance.
4. Model Building and Comparison
Objective: Build and compare different machine learning models.
Actions:
Train models using Logistic Regression, K-Nearest Neighbors (KNN), Decision Tree, and Support Vector Machine (SVM).
Evaluate models based on accuracy and other relevant metrics.
Compare the fit time of each model.
5. Hyperparameter Tuning
Objective: Optimize the models by tuning their hyperparameters.
Actions:
Define hyperparameter grids for KNN, Decision Tree, and SVM.
Use GridSearchCV and RandomizedSearchCV to find the best hyperparameters.
Evaluate the best models on the test set and compare their performance.
6. Results and Interpretation
Objective: Summarize and interpret the results of the hyperparameter tuning and model evaluation.
Actions:
Report the best parameters and accuracy for each model.
Interpret the test accuracy and cross-validation results.
Identify the best-performing model based on test accuracy and model interpretability.
Conclusion

The Support Vector Machine (SVM) model with a linear kernel and low regularization (C=0.1) was identified as the best-performing model, achieving a test accuracy of 88.65%. The model was found to generalize well, with a close match between cross-validation and test accuracy. The Decision Tree model also performed well, offering a balance between accuracy and interpretability.


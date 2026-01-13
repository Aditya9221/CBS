  Company Bankruptcy Prediction System

Project Overview :

Financial instability is a major risk for businesses, investors, and financial institutions.
This project focuses on building a machine learning system to predict whether a company is likely to go bankrupt based on its financial indicators.

The goal is to identify early warning signs of bankruptcy using historical company data and classification models.

Problem Statement :

Predict whether a company will go bankrupt (1) or remain financially healthy (0) using financial ratios and performance metrics.

This is a binary classification problem.

Solution Approach :

The project follows an end-to-end data science workflow:

Data understanding and exploration (EDA),
Data cleaning and preprocessing,
Feature scaling and selection,
Model training and evaluation,
Performance comparison and final model selection.

Dataset Description

The dataset contains financial ratios and indicators of companies.

Technologies Used :

Python
Pandas & NumPy – data manipulation
Matplotlib & Seaborn – visualization
Scikit-learn – preprocessing, modeling, evaluation

Target variable :
1 → Bankrupt
0 → Not Bankrupt
The dataset is imbalanced, which reflects real-world bankruptcy scenarios.

Machine Learning Models :
Logistic Regression
Random Forest

Evaluation metrics:
Accuracy,
Precision,
Recall,
F1-Score,
ROC-AUC.

Key Challenges :

Handling imbalanced data,
Selecting important features from a large number of variables,
Preventing overfitting,
Choosing the right scaling technique.

Results :

The final model demonstrates:
Strong recall for bankrupt companies (important for risk detection),
Balanced overall performance,
Practical usability for financial risk assessment.

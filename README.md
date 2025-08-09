# Customer_churn_prediction

This project implements a machine learning pipeline to predict customer churn using Logistic Regression, Random Forest, and SVM classifiers. It includes feature engineering, handling class imbalance with SMOTE, dimensionality reduction with PCA, hyperparameter tuning, and model evaluation.

---

## Overview

Customer churn prediction helps businesses identify customers likely to leave, enabling targeted retention strategies to reduce churn and increase revenue.

---

## Features

- Data preprocessing: scaling, encoding categorical variables
- Handling imbalanced data with SMOTE
- Feature engineering: polynomial features and PCA for dimensionality reduction
- Model training and comparison: Logistic Regression, Random Forest, SVM
- Hyperparameter tuning using RandomizedSearchCV
- Evaluation with metrics: precision, recall, F1-score, ROC-AUC, confusion matrix
- Feature importance analysis for Random Forest

---

## Business Applications and Recommendations

How to use the model for retention:
Identify At-Risk Customers:
Score all current customers with the model to classify those likely to churn.

Targeted Retention Campaigns:
Direct personalized offers, communications, or loyalty programs to high-risk customers to increase engagement and reduce churn.

Resource Optimization:
Allocate marketing and customer success resources efficiently by focusing on customers where retention efforts will be most impactful.

Continuous Monitoring:
Periodically re-score customers as new data becomes available, adapting retention strategies dynamically.

---



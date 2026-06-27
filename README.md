# Employee Attrition Prediction

## Overview
This project predicts employee attrition using Machine Learning. It compares multiple classification models and identifies employees 
at risk of leaving the organization. Based on the predicted probability, employees are categorized into different risk zones 
to help HR take appropriate retention actions.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Imbalanced-learn (SMOTE)

## Machine Learning Models
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

## Project Workflow
- Data Preprocessing
- One-Hot Encoding (`get_dummies`)
- Stratified Train-Test Split (80:20)
- Handle Class Imbalance using SMOTE
- 5-Fold Cross Validation
- Model Evaluation (Accuracy, Precision, Recall, F1-Score, ROC-AUC, Confusion Matrix)
- Employee Risk Zone Prediction

## Employee Risk Zones
- 🟢 Safe Zone (<20%)
- 🟡 Low-Risk Zone (20%–60%)
- 🟠 Medium-Risk Zone (60%–90%)
- 🔴 High-Risk Zone (>90%)

## Results
Among the three models, **Random Forest Classifier** achieved the best overall performance based on Cross Validation, 
Classification Report, ROC-AUC Score, and Confusion Matrix.

## Conclusion
This project demonstrates an end-to-end machine learning pipeline for predicting employee attrition and 
provides actionable insights to help organizations improve employee retention.

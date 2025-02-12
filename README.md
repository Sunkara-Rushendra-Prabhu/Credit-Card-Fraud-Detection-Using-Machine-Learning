# Credit-Card-Fraud-Detection-Using-Machine-Learning
Overview
With the rise of e-commerce and online transactions, credit card fraud has become a major concern. This project implements a fraud detection system using machine learning techniques, specifically Logistic Regression, Decision Tree, and Random Forest Classifier. The project addresses class imbalance using SMOTE and undersampling, ensuring accurate fraud detection while minimizing false positives.

Features
Preprocessing of transaction data, including duplicate removal and feature scaling.
Handling class imbalance with undersampling and oversampling (SMOTE).
Implementation of Logistic Regression, Decision Tree, and Random Forest Classifier.
Performance evaluation using accuracy, precision, recall, and F1-score.
Achieved 99.99% accuracy with Random Forest Classifier.
Technologies Used
Python
NumPy, Pandas (for data handling and preprocessing)
Scikit-learn (for model training and evaluation)
Matplotlib, Seaborn (for visualization)
SMOTE (to handle class imbalance)
Joblib (to save and deploy models)
Dataset
The dataset used in this project was obtained from Kaggle and contains 284,807 credit card transactions, including 473 fraudulent cases. It consists of 31 features, representing anonymized transaction details.

Data Preprocessing
Duplicate Removal: Removed 9,144 duplicate rows to maintain data integrity.
Feature Scaling: Standardized the Amount feature using StandardScaler.
Handling Class Imbalance: Applied undersampling and SMOTE-based oversampling to ensure fair model training.
Model Selection
We evaluated three machine learning models:

Logistic Regression – Used as a baseline for fraud detection.
Decision Tree Classifier – Captures non-linear relationships in transaction patterns.
Random Forest Classifier – An ensemble learning method, delivering the highest accuracy.

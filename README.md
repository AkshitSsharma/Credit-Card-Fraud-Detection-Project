Project Overview

This project implements a machine learning system to detect fraudulent credit card transactions. It helps financial institutions identify suspicious activities and prevent losses.

Dataset

Source: Public credit card transaction dataset (e.g., Kaggle)

Features: Transaction amount, time, and anonymized features (V1–V28)

Target: Class (0 = legitimate, 1 = fraud)

Methodology

Data Preprocessing

Handle missing values

Feature scaling

Train-test split

Exploratory Data Analysis (EDA)

Analyze class imbalance

Visualize feature distributions

Modeling

Logistic Regression

Random Forest

XGBoost

Evaluation Metrics

Accuracy

ROC-AUC

Precision, Recall, F1-Score

Key Results

Achieved high accuracy and ROC-AUC score

XGBoost provided the best performance for fraud detection

Tools & Technologies

Python, Pandas, NumPy, Matplotlib, Seaborn

Scikit-learn, XGBoost

Conclusion

The model can reliably detect fraudulent transactions, helping reduce financial risks. Future improvements could include real-time deployment and advanced feature engineering.

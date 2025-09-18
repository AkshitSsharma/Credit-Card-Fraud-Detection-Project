Overview

ML-based system to detect fraudulent credit card transactions, helping prevent financial losses.

Dataset

Features: Transaction amount, time, anonymized features (V1–V28)

Target: Class (0 = legitimate, 1 = fraud)

Approach

Preprocessing: Handle missing values, feature scaling, train-test split

EDA: Class imbalance analysis, feature visualization

Modeling: Logistic Regression, Random Forest, XGBoost

Evaluation: Accuracy, ROC-AUC, Precision, Recall, F1-Score

Results

XGBoost gave the best performance

High accuracy & ROC-AUC for fraud detection

Tools

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost

Conclusion

Reliable fraud detection model; future work: real-time deployment & feature engineering

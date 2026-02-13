# Indian-Digital-Payment-Fraud-Detection-System
A machine learning-based fraud detection system built using synthetic but behaviorally realistic Indian digital payment transaction data.  This project simulates real-world fintech fraud detection by identifying suspicious digital payment transactions using classification models and performance evaluation metrics.

Project Overview:-
Digital payments are increasing rapidly in India (UPI, cards, wallets). With growth comes fraud risk.
This project builds a complete end-to-end fraud detection pipeline including:
Exploratory Data Analysis (EDA)
Feature engineering & preprocessing
Logistic Regression baseline model
Random Forest classifier
Threshold tuning
ROC-AUC evaluation
Confusion matrix analysis
Model deployment using joblib

Dataset:-
8000 synthetic digital transactions
Realistic rule-based fraud generation
6–12% fraud rate
Same feature structure as production systems

Features:-
transaction_amount, transaction_frequency_24h,
avg_transaction_amount_7d, is_foreign_transaction,
payment_status, payment_mode, device_type,
merchant_category, day_type, demography_region
Target: fraud

Model Performance (Random Forest):-
Precision (Fraud): 0.91
Recall (Fraud): 0.87
F1-Score: 0.89
ROC-AUC: 0.948
Low false positives and strong fraud detection capability.

Tech Stack:-
Python
Pandas / NumPy
Scikit-learn
Matplotlib / Seaborn
Joblib

# Credit Card Fraud Detection 🛡️

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. 
The dataset is highly imbalanced, with a very small percentage of transactions marked as fraudulent.

## Problem Statement
Given a dataset of transactions, classify whether a transaction is fraudulent or not.

## Dataset
- Source: [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- 284,807 transactions with 492 fraud cases (0.17%)

## Features
- Anonymized PCA-transformed numerical features (`V1` to `V28`)
- `Amount`: Transaction amount
- `Time`: Seconds elapsed between transaction and first transaction in the dataset
- `Class`: 1 for fraud, 0 for normal

## Model
- Logistic Regression
- Random Forest
- Isolation Forest
- SMOTE (for handling class imbalance)


# Credit Card Fraud Detection using Machine Learning

## Overview
This project builds a machine learning model to detect fraudulent credit card transactions using transaction data.

The dataset is highly imbalanced, so class weighting techniques were used during model training.

## Dataset
Credit Card Fraud Detection Dataset (Kaggle)

Transactions: 284,807  
Fraud Cases: 492

## Techniques Used
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Handling class imbalance
- Logistic Regression
- Random Forest

## Evaluation Metrics
- Precision
- Recall
- F1 Score
- ROC-AUC

## Results

### Logistic Regression
- Recall: 0.92
- ROC-AUC: 0.94

### Random Forest
- Precision: 0.96
- Recall: 0.74
- ROC-AUC: 0.87

Random Forest achieved higher precision in detecting fraudulent transactions.

## Technologies
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

Dataset is not included due to GitHub file size limits.

Downloaded dataset from:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## Results

Random Forest performed best in detecting fraudulent transactions.

Accuracy: ~99%  
ROC-AUC: ~0.87

Confusion Matrix:
(image)
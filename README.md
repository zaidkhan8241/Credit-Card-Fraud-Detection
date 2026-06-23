# Credit Card Fraud Detection Using Machine Learning

## Overview

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The dataset is highly imbalanced, containing a very small percentage of fraudulent transactions compared to normal transactions. Various preprocessing techniques and classification models are used to build an effective fraud detection system.

## Features

* Exploratory Data Analysis (EDA)
* Data preprocessing and feature scaling
* Train-test split 
* Model training using XGBoost Classifier
* Performance evaluation using multiple metrics
* ROC-AUC analysis and classification report
* Fraud prediction on unseen transactions

## Dataset

The project uses the Credit Card Fraud Detection dataset, which contains anonymized transaction features (`V1-V28`), transaction time, amount, and the target variable `Class`, where:

* `0` → Normal transaction
* `1` → Fraudulent transaction

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost

## Machine Learning Workflow

1. Data loading and exploration
2. Data preprocessing
3. Train-test split
4. Model training using XGBoost
5. Cross-validation
6. Prediction and evaluation
7. Performance analysis

## Evaluation Metrics

Since the dataset is highly imbalanced, model performance is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC Score
* Confusion Matrix

## Results

The trained model effectively distinguishes between legitimate and fraudulent transactions while maintaining high recall and ROC-AUC scores, making it suitable for fraud detection applications.

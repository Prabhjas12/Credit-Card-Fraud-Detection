# Real-Time Credit Card Fraud Detection

This project builds a machine learning pipeline for detecting fraudulent credit card transactions using the Kaggle Credit Card Fraud Detection dataset. The project compares baseline models, supervised ensemble models, an autoencoder anomaly detector, and a hybrid fraud scoring model.

The main task is binary classification:

- `0` = legitimate transaction
- `1` = fraudulent transaction

Because the dataset is highly imbalanced, the project focuses on fraud-specific metrics such as precision, recall, F1-score, ROC-AUC, and PR-AUC instead of accuracy alone.

---

## Project Overview

Credit card fraud detection is a challenging data mining problem because fraudulent transactions are very rare compared to legitimate transactions. A model can achieve high accuracy by predicting every transaction as normal, but that would fail to detect fraud. This project handles the imbalance by using appropriate evaluation metrics, stratified data splitting, class weighting, threshold tuning, and anomaly detection.

The project includes:

- Data validation
- Exploratory data analysis
- Feature engineering
- Preprocessing and train/validation/test splitting
- Baseline model comparison
- Gradient Boosting model
- Autoencoder anomaly detection model
- Hybrid Gradient Boosting + Autoencoder score
- Final model evaluation

---

## Dataset

Dataset: **Credit Card Fraud Detection**  
Source: Kaggle  
Link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

The raw dataset is not included in this GitHub repository because the file is large. To reproduce the project, download the dataset from Kaggle and place the file here:

```text
data/raw/creditcard.csv

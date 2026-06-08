# Real-Time Credit Card Fraud Detection

This project builds a credit card fraud detection pipeline using the Kaggle Credit Card Fraud Detection dataset. The task is binary classification: predict whether a transaction is fraudulent or legitimate.

## Dataset

Dataset: Kaggle Credit Card Fraud Detection  
Link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

The raw dataset should be placed here:

data/raw/creditcard.csv

## Project Structure

- notebooks/1_data_check.ipynb: Initial dataset checks
- notebooks/2_eda.ipynb: Exploratory data analysis
- notebooks/3_preprocessing_and_labeling.ipynb: Cleaning, feature engineering, train/validation/test split
- notebooks/4_baseline_models.ipynb: Baseline models
- notebooks/5_mainmodel_results.ipynb: Gradient Boosting, Autoencoder, Hybrid Model, final results
- reports/: Final report PDF
- figures/: Report figures

## Models

The project compares:

- Dummy Classifier
- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- Autoencoder anomaly detector
- Hybrid Gradient Boosting + Autoencoder model

## Evaluation Metrics

Because the dataset is highly imbalanced, the project uses:

- Precision
- Recall
- F1-score
- ROC-AUC
- PR-AUC

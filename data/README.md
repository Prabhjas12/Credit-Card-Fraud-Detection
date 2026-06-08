# Data Folder Instructions

This folder is used to store the dataset files for the Credit Card Fraud Detection project.

The original dataset is **not included in this GitHub repository** because the raw CSV file is large. To run the notebooks, you must download the dataset manually and place it in the correct folder.

## Dataset

Dataset name: **Credit Card Fraud Detection**

Source: Kaggle  
Dataset link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

The dataset contains credit card transactions made by European cardholders in September 2013. The goal is to predict whether each transaction is fraudulent or legitimate.

## Folder Structure

The `data/` folder should look like this:

```text
data/
│
├── README.md
│
├── raw/
│   └── creditcard.csv
│
└── processed/
    ├── X_train_scaled.csv
    ├── X_val_scaled.csv
    ├── X_test_scaled.csv
    ├── X_train_unscaled.csv
    ├── X_val_unscaled.csv
    ├── X_test_unscaled.csv
    ├── y_train.csv
    ├── y_val.csv
    └── y_test.csv

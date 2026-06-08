# Notebooks Folder

This folder contains the main project notebooks.

Run the notebooks in the following order:
1_data_check.ipynb
Initial dataset inspection, including shape, columns, missing values, duplicates, and class distribution.
2_eda.ipynb
Exploratory data analysis, including class imbalance, transaction amount patterns, time patterns, and PCA feature comparisons.
3_preprocessing_and_labeling.ipynb
Preprocessing notebook that removes duplicates, engineers features, creates train/validation/test splits, scales features, and saves processed datasets.
4_baseline_models.ipynb
Trains and evaluates baseline models, including Dummy Classifier, Logistic Regression, Decision Tree, and Random Forest.
5_mainmodel_results.ipynb
Trains and evaluates main models, including Gradient Boosting, Autoencoder anomaly detection, and a Hybrid Model.
Important
Run all notebooks from top to bottom after placing the raw dataset at:
data/raw/creditcard.csv

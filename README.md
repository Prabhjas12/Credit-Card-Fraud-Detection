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
```

The file must be named exactly:

```text
creditcard.csv
```

---

## How to Run This Project

### 1. Clone the Repository

```bash
git clone https://github.com/prabhjas14/credit-card-fraud-detection.git
cd credit-card-fraud-detection
```

### 2. Install Requirements

```bash
pip install -r requirements.txt
```

### 3. Download the Dataset

Download the dataset from Kaggle:

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

After downloading and unzipping it, place the file here:

```text
data/raw/creditcard.csv
```

The file must be named exactly:

```text
creditcard.csv
```

### 4. Run the Notebooks

Open Jupyter Notebook:

```bash
jupyter notebook
```

Then run the notebooks in this order:

```text
notebooks/1_data_check.ipynb
notebooks/2_eda.ipynb
notebooks/3_preprocessing_and_labeling.ipynb
notebooks/4_baseline_models.ipynb
notebooks/5_mainmodel_results.ipynb
```

The third notebook creates the processed data files inside:

```text
data/processed/
```

The fourth and fifth notebooks use those processed files to train and evaluate the models.

---

## Final Report

The final project report is located in:

```text
reports/DSC148_Final_Report_Prabhjas_Singh.pdf
```

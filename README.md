# Fraud Detection IN ONLINE TRANSACTION
## Overview

The repository presents my MSc thesis project which implements a system for detecting online financial transaction fraud. The project aims to create an intelligent system that detects fraudulent activities through its combination of machine learning deep learning and anomaly detection techniques. The system addresses real-world problems by dealing with class imbalance and evolving fraud patterns and producing accurate and comprehensible prediction results.

## Contents

The main notebook of the repository presents "Thesis (Code).ipynb" which implements the entire fraud detection system. The notebook presents data preprocessing processes and feature engineering methods and model development procedures and evaluation techniques and result visualization steps.

## Dataset

The project uses a financial transaction dataset containing both legitimate and fraudulent transaction records. The dataset shows high imbalance because real-world financial systems experience infrequent fraudulent transaction occurrences. The dataset includes features which describe transaction type and transaction amount and account balance details. The data preprocessing stage involves data cleaning and categorical variable encoding and numerical feature normalization and SMOTE-based class imbalance management. The repository does not contain the dataset because of size and privacy restrictions so users must acquire it from an appropriate source to execute the notebook.The dataset that is used is 
https://www.kaggle.com/datasets/rupakroy/online-payments-fraud-detection-dataset

## Methodology

The system contains different methods which work to detect fraudulent activities. A Random Forest model serves as the baseline machine learning method because it shows excellent performance with structured data. A Deep Neural Network is implemented to capture complex patterns and relationships within the dataset. The autoencoder model detects anomalies in transaction data through its ability to identify atypical transaction patterns. The detection system uses a hybrid model which improves detection accuracy through the combination of different model outputs.

#  Fraud Detection – Machine Learning End-to-End

##  Overview
This project implements an end-to-end Machine Learning system to detect fraudulent credit card transactions.  
It focuses on handling highly imbalanced data, optimizing business-relevant metrics, and deploying the model as a production-ready API.

##  Business Problem
Fraudulent transactions represent a small percentage of total operations but generate significant financial losses.  
The goal is to **maximize fraud detection (recall)** while maintaining a reasonable false positive rate.

## 📊 Dataset
- Source: Credit Card Fraud Detection Dataset (European cardholders)
- Transactions: 284,807
- Fraud cases: 492 (~0.17%)
- Features: 28 anonymized PCA components + Amount

##  Approach
1. Exploratory Data Analysis (EDA)
2. Feature engineering and scaling
3. Model training with imbalance handling
4. Model evaluation using proper metrics
5. Experiment tracking with MLflow
6. Model deployment via FastAPI and Docker

## 📈 Models
- Logistic Regression (baseline)
- Random Forest
- Gradient Boosting (XGBoost / LightGBM)

##  Metrics
- Recall (fraud detection)
- Precision
- F1-score
- ROC AUC
- Precision-Recall AUC

Accuracy is not used as the primary metric due to class imbalance.

## Project Structure



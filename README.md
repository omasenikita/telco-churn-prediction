# Telco Customer Churn Prediction
Predicting telecom customer churn using machine learning to identify customers likely to leave.

## 📌 Project Overview
This project analyzes telecom customer data to predict which customers are at risk of leaving (churning). By identifying potential churners, companies can take proactive measures to retain customers and improve satisfaction.

## 🗂 Dataset
- Contains customer details such as demographics, account information, usage patterns, and service details.
- Common features include: `gender`, `SeniorCitizen`, `Partner`, `Dependents`, `tenure`, `PhoneService`, `MultipleLines`, `InternetService`, `Contract`, `PaymentMethod`, `MonthlyCharges`, `TotalCharges`, and `Churn`.
- Source: [Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## 🛠 Features
- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Encoding and Scaling
- Machine Learning Models:
  - Random Forest Classifier (current implementation)
  - Logistic Regression (optional for comparison)
  - XGBoost Classifier (optional for improvement)
- Model Evaluation Metrics:
  - Accuracy
  - Precision
  - Recall (Sensitivity)
  - F1-score
  - ROC-AUC
  - Confusion Matrix

## 💻 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/omasenikita/telco-customer-churn-prediction.git

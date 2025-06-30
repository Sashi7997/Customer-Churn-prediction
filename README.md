# Customer Churn Prediction

This project uses machine learning to predict customer churn based on telecom service usage and billing data. The model helps identify high-risk customers, enabling targeted retention strategies.

## 📌 Overview

- **Goal**: Predict if a customer is likely to churn (leave the service).
- **Tech Stack**: Python, Pandas, Scikit-learn, XGBoost, SHAP, SMOTE, Matplotlib
- **Model**: XGBoost Classifier
- **Performance**:
  - Accuracy: ~81%
  - ROC-AUC: ~87%

## 📁 Dataset

The dataset includes features such as:
- Demographics (e.g., gender, senior citizen)
- Services (e.g., phone service, contract type)
- Billing (e.g., monthly charges, payment method)
- Target: `Churn` (Yes/No)

> Sample data file: `data/churn_data.csv`

## ⚙️ Features

- Data preprocessing and encoding
- Class imbalance handled using **SMOTE**
- Model training with **XGBoost**
- Evaluation using **Accuracy** and **ROC-AUC**
- Model interpretation using **SHAP** values

## 🧠 Key Insights

- Contract type and monthly charges are top indicators of churn.
- Shorter tenure and electronic payments also correlate with higher churn risk.

## 📊 Visualizations

SHAP summary plot for feature importance:
![SHAP Plot](shap_summary_plot.png)

## 🗂 Project Structure


# Customer-Churn-Analysis
# 📉 Customer Churn Prediction

This project predicts customer churn using machine learning models and exploratory data analysis (EDA) in Python. SQL is used for basic data querying and validation. The goal is to identify potential customer churn and understand the key drivers behind it.

---

## 📦 Project Overview

- **Domain**: Telecom / Customer Retention  
- **Problem**: Predict whether a customer will churn based on their demographics, contract details, and service usage  
- **Dataset**: Telco Customer Churn Dataset (~7,000 rows)  
- **Goal**: Build a classification model and extract actionable business insights

---

## 🛠 Tools & Technologies Used

- **Python**: pandas, numpy, matplotlib, seaborn, scikit-learn  
- **SQL**: Basic queries (joins, filters, aggregations)  
- **Jupyter Notebook**: Analysis and model development

---

## 📊 Project Workflow

### 1. Data Preprocessing
- Loaded dataset and checked for missing/null values  
- Handled missing data appropriately  
- Converted categorical variables using one-hot encoding  
- Scaled numerical features

### 2. Exploratory Data Analysis (EDA)
- Analyzed churn rate based on:
  - Gender
  - Contract type
  - Tenure
  - Monthly charges
- Used visualizations (bar plots, histograms, heatmaps) to explore trends

### 3. Model Building
- Implemented and compared:
  - Logistic Regression  
  - Random Forest  
  - XGBoost  
- Evaluated models using:
  - Accuracy
  - Precision & Recall
  - Confusion Matrix
- Best model achieved ~78% accuracy

---

## 📈 Key Insights
- Month-to-month customers had the highest churn risk  
- Higher monthly charges and shorter tenure increased churn likelihood  
- Electronic payment methods showed more churn tendency

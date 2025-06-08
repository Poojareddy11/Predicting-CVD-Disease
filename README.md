# 🫀 Cardiovascular Disease Risk Prediction

A data mining project aimed at predicting cardiovascular disease (CVD) risk using individual lifestyle attributes and machine learning models.

---

## 📊 Project Overview

This project focuses on forecasting the risk of cardiovascular diseases using a dataset obtained from Kaggle, containing **308,855 rows** and **19 features**. The primary goal is to explore various machine learning algorithms and identify significant personal attributes contributing to CVD risk.

---

## 📁 Dataset

**Source:** Kaggle – CVD Risk Prediction  
**Features include:**
- General Health
- Checkup Frequency
- Exercise Habits
- Health History (e.g., Diabetes, Cancer, Arthritis)
- Demographics (e.g., Sex, Age, Height, Weight)
- Lifestyle (e.g., Smoking, Alcohol, Diet)

---

## 🧠 ML Techniques Used

- Logistic Regression (with Hyperparameter Tuning)
- Decision Trees
- Random Forest
- Support Vector Machines (SVM)

---

## ⚙️ Process Workflow

### 🔹 Data Preprocessing
- Cleaning missing values and outliers
- Feature scaling
- Merging multiple datasets

### 🔹 Feature Selection
- Correlation analysis
- Feature importance using tree-based models
- Statistical tests (T-tests, ANOVA)

### 🔹 Model Training & Evaluation
- N-Fold Cross-Validation
- Metrics: Accuracy, Precision, Recall, F1-score, AUC-ROC
- Hyperparameter Tuning via Grid Search / Random Search

---

## 🧪 Evaluation

Models were evaluated based on:
- General performance across validation folds
- Interpretability for healthcare insights
- Statistical robustness of key attributes

---

## 🎯 Key Outcomes

- Identified top predictive attributes for CVD risk
- Logistic Regression with tuned parameters provided a strong baseline
- Random Forest and SVM delivered high accuracy and robustness
- Actionable insights generated for healthcare practitioners

---

## 📂 Files

| File Name                 | Description                               |
|--------------------------|-------------------------------------------|
| CVD_cleaned.csv        | Cleaned and processed dataset             |
| merged_data.csv        | Combined dataset after preprocessing      |
| vTargetMailCustomer.csv, VTargetBuyers.csv | Raw data sources          |
| Project Proposal.docx  | Formal project documentation              |
| README.md              | This file                                 |

---

## 📌 Future Work

- Integrating deep learning models
- Building a web-based CVD risk calculator
- Extending the pipeline to support real-time wearable health data

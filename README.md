# 🌟 COVID-19 Risk Prediction and Analysis

This project aims to predict whether a COVID-19 patient is at high risk based on their medical history and current symptoms. Using machine learning techniques, the analysis also identifies the most significant factors influencing high-risk outcomes.

---

## 🛠 Project Overview

- **Objective**: Predict high-risk outcomes for COVID-19 patients and analyze contributing factors.
- **Dataset**: COVID-19 data with over 1,048,575 rows and 21 features (source: [Kaggle](https://www.kaggle.com/datasets/meirnizri/covid19-dataset/data)).
- **Approach**:
  1. Preprocessed the dataset by handling missing values and balancing the target variable.
  2. Applied feature selection methods (full features, filter-based, and wrapper-based).
  3. Evaluated six machine learning models: Logistic Regression, Decision Tree, SVM, Random Forest, Bagging, and Gradient Boosting.

---

## 🔍 Key Findings

- **Top-performing Models**:
  - **Decision Tree**: Achieved the highest AUC (99.29%).
  - **Random Forest**: Delivered the best accuracy and F1 score (95.47%).
- **Top Features**:
  - Hospitalization status (`Patient_Type`)
  - Ventilation (`Intubed`)
  - Pneumonia status (`Pneumonia`)
  - Age

---

## 🚀 Repository Structure

- `covid_outcome_analysis.ipynb`: Contains the Python code and step-by-step analysis.
- `Covid_Project_Report.pdf`: Comprehensive report detailing methods, challenges, and results.

---

## 📊 Methodology

- **Data Preprocessing**: Converted missing data to meaningful values and balanced the dataset.
- **Feature Selection**:
  - Full Model: Used all features.
  - Filter Model: Selected features with correlations above a threshold.
  - Wrapper Model: Applied forward selection for optimal features.
- **Modeling and Evaluation**:
  - Applied 75% training and 25% testing split.
  - Used metrics such as accuracy, F1 score, and AUC for evaluation.

---

## 💡 Future Work

- Improve computational resources for faster execution and scalability.
- Test additional ensemble techniques and advanced hyperparameter tuning.
- Incorporate external datasets to enhance generalizability.

---

**Explore the repository and uncover insights into predictive modeling for public health!** 😊

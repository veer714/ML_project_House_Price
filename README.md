# 🏡 House Price Prediction - Internship ML Project

## 📌 Project Overview
This project applies **Machine Learning Regression** to predict house prices based on structural and amenity features.  
It demonstrates an end-to-end ML workflow: data preprocessing, exploratory data analysis (EDA), model training, evaluation, and feature importance analysis.

---

## 📂 Dataset
- **Rows:** 545
- **Target Variable:** `price`

---

## 🔍 Workflow
1. **Data Preparation**
   - Cleaned dataset and handled missing values
   - Encoded categorical variables
   - Train/test split (80/20)

2. **Exploratory Data Analysis (EDA)**
   - Distribution plots for numerical features
   - Bar charts for categorical features
   - Correlation heatmap to identify predictors

3. **Model Training**
   ```python
   lr = LinearRegression()
   lr.fit(X_train, y_train)
   y_pred = lr.predict(X_test)

# 🏠 House Price Prediction using CatBoost Regressor

This project predicts house prices based on features such as area using a powerful gradient boosting algorithm — **CatBoost Regressor**. It's a part of my data science learning journey to apply real-world machine learning techniques on structured data.

## 📌 Problem Statement

Build a regression model to accurately predict the price of a house based on the available features such as area (and any others used). The goal is to minimize the prediction error and understand which features impact housing prices most.

## 🧰 Tools & Technologies Used

- Python
- Pandas, NumPy
- CatBoost
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## 📂 Dataset

- The dataset contains features like `Area`, `Location`, `parking`,'furnishing status', etc.
- Preprocessing included handling missing values, encoding categorical data, and feature scaling where necessary.

## 📊 Model

- **Model Used**: CatBoost Regressor
- Reason for selection: Handles categorical variables automatically and performs well with minimal tuning.

### ✅ Performance Metrics

- R² Score: `0.6396` 
- MSE: `1821818422007.28` 

## 📈 Visualizations

- Correlation Matix using heatmap
- Histogram for sepate bins

## 🧠 What I Learned

- How to preprocess and clean structured data
- How gradient boosting models like CatBoost work
- Evaluating regression models using various metrics
- Importance of feature engineering and hyperparameter tuning

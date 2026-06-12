# Rce-time-prediction-F1
# 🏎️ Formula 1 Race Time Prediction

## 📌 Project Overview

This project is a Machine Learning pipeline built to predict Formula 1 race times using historical data from the Kaggle Formula 1 dataset (1950–2020).

The goal is to explore race data, engineer meaningful features, and compare multiple regression models to achieve the best prediction performance.

---

## 📊 Dataset

The dataset is sourced from Kaggle:

👉 Formula 1 World Championship Dataset (1950–2020)

It includes information about:
- Races
- Drivers
- Constructors
- Lap times
- Pit stops
- Results

---

## ⚙️ Project Pipeline

The project follows a complete data science workflow:

1. 📥 Data Loading (Kaggle API + Google Drive)
2. 🧹 Data Cleaning & Preprocessing
3. 🔧 Feature Engineering
4. 📊 Exploratory Data Analysis (EDA)
5. ⏳ Time-based Train/Test Split (to avoid data leakage)
6. 🤖 Model Training:
   - Ridge Regression
   - LightGBM
   - XGBoost
7. 🔍 Hyperparameter Optimization using Optuna
8. 📈 Model Evaluation
9. 📉 Error Analysis (Residuals)

---

## 🧠 Machine Learning Models

The following models were tested:

- Linear Model: Ridge Regression
- Gradient Boosting: LightGBM
- Gradient Boosting: XGBoost

Each model was evaluated using metrics such as:
- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)

---

## 🏆 Results

The best performing model in this project was:

- ✅ Ridge Regression

This shows that a simpler model generalized better than more complex models on this dataset.

---

## 🛠️ Technologies Used

- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- LightGBM
- XGBoost
- Optuna
- Matplotlib / Seaborn
- Google Colab

---

## 🚀 How to Run the Project

Clone the repository:

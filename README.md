## Rainfall-Prediction-using-Machine-Learning

## Project Overview
The goal of this project is to predict whether it will rain tomorrow based on historical weather data from Australia. The dataset used is the Rainfall in Australia dataset, which includes features like temperature, humidity, wind speed, cloud cover, and historical rainfall records from various weather stations.

## Website Link


## 📊 Dataset
- Source: [Kaggle - Rainfall in Australia](https://www.kaggle.com/jsphyg/weather-dataset-rattle-package)
- Size: ~140,000 rows
- Target: `RainTomorrow` (Yes/No)

## ⚙️ Preprocessing
- Handled missing values with imputation
- Encoded categorical features
- Feature engineering (RainToday, Season, Month, etc.)
- Normalization and train-test split

## 🤖 Models Tested
| Model | ROC-AUC Score |
|-------|---------------|
| Logistic Regression | ~0.78 |
| Random Forest | ~0.85 |
| XGBoost | ~0.86 |
| SVC | ~0.82 |
| **CatBoost** | **~0.89** ✅ Best

## 🏆 Best Model: CatBoost
- Native support for categorical features
- High performance on tabular data
- ROC-AUC: **89%**


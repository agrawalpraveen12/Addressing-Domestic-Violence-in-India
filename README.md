# 🔍 Domestic Violence Prediction in India (2001–2021)

A data-driven project leveraging machine learning to analyze and predict domestic violence cases in India using crime statistics and socio-crime features from 2001 to 2021.

## 📌 Project Overview

This project explores the intersection of data science and social welfare. Using crime data related to women in India, we built regression models to forecast domestic violence cases and visualized key patterns across states and time. The insights generated can help support data-driven policymaking and awareness initiatives.

---

## 📂 Dataset

The primary dataset used:
- `CrimesOnWomenData.csv`: Contains yearly crime statistics for Indian states from 2001 to 2021.

Key columns:
- Rape Cases  
- Dowry Deaths  
- Kidnap and Assault  
- Domestic Violence  
- Assault on Women  
- Assault on Minors  
- Witchcraft  
- State, Year, Total Cases  

---

## 🎯 Objectives

- Analyze temporal and geographic DV trends  
- Identify top predictors of domestic violence  
- Build and evaluate ML models for prediction  
- Visualize insights for policy and awareness  

---

## 🔧 Tools & Technologies

- Python (Pandas, NumPy, Seaborn, Matplotlib, Plotly)
- Machine Learning: Scikit-learn, XGBoost, RandomForest
- Jupyter Notebook / Google Colab
- LaTeX for documentation and reporting

---

## 📊 Exploratory Data Analysis

EDA involved:
- Trend analysis of DV cases over time
- State-wise crime distributions
- Correlation heatmaps
- Feature distributions and ratios

Visuals included in `/images/`:
- `dv_cases_by_state.png`
- `dv_trend.png`
- `correlation_heatmap.png`
- `actual_vs_predicted.png`
- `residuals.png`
- `feature_importance.png`

---

## 🤖 Modeling

Three regression models were evaluated:
- Linear Regression: R² = 0.54
- Random Forest: R² = 0.80
- **XGBoost**: R² = **0.83** (Best performer)

Hyperparameter tuning was performed using `GridSearchCV`.

---

## ✅ Results

- **Best MAE:** 608 (XGBoost)  
- **Best R² Score:** 0.83  
- Key predictors: Dowry Deaths, Rape, Assault on Women

---

## 🙌 Author

**Praveen Agrawal**  
MSc Data Science – IIIT Lucknow 
📅 June 2025

---

## 📎 License

This project is released under the [MIT License](LICENSE).

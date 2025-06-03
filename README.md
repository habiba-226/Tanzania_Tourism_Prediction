# 🧠 Tourism Expenditure Prediction

This project focuses on predicting the **total expenditure of tourists** visiting Tanzania based on detailed trip information, demographic factors, and travel packages. The goal is to aid tourism boards and agencies in understanding the key drivers of spending behavior and enhancing strategic decision-making.

---

## 🎯 Objective

Develop a robust regression model using ensemble techniques to accurately forecast total spending per tourist. This enables data-driven budgeting, personalized marketing, and optimized service offerings.

---

## 🧪 Project Overview

- **Exploratory Data Analysis (EDA)** to understand patterns in demographics, trip attributes, and spending.
- **Data Cleaning & Feature Engineering** to enhance prediction performance.
- **Modeling using Advanced Regressors** like CatBoost, XGBoost, LightGBM, SVR, and others.
- **Stacking and Blending** of multiple models for improved accuracy.
- **Final Evaluation** using Mean Absolute Error (MAE) as the performance metric.

---

## 📊 Key Insights

- **Younger tourists (ages 1–64)** tend to spend more when traveling with spouses and children.
- **Dominica** had the highest tourist spending among all countries.
- **Accommodation and food** were the most frequently included items in travel packages.
- **Group size, country of origin, and travel arrangement type** were among the most important predictors of total cost.

---

## 🏆 Best Model

- **Model:** CatBoost Regressor  
- **Performance Metric (MAE):** 5.15 Million  
- The CatBoost model outperformed all others, showing superior accuracy in predicting total tourism expenditure.

---

## 🧠 Top 10 Most Important Features

| Rank | Feature                      | Insight                                                             |
|------|------------------------------|---------------------------------------------------------------------|
| 1    | Total persons                | Group size is the strongest predictor of spending                   |
| 2    | Country                      | Country of origin significantly impacts expenditure                 |
| 3    | Package Tour Arrangement     | Organized tours are major spending drivers                          |
| 4    | Total nights spent           | Longer trips result in higher total costs                           |
| 5    | Nights spent on mainland     | More nights on mainland influence total expenditure                 |
| 6    | Package - International Trans| Transport packages increase spending                                |
| 7    | Age group                    | Age demographics impact spending habits                             |
| 8    | Nights in Zanzibar           | Zanzibar visits contribute to higher trip costs                     |
| 9    | Package - Accommodation      | Inclusion of accommodation influences overall costs                 |
| 10   | Number of females            | Gender composition has moderate impact                              |

---

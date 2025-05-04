# 🌧️ Cloudburst Prediction Using Machine Learning

This repository contains my final report for the course *Practicum in Data Analysis*, part of the Columbia QMSS Master’s Program. The project focuses on predicting cloudburst events using machine learning models applied to NOAA Local Climatological Data (LCD). It combines domain-informed feature engineering, rare-event detection strategies, and model evaluation across multiple algorithms.

## 📘 Project Summary

Cloudbursts—short but extreme rainfall events—can lead to severe flooding and damage, yet are difficult to predict due to their rarity and localized nature. In this project, I used 10 years of hourly weather station data to construct a prediction pipeline. I engineered meteorologically relevant features (e.g., pressure changes, dew point depression, precipitation accumulation), applied models like Random Forests and Autoencoders, and evaluated performance with a focus on rare-event sensitivity.

## 📂 Files

- `Weather Data Exploration_Ariel Shao.ipynb`
  Initial data exploration and preprocessing steps. Includes visualizations, summary statistics, and variable selection rationale.

- `Heavy Rainfall Forecasting_Ariel Shao.ipynb`  
  Model implementation notebook, including Random Forest and autoencoder models, feature selection, hyperparameter tuning, and performance evaluation.

- `Improving Cloudburst Prediction_Ariel Shao.ipynb`  
  Applies feature engineering (e.g., dry period duration, interaction terms) and a Random Forest model to improve cloudburst prediction.

- `Final Report_Weixuan (Ariel) Shao.pdf`
  Full final report summarizing methodology, results, ethical considerations, and reflections.

## 📑 Report Contents

The full report is available [here.](https://github.com/weixuanshao/cloudburst-prediction-ariel/blob/main/Final%20Report_Weixuan%20(Ariel)%20Shao.pdf) 

The report is organized into the following sections:

1. **Problem Statement**
2. **Literature Review**
3. **Data Processing and Feature Engineering**
4. **Model Implementation and Evaluation**
5. **Ethical Considerations**
6. **AI Assistant Use and Process Reflection**
7. **Conclusion and Future Directions**

## 🛠️ Tools and Technologies

- **Languages & Libraries**: Python, pandas, NumPy, scikit-learn, matplotlib, seaborn
- **Data Source**: NOAA Local Climatological Data (LCD)
- **AI Assistance**: ChatGPT (for debugging, research summarization, feature engineering assistance)

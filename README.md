# Predicting Energy Consumption

## Overview
This project focuses on forecasting energy consumption using historical hourly demand data. 
The objective is to demonstrate an end-to-end machine learning workflow, emphasizing data understanding,
feature engineering, model selection, and evaluation rather than production-level accuracy.

## Dataset
- Six years of hourly energy consumption data
- Univariate time series with strong seasonal patterns

## Approach
- Data preprocessing and missing value handling
- Time-based feature engineering (lags, rolling statistics)
- Model comparison using machine learning models
- Evaluation using MAE and RMSE
- Interpretation of results and limitations

## Evaluation Metrics
- **MAE (Mean Absolute Error)** for average prediction accuracy
- **RMSE (Root Mean Squared Error)** to penalize large forecasting errors, especially during peak demand periods

## Key Insights
- The model captures overall trends and seasonality effectively
- Prediction errors increase during peak demand hours
- Incorporating exogenous variables (weather, holidays) could improve performance

## Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn

## Disclaimer
This project was developed for academic/assessment purposes, focusing on methodology and interpretability.

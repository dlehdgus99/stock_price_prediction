# Financial Data Prediction with XGBoost and Optuna

This project focuses on predicting financial market data using machine learning techniques. It combines data preprocessing, feature engineering, model training with XGBoost, and hyperparameter optimization using Optuna to achieve the best predictive performance.

## Overview

- **Bid Price and Ask Price**: Introduction to key financial concepts relevant to the data.
- **Data Preprocessing**: Steps to prepare the dataset for analysis, including handling missing data and feature scaling.
- **Feature Engineering**: Techniques employed to create new features that can improve model predictions.
- **XGBoost Regressor Model**: Details on using the XGBoost framework for modeling.
- **Hyperparameter Tuning with Optuna**: Optimization of model parameters for improved accuracy.
- **Model Visualization**: Insights into the data and model through various visualization techniques.

## Setup and Installation

1. Ensure Python 3.x is installed.
2. Install required libraries: `pip install pandas numpy sklearn matplotlib seaborn xgboost optuna`.

## Data Preprocessing

- Splitting the dataset.
- Handling missing values through forward filling and zero filling.
- Feature scaling for numerical variables.

## Feature Engineering

- Calculation of new features such as average prices and sizes.
- Introduction of time-based features.
- Implementation of rolling window features for time-series analysis.

## Modeling

- Training an XGBoost Regressor model.
- Evaluating model performance using time-series cross-validation.

## Hyperparameter Tuning

- Using Optuna to find the optimal set of parameters for the XGBoost model.

## Visualization

- Various plots for model evaluation and insight generation: feature importance, scatter plots, correlation heatmap, time series, and box plots.

## Conclusion

- Summary of findings and model performance.
- Suggestions for further improvements and experimentation.
# Predicting Personal Remittances in Saudi Arabia

## Overview

This project explores and predicts **Personal Remittances, Received (current US$)** in Saudi Arabia using machine learning models. The analysis combines economic and migration indicators to build predictive models, aiming to uncover insights into remittance trends and improve forecasting accuracy.

## Features

- Data preprocessing and feature engineering
- Exploratory data analysis with visualizations
- Implementation of machine learning models:
  - Linear Regression
  - Random Forest Regressor
  - Gradient Boosting Regressor
- Model evaluation and performance comparison

## Technologies Used

- **Programming Language:** Python
- **Libraries:**
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - statsmodels

## Dataset

The data was sourced from multiple World Bank indicators and focused on Saudi Arabia. Key features include:

- **Target Variable:** Personal Remittances, Received (current US$)
- **Features:**
  - Population, Total
  - Net Migration
  - GDP Growth (Annual %)
  - Unemployment Rate (%)
  - Remittance Growth Rate
  - Remittance per Capita
  - Remittance Volatility
  - Remittance-to-GDP Ratio

### Data Processing Steps

1. Merging multiple datasets into a unified DataFrame.
2. Filtering data for Saudi Arabia and years 1990 onward.
3. Handling missing values using KNN imputation.
4. Feature engineering to create additional remittance-related indicators.

## Methodology

The project followed a structured workflow:

1. **Data Preprocessing:** Data cleaning, imputation, and feature engineering.
2. **Exploratory Analysis:** Visualization of trends and relationships between indicators.
3. **Model Implementation:** Training and evaluating three machine learning models:
   - Linear Regression
   - Random Forest Regressor
   - Gradient Boosting Regressor
4. **Model Evaluation:** Comparing performance using:
   - Mean Absolute Error (MAE)
   - Root Mean Squared Error (RMSE)
   - R-squared (R²)

## Results

The Gradient Boosting model achieved the best results with:
- **MAE:** 16,557,204.53
- **R-squared:** 0.9944
- **RMSE:** 21,337,922.47

It outperformed Linear Regression and Random Forest, making it the most reliable model for predicting remittance trends.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/remittance-prediction-saudi-arabia.git

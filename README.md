# Walmart Sales EDA, Modelling & Forecasting

## Overview

This project involves an in-depth analysis of Walmart's sales data. The steps include Exploratory Data Analysis (EDA), building predictive models, and forecasting future sales based on historical data. The goal is to uncover patterns in the data, identify key features affecting sales, and create a robust forecasting model.

## Project Structure

This repository contains the following files and folders:

- **sales-eda-modelling-forecasting.ipynb**: Jupyter notebook with the code for data analysis, modelling, and forecasting.
  
## Requirements

To run the notebook and replicate the analysis, the following Python libraries are required:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `sklearn`
- `statsmodels`

You can install these libraries using the following command:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels

## Workflow

1. **Exploratory Data Analysis (EDA)**: In this phase, the Walmart sales data is explored for insights using visualizations, summary statistics, and feature analysis.
   
2. **Feature Engineering**: We create new features that might be influential for model performance, such as holiday periods, store details, and event-based promotions.

3. **Model Building**:
   - **Linear Regression**: A simple model for predicting sales.
   - **XGBoost**: An advanced model that uses boosting techniques to improve accuracy.
   - **ARIMA**: A time series forecasting model to predict future sales based on past data.
   
4. **Model Evaluation**: Evaluation metrics such as RMSE and MAE are calculated to compare model performances.

5. **Forecasting**: Based on the best-performing model, future sales are forecasted, providing actionable insights for business planning.

## How to Run the Project

1. Clone the repository:

   ```bash
   git clone <repository-url>

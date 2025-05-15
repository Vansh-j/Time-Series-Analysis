# Time Series Forecasting with Machine Learning

## Overview

This project focuses on forecasting future values in a time series using machine learning techniques. The dataset used contains hourly energy consumption data, and the goal is to build predictive models that can estimate future energy usage based on historical trends.

## Features

- Hourly energy consumption dataset
- Time-based feature engineering (hour, day of week, etc.)
- Data visualization and exploratory analysis
- Model training using regression algorithms
- Evaluation using MAE, RMSE, and R² scores
- Forecast visualization to compare predictions with actual values

## Project Structure

- **Data**: Raw and processed energy consumption data
- **Notebooks**: Step-by-step implementation in Python notebooks
- **Models**: Trained machine learning models for forecasting
- **Results**: Forecast outputs and performance charts

## Techniques Used

- Lag features and rolling window statistics
- Train-test split based on time (no random shuffling)
- Regression models (e.g., Linear Regression, Random Forest, Gradient Boosting)
- Time series-aware evaluation metrics

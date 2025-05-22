Retail Sales Forecasting

This project demonstrates retail sales forecasting using historical sales and external data. It is structured into several key stages, each handling a crucial part of the data pipeline: Data Collection, EDA, Feature Engineering, and Forecasting.

Project Structure

1. Data Collection
    - Collects historical sales data and external data (e.g., CPI, Gasoline Price, Holiday Type)
    - Sources of data: API, Kaggle 
2. EDA.ipynb: Exploratory Data Analysis
    - Performs a deep dive into the sales dataset
    - Identifies key trends, seasonal patterns, outliers, and distribution
    - Uses visualizations (line plots, bar charts, heatmaps) to understand:
        - Monthly sales variations
        - Yearly seasonality
        - Effects of major events
3. Feature Engineering: Data Preparation and Feature Engineering
    - Cleans and aggregates raw sales data
    - Prepares monthly time series data
    - Handles missing values, outliers, and data normalization
4. Forecasting: Model Implementation and Evaluation
    - Develops and evaluates several forecasting models, ranging from simple baselines to more advanced techniques
    - Implements:
        - Naive Forecast
        - Moving Average Forecast
        - Prophet (No Regressors)
        - Prophet (With Regressors)
    - Provides a side-by-side comparison of model accuracy using standard metrics and statistical significance tests

Key Components

- Time Series Decomposition: Breaks down the series into trend, seasonality, and residuals to understand underlying patterns
- Model Comparison: Comprehensive evaluation and statistical comparison of all implemented models

Goals and Objectives

- To develop a robust retail sales forecasting model using historical sales and external data
- To evaluate the performance of different forecasting models and identify the best approach
- To provide insights into sales trends and patterns to inform business decisions

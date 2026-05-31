# Sales & Demand Forecasting for Businesses

## Project Overview
This project focuses on forecasting sales using historical business data. The objective is to build a machine learning model that predicts future sales trends and helps businesses make data-driven decisions for inventory planning, demand management, and sales optimization.

## Dataset
The dataset contains historical sales information with the following columns:

- date
- store
- sales
- promo
- holiday

## Objective
To develop a sales forecasting model using machine learning techniques and generate business-friendly insights from historical sales data.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Project Workflow

### 1. Data Cleaning
- Checked for missing values
- Removed duplicate records
- Converted date column to datetime format

### 2. Time-Based Feature Engineering
Created the following features from the date column:
- year
- month
- day
- dayofweek
- weekofyear

### 3. Sales Forecasting Model
A Random Forest Regressor model was used to forecast sales based on:
- store
- promo
- holiday
- year
- month
- day
- dayofweek
- weekofyear

### 4. Model Evaluation
The model performance was evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

### 5. Error Analysis
Prediction errors were analyzed to understand model performance and forecasting accuracy.

### 6. Visualization
The following visualizations were created:

- Error Distribution
- Actual Sales vs Forecasted Sales

## Results
The model successfully learned sales patterns from historical data and generated sales forecasts for future business planning.

## Business Insights
- Promotional activities influence sales performance.
- Holiday periods affect customer demand.
- Seasonal patterns impact sales trends.
- Forecasting helps businesses improve inventory and resource planning.
- Historical sales data can be used to make better business decisions.

## Deliverables
- Sales Forecasting Model
- Jupyter Notebook
- Forecast Visualizations
- Business Insights Report

## Repository Structure

FUTURE_ML_01

├── Sales_Forecasting.ipynb

├── store_sales.csv

├── README.md

└── outputs 

## Author
K.Divya 

## Internship
Future Interns - Machine Learning Internship

Task 01: Sales & Demand Forecasting for Businesses

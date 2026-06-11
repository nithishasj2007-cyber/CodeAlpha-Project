# Car Price Prediction using Machine Learning

## Overview

This project predicts the selling price of a used car using Machine Learning techniques.

The workflow includes:

- Data Preprocessing
- Feature Engineering
- Model Training
- Model Evaluation
- Price Prediction

## Dataset

Dataset: car data.csv

Features:

- Car_Name
- Year
- Present_Price
- Driven_kms
- Fuel_Type
- Selling_type
- Transmission
- Owner

Target Variable:

- Selling_Price

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn

## Machine Learning Model

Random Forest Regressor

## Steps Performed

### 1. Data Preprocessing

- Checked missing values
- Converted categorical features into numerical values
- Removed unnecessary columns

### 2. Feature Engineering

Created a new feature:

Car_Age = Current Year - Manufacturing Year

### 3. Model Training

- Train-Test Split (80-20)
- Random Forest Regressor

### 4. Model Evaluation

Metrics used:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

## Results

The model successfully predicts used car prices based on:

- Car age
- Present price
- Kilometers driven
- Fuel type
- Transmission
- Ownership history

## Real-World Applications

- Used Car Marketplaces
- Automobile Dealers
- Vehicle Valuation Systems
- Insurance Pricing

## Author

Nithisha S J
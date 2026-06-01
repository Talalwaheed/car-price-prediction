# Car Price Prediction with Machine Learning

A machine learning project that estimates the selling price of a used car based on 
its features. The project walks through the full data science workflow — from data 
cleaning and encoding to model training, evaluation, and an interactive price 
predictor built with ipywidgets.

## Overview

Used car pricing is influenced by a wide range of factors including age, mileage, 
fuel type, transmission, and more. This project trains a Linear Regression model 
on a labeled car dataset to predict selling prices, then wraps the model in an 
interactive form where users can input vehicle details and receive an instant 
price estimate.

## What This Project Does

- Loads a car dataset CSV with automatic column cleaning and normalization
- Handles missing values and encodes categorical features using Label Encoding
- Visualizes feature correlations through a heatmap
- Scales features using StandardScaler for better model performance
- Trains a Linear Regression model on an 80/20 train-test split
- Evaluates the model using Mean Squared Error and R-squared score
- Plots actual vs predicted prices for visual performance assessment
- Provides an interactive widget-based UI to predict prices on custom inputs

## Model Evaluation

The model is evaluated using two metrics:

- **Mean Squared Error (MSE)** — measures the average squared difference between 
  actual and predicted prices
- **R² Score** — indicates how well the model explains the variance in car prices

## Tech Stack

- Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly)
- Scikit-learn (Linear Regression, StandardScaler, LabelEncoder)
- ipywidgets (interactive price prediction form)
- Google Colab

## Dataset

The project accepts any car sales CSV dataset containing a selling price column 
along with vehicle feature columns such as fuel type, transmission, mileage, 
year, and owner history.

## Author

M. Talal Bin Waheed

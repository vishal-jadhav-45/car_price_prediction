# Car Price Prediction using Linear Regression

## Project Overview

This project focuses on predicting the price of Ford cars using Machine Learning. The project uses a dataset containing 17,966 car records with features such as model, year, transmission, mileage, fuel type, tax, MPG, and engine size.

The project includes data exploration, exploratory data analysis (EDA), preprocessing, feature encoding, feature scaling, model training, and evaluation using Linear Regression.

## Dataset

The dataset contains 17,966 rows and 9 columns.

### Features

- Model
- Year
- Transmission
- Mileage
- Fuel Type
- Tax
- MPG
- Engine Size

### Target

- Price

## Exploratory Data Analysis

The project performs EDA to understand the relationship between car prices and different features.

EDA includes:

- Price distribution analysis
- Correlation analysis
- Price vs Year
- Price vs Mileage
- Price vs Engine Size
- Price vs Transmission
- Price vs Fuel Type
- Price vs Car Model
- Price vs MPG

## Data Preprocessing

The following preprocessing steps were performed:

- Separated features and target variable
- Applied one-hot encoding to categorical features
- Applied feature scaling using StandardScaler
- Split the dataset into training and testing sets

## Machine Learning Model

### Linear Regression

Linear Regression was used to predict car prices based on the available features.

The dataset was divided into:

- 80% Training Data
- 20% Testing Data

## Model Performance

- R² Score: 0.8464
- Adjusted R² Score: 0.8450

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Structure

```text
car-price-prediction/
│
├── car_price_prediction_project.ipynb
├── ford.csv
└── README.md

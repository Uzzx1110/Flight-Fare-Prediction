# Flight Price Prediction

This project aims to predict flight prices using machine learning techniques. It analyzes various factors affecting flight fares and develops a model to estimate prices for future flights.

## Table of Contents
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Feature Engineering](#feature-engineering)
- [Model Building](#model-building)
- [Model Evaluation](#model-evaluation)

## Dataset

The dataset contains information about flight bookings, including:
- Airline
- Date of journey
- Source and Destination
- Route
- Departure and Arrival times
- Duration
- Total Stops
- Additional Information

## Data Preprocessing

- Handled missing values
- Converted date and time features to appropriate formats
- Extracted additional features from existing data

## Exploratory Data Analysis

- Analyzed the distribution of flight prices
- Explored relationships between various features and flight prices
- Visualized patterns and trends in the data

## Feature Engineering

- Created new features from existing data
- Encoded categorical variables
- Scaled numerical features

## Model Building

Several machine learning models were trained and evaluated:
- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

## Model Evaluation

Models were evaluated using the following metrics:
- R-squared Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

The Random Forest Regressor performed the best with an R-squared score of 0.8191 on the test set.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost

## Usage

1. Ensure all required libraries are installed.
2. Run the Jupyter notebook to preprocess data, train models, and make predictions.
3. Use the trained model to predict flight prices for new data.

## Future Work

- Experiment with more advanced machine learning algorithms
- Incorporate additional relevant features
- Deploy the model as a web application for easy access

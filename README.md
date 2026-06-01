# Vehicle CO₂ Emission Prediction using Databricks

## Project Overview

This project predicts vehicle CO₂ emissions using machine learning models built on Databricks with PySpark and Spark SQL.
The objective is to estimate CO₂ emissions based on vehicle specifications such as engine size, cylinders, fuel type, transmission type, and fuel consumption metrics.

## Technologies Used

* Databricks
* PySpark
* Spark SQL
* Delta Lake
* MLflow
* Python
* Machine Learning

## Dataset

Vehicle CO₂ Emissions Dataset from Kaggle.

Features:

* Engine Size
* Cylinders
* Transmission
* Fuel Type
* Fuel Consumption (City)
* Fuel Consumption (Highway)
* Fuel Consumption (Combined)

Target:

* CO₂ Emissions (g/km)

## Project Workflow

1. Data Ingestion
2. Data Cleaning
3. Exploratory Data Analysis using SQL
4. Feature Engineering
5. Model Training
6. Model Evaluation
7. Prediction Generation

## Machine Learning Models

* Linear Regression
* Random Forest Regressor
* Gradient Boosted Tree Regressor

## Evaluation Metrics

* RMSE
* MAE
* R² Score

## Results

The best performing model was selected based on RMSE and R² performance.

## Future Improvements

* Hyperparameter tuning
* Model deployment
* Real-time prediction API
* Power BI Dashboard integration


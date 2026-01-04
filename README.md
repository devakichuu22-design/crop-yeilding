# crop-yeilding
Project Overview

This project focuses on predicting crop yield using basic machine learning techniques in Python. The model estimates crop yield (kg/acre) based on soil nutrients, environmental conditions, and fertilizer usage.
It is implemented using Linear Regression and common data science libraries.

This project is suitable for academic submissions, mini projects, and ML practice.
Problem Statement

Crop yield depends on multiple factors such as:

Soil nutrients (Nitrogen, Phosphorus, Potassium)

Rainfall

Temperature

Fertilizer usage

Soil pH


Fertilizer usage

Soil pH
Dataset Description

The dataset is created within the notebook and contains the following features:

Feature Name	Description
Nitrogen	Nitrogen content in soil
Phosphorus	Phosphorus content in soil
Potassium	Potassium content in soil
Rainfall_mm	Rainfall in millimeters
Temperature_C	Temperature in Celsius
Fertilizer_kg	Fertilizer used (kg)
Soil_pH	Soil pH value
Yield	Crop yield (kg/acre) – Target variable
Project Workflow

Import libraries

Create and load dataset

Exploratory Data Analysis (EDA)

Dataset shape and info

Summary statistics

Yield distribution visualization

Feature selection

Train-test split

Model training using Linear Regression

Model evaluation

Mean Squared Error (MSE)

R² Score
Machine Learning Model

Algorithm Used: Linear Regression

Why Linear Regression?

Simple and effective for continuous value prediction

Easy to interpret

Suitable for small datasets

Model Evaluation Metrics

Mean Squared Error (MSE) – Measures prediction error

R² Score – Measures model accuracy
How to Run the Project

Clone or download the repository

Open the notebook:

crop yeilding.ipynb


Run all cells in order using Jupyter Notebook or Google Colab

Output

Visualization of crop yield distribution

Trained regression model

Performance metrics (MSE and R² score)

Crop yield prediction based on input features
Applications

Agricultural decision support systems

Smart farming

Academic ML projects

Yield estimation studies

 Future Enhancements

Use real-world datasets

Apply advanced models (Random Forest, XGBoost)

Add feature scaling

Deploy as a web application

Include weather API integration

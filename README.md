# Fuel-Consumption-rating---Linear-Regression
This repository contains a linear regression analysis of the Fuel Consumption Ratings dataset. The goal is to predict the Smog Rating based on various vehicle characteristics and fuel consumption metrics.

#Dataset Overview:
The dataset includes features such as:
Make: The manufacturer of the vehicle.
Model: The specific model of the vehicle.
Model Year: The year the vehicle was manufactured.
Fuel Type: Type of fuel used by the vehicle.
Transmission: Type of transmission in the vehicle.
Fuel Consumption: Various metrics for fuel consumption (city, highway, combined).
CO2 Emissions: CO2 emissions in grams per kilometer.
Smog Rating: Target variable indicating the smog rating of the vehicle.

#Key Steps in the Analysis
Data Loading and Overview: Load the dataset using Pandas and display basic information such as shape, data types, and missing values.
Exploratory Data Analysis (EDA):
Visualize the distribution of categorical features (Fuel Type, Transmission, etc.).
Analyze skewness and correlation among features.
Identify outliers using interquartile range (IQR).
Data Preprocessing:
One-hot encode categorical variables.
Standardize numerical features using StandardScaler.
Modeling:
Split the data into training and testing sets.
Train and evaluate several regression models: Linear Regression, Lasso, Ridge, and Elastic Net.
Model Evaluation:
Calculate and display performance metrics including R² score, Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE) for each model.

#Requirements
To run this analysis, you will need the following Python libraries:
numpy
pandas
seaborn
matplotlib
plotly
scikit-learn
scipy

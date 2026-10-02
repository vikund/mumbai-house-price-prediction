# Mumbai House Price Prediction

An end-to-end machine learning project for predicting house prices in Mumbai using real-world property listing data.

## Project Overview

In this project, Mumbai house-price data was cleaned, explored, transformed, and used to build regression models for house-price prediction.

The project covers the complete basic machine learning workflow:

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Log Transformation
* Train-Test Split
* Feature Scaling
* One-Hot Encoding
* Linear Regression
* Ridge Regression
* Lasso Regression
* Hyperparameter Tuning using GridSearchCV
* Model Evaluation
* Overfitting Check

## Dataset

The dataset contains Mumbai property listings with information such as:

* BHK
* Property type
* Locality
* Area
* Price
* Region
* Status
* Age

The target variable used for modelling was house price in lakhs, transformed using a logarithmic transformation.

## Models Used

Three regression models were trained and compared:

1. Linear Regression
2. Ridge Regression
3. Lasso Regression

Ridge and Lasso hyperparameters were selected using 5-fold GridSearchCV.

## Results

The models were evaluated using R² and RMSE on the test set.

The final selected model was **Ridge Regression**.

* Test R²: **0.9495**
* Best Ridge alpha: **0.1**

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab

## Project File

The complete machine learning implementation is available in the `.ipynb` notebook included in this repository.


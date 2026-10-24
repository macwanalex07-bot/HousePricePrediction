# House Price Prediction Using Regression Models

## Project Overview

This project focuses on predicting house prices using various Supervised Machine Learning Regression techniques. The dataset contains information about house characteristics such as area, bedrooms, bathrooms, location score, age of property, garage availability, pool availability, and other factors affecting house prices.

The objective is to compare different regression models and determine which model provides the best prediction performance.

---

## Dataset Information

The dataset contains 4200 records and 12 columns.

### Features

* house_id
* area_sqft
* bedrooms
* bathrooms
* location_score
* age_years
* distance_city_km
* lot_size_sqft
* has_garage
* has_pool
* renovation_years_ago

### Target Variable

* house_price_inr

### Data Preprocessing

* Checked for missing values
* Removed identifier column (house_id)
* Defined independent and dependent variables
* Split data into training and testing sets

---

## Machine Learning Models Used

### 1. Simple Linear Regression

Simple Linear Regression was implemented using a single feature:

* area_sqft

Purpose:

* To understand the relationship between house area and house price.

---

### 2. Multiple Linear Regression

Multiple Linear Regression was implemented using all relevant features:

* area_sqft
* bedrooms
* bathrooms
* location_score
* age_years
* distance_city_km
* lot_size_sqft
* has_garage
* has_pool
* renovation_years_ago

Purpose:

* To improve prediction accuracy by utilizing all available information.

---

### 3. Polynomial Regression

Polynomial Regression (Degree = 2) was implemented to capture non-linear relationships between features and house prices.

Purpose:

* To model complex relationships that cannot be captured by linear regression.

---

### 4. Gradient Descent (SGD Regressor)

Stochastic Gradient Descent (SGD) was implemented for optimization and model training.

Purpose:

* Efficient learning on large datasets.
* Faster optimization compared to traditional methods.

---

## Evaluation Metrics

The following metrics were used to evaluate model performance:

### Mean Absolute Error (MAE)

Measures average prediction error.

### Mean Squared Error (MSE)

Measures squared prediction error.

### Root Mean Squared Error (RMSE)

Provides error in the same unit as the target variable.

### R² Score

Measures how well the model explains the variance in house prices.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Project Workflow

1. Data Collection
2. Data Exploration
3. Data Cleaning
4. Data Visualization
5. Feature Selection
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Performance Comparison
10. Final Conclusion

---

## Results

The regression models were trained and evaluated using R² Score, MAE, MSE, and RMSE.

After comparison, the model with the highest R² Score and lowest prediction error was selected as the best-performing model for house price prediction.

---

## Conclusion

This project demonstrates how supervised machine learning techniques can be used to predict house prices. Multiple Linear Regression and Polynomial Regression generally provide better performance than Simple Linear Regression because they utilize more information from the dataset.

The project highlights the importance of feature selection, model evaluation, and bias-variance analysis in building effective predictive models.

---

## Author
Alex Macwan

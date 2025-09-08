# Linear Regression Example Project

## Overview
This project demonstrates **linear regression**, a supervised learning technique used to predict a **continuous value** based on input features. Linear regression models the relationship between the **independent variable(s)** and a **dependent variable** by fitting a straight line.

---

## How It Works
The goal of linear regression is to find the line (or hyperplane for multiple features) that **best fits the data**:

\[
y = b_0 + b_1x_1 + b_2x_2 + \dots + b_nx_n
\]

- \(y\) → predicted value  
- \(x_i\) → feature values  
- \(b_i\) → coefficients (weights)  
- \(b_0\) → intercept  

The line is chosen to **minimize the difference** between predicted and actual values, typically using **Mean Squared Error (MSE)**.

---

## Example Use Case
- Predicting **house prices** based on size, location, and number of bedrooms.  
- Forecasting **sales** based on advertising spend.  
- Estimating **temperature** for tomorrow based on historical data.

---

## Evaluation Metrics
Linear regression performance can be measured using:  
- **Mean Squared Error (MSE)** → Average squared difference between predicted and actual values.  
- **Root Mean Squared Error (RMSE)** → Square root of MSE, in the same units as the target.  
- **R² Score** → Proportion of variance in the dependent variable explained by the model.

---

## Implementation Steps
1. Load and inspect the dataset.  
2. Split the data into **training** and **test** sets.  
3. Train a **linear regression model** on the training set.  
4. Make predictions on the test set.  
5. Evaluate the model using metrics like MSE or R².  

---

This project demonstrates the basics of **linear regression**, including building, predicting, and evaluating a simple predictive model.


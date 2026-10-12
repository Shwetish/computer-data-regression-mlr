# Computer Hardware Price Prediction Model
Multilinear regression model to predict computer system pricing based on hardware specifications like RAM, hard drive storage, and speed

## 1. Business Problem
* **1.1 Business Objective**: Build an automated pricing tool for computer hardware using key attributes (such as speed, RAM, hard drive size, screen dimensions, and multimedia features).

## 2. Data Pre-processing & Feature Engineering
* Cleaned hardware specification columns and handled categorical indicator variables (e.g., CD drive, premium status).
* Treated outliers affecting price variance.

## 3. Model Building & Validation
* Fitted multilinear regression models on scaled hardware metrics.
* Checked regression diagnostics including VIF for collinearity among processor and memory variables, alongside residual plots.
* Evaluated models using **RMSE** and **R-Squared** tabulations.

## 4. Business Impact
* Enables retailers and manufacturers to dynamically price computer inventory according to market standards and hardware configurations.

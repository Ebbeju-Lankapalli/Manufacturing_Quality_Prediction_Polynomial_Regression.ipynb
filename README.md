# Manufacturing Quality Prediction using Polynomial Regression

## Overview

This project predicts the Quality Rating of manufactured products using Polynomial Regression. The model captures both linear and non-linear relationships between manufacturing process parameters such as temperature, pressure, interaction terms, and derived material metrics.

---

## Problem Statement

Investigate how various process parameters affect product quality by building a Polynomial Regression model. The goal is to capture both linear and non-linear relationships between factors such as temperature, pressure, and derived interaction and transformation metrics to predict the overall quality rating of manufactured items.

---

## Dataset Information

### Input Features

#### Temperature (°C)
Temperature during the manufacturing process that influences material properties and final product quality.

#### Pressure (kPa)
Applied pressure during production that affects material transformation and process outcomes.

#### Temperature × Pressure
Interaction feature representing the combined effect of temperature and pressure.

#### Material Fusion Metric
Derived metric representing material fusion characteristics.

#### Material Transformation Metric
Derived metric representing material transformation behavior.

### Target Variable

#### Quality Rating
Overall quality score of the manufactured product.

---

## Project Workflow

### 1. Data Loading

### 2. Exploratory Data Analysis (EDA)

### 3. Missing Value Analysis

### 4. Duplicate Detection

### 5. Correlation Analysis

### 6. Feature Engineering

### 7. Polynomial Feature Generation

### 8. Model Building

### 9. Model Training

### 10. Model Evaluation

### 11. Residual Analysis

### 12. Test Prediction

### 13. Submission File Generation

---

## Technologies Used

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Machine Learning Algorithm

### Polynomial Regression

Polynomial Regression extends Linear Regression by introducing polynomial terms, allowing the model to learn non-linear relationships between features and the target variable.

### Pipeline Components

#### StandardScaler
Standardizes feature values before training.

#### PolynomialFeatures
Generates polynomial and interaction features.

#### LinearRegression
Fits the regression model on transformed features.

---

## Evaluation Metrics

### Mean Squared Error (MSE)

### Root Mean Squared Error (RMSE)

### R² Score

---

## Visualizations

### Correlation Heatmap

### Actual vs Predicted Plot

### Residual Plot

---

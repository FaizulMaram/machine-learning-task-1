# Machine Learning Task 1

This repository contains the implementation of Machine Learning Task 1 for the DS-550 Machine Learning course.

The task covers the mathematical foundations and practical implementation of regression and classification techniques using Python.

## Overview

### Q1 — Regression Derivations
Derivation of gradient descent/ascent update rules from the maximum likelihood perspective for:

- Linear Regression
- Logistic Regression

### Q2 — Housing Price Prediction
Implementation of Linear Regression for predicting housing prices using:

- Gradient Descent
- Normal Equation
- Feature Scaling
- Learning Rate Comparison
- Model Evaluation using MSE, RMSE, and R² Score
- Mean Baseline Comparison
- Actual vs Predicted Price Visualization

The model uses the following features:

- Bedrooms
- Living Area (`living_in_m2`)
- Real Bathrooms

### Q3 — Polynomial Interpolation and Regression
Estimation of projectile force at a given velocity using:

- Fifth-degree polynomial interpolation
- Quadratic polynomial regression
- Comparison between interpolation and regression

### Q4 — Logistic Regression Classification
Implementation and comparison of Logistic Regression classifiers using:

- Linear Decision Boundary
- Non-linear Decision Boundary
- Classification Performance Analysis

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab

## Repository Structure

```text
Machine-Learning-Assignment-1/
│
├── machine_learning_assignment_1.ipynb
├── q2train.csv
├── q2test.csv
├── q4trainlr.csv
├── q4testlr.csv
└── README.md

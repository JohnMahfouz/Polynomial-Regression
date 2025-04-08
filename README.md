# Polynomial Regression for Predicting Revenue Per Day

## 📌 Overview

This project applies **Polynomial Regression** to predict **RevenuePerDay** using the dataset from `assignment1dataset.csv`. It demonstrates feature selection, data preprocessing, and the implementation of polynomial regression models using different degrees to determine the best-fit model. The performance of each model is evaluated using **Mean Squared Error (MSE)** on both training and testing datasets.

## 🛠️ Features

- **Feature Selection:** Identifies features that have a correlation greater than 0.5 with the target variable `RevenuePerDay`.
- **Data Preprocessing:** Scales the selected features to a range between 0 and 1.
- **Polynomial Regression:** Implements polynomial regression models of varying degrees (1 to 5) to predict the target.
- **Model Evaluation:** Uses Mean Squared Error (MSE) to evaluate the performance of the models.

## 🎯 Purpose

This project aims to:
- Demonstrate the use of polynomial regression to model a non-linear relationship between features and the target.
- Show how polynomial degree affects model performance and generalization (overfitting vs underfitting).
- Explore feature correlation and preprocessing techniques to improve model accuracy.

## 🔧 System Design

The script performs the following steps:
1. **Data Loading and Exploration:**
   - Reads the dataset and displays features that correlate highly with `RevenuePerDay`.
   - Visualizes feature correlations using a heatmap.
   
2. **Data Preprocessing:**
   - Scales the selected features using **min-max normalization**.
   
3. **Polynomial Regression Implementation:**
   - Creates polynomial features up to a degree of 5.
   - Fits a **Linear Regression** model to the polynomial features.
   
4. **Model Evaluation:**
   - Computes **Mean Squared Error (MSE)** for both training and testing datasets for each polynomial degree.

5. **Plotting MSE vs Polynomial Degree:**
   - Visualizes the relationship between polynomial degree and MSE for both train and test datasets.

## 📈 Results

The Mean Squared Error (MSE) for each polynomial degree is printed, and a plot is generated to show the performance of each model.

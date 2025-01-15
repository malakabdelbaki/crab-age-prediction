# crab-age-prediction

This repository contains a Jupyter Notebook showcasing a comprehensive machine learning workflow aimed at predicting the age of crabs. The project includes the implementation of multiple regression models and various techniques to enhance model performance.

## Overview

The primary objective of this project was to accurately predict crab age using features such as physical measurements. Multiple machine learning models were developed, tested, and compared to determine the best-performing approach.

## Models Attempted

1. **Linear Regression with Regularization**:
   - Lasso
   - Ridge
   - ElasticNet

2. **Polynomial Ridge Regression**:
   - Hyperparameter tuning
   - Outlier removal
   - Feature extraction
   - Feature Engineering

3. **Quantile Regression**

4. **RANSAC Regressor** (RANdom SAmple Consensus)

5. **Huber Regressor**

6. **Stacking Regressor**:
   - Combined Quantile and Huber Regressors

## Best Model

After extensive experimentation, **LightGBM** emerged as the best-performing model due to its superior predictive accuracy and ability to handle the dataset effectively.

## Features of the Project

- Comprehensive implementation of regression models with detailed comparisons.
- Exploration of advanced techniques like quantile regression and stacking.
- Hyperparameter tuning and outlier removal to optimize model performance.
- Detailed analysis of results and insights from different approaches.

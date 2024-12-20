# labeval
Overview
This project utilizes the PyCaret library to perform automated regression tasks on a given dataset (Fuel_cell_performance_data-Full.csv). I explore different feature transformations, normalization methods, feature selection techniques, and a variety of regression models to find the best model for predicting a target variable (Target3). Among all the evaluated models and transformations, Random Forest Regression (RF) proved to be the best-performing model.

Objective
The goal of this project is to compare several regression models under different conditions such as:

Transformation methods (e.g., Ye0-Johnson, Quantile)
Feature selection techniques (e.g., Classic, Univariate, Sequential)
Normalization methods (e.g., Z-score, Min-Max, Robust)
Model performance across different feature selection settings
aim is to identify the most efficient model and transformation for predicting fuel cell performance from the dataset.

Methodology
1. Data Preprocessing
2.  PyCaret Setup and Transformation Methods
3.  Feature Selection Methods
4.  Normalization Methods
5.   Model Evaluation
The following regression models were evaluated:

Random Forest (RF)
Extra Trees (ET)
LightGBM
XGBoost
Ridge Regression
Lasso Regression
KNN Regression
Huber Regression
ElasticNet (EN)

Conclusion
After evaluating multiple feature selection methods, transformations, and normalization techniques, Random Forest emerged as the best model for predicting fuel cell performance. It showed superior performance in terms of prediction accuracy, generalization, and robustness, making it the ideal choice for this regression task.
Best Model: Random Forest Regression (RF)
R² Score: RF achieved the best R² score, demonstrating its superior ability to fit the data and generalize to unseen examples.
Normalization Methods: The Z-score normalization method provided the best results when combined with Random Forest.
Feature Selection: The Sequential feature selection method proved effective in enhancing model performance, especially when the proportion of features to select was set to 0.2.

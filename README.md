# Medical Cost Personal Datasets Analysis

## Overview
This project involves analyzing medical cost data to derive insights about healthcare expenses and the factors influencing them. The analysis is performed using Python in a Jupyter Notebook, leveraging data analysis and visualization libraries.

## Dataset
The analysis uses the **Medical Cost Personal Datasets**, which contains information about:
- **Attributes**: Age, gender, BMI, number of children, smoking status, and region.
- **Target Variable**: Medical charges for each individual.

The dataset aims to understand the relationship between these attributes and medical costs.

## Objective
The goal of this project is to:
1. Explore the dataset to understand its structure and statistical properties.
2. Perform data preprocessing and cleaning.
3. Visualize key trends and relationships in the data.
4. Build and evaluate predictive models to estimate medical costs.

## Prerequisites
### Tools and Libraries
- Python 3.12
- Libraries used:
  - `pandas` for data manipulation
  - `numpy` for numerical computations
  - `matplotlib` and `seaborn` for data visualization
  - `scikit-learn` for machine learning models
  - `statsmodels` for statistical analysis

## Steps in the Analysis
1. **Data Loading and Exploration**:
   - Load the dataset.
   - Check for null or missing values.
   - Explore the statistical properties of the dataset.

2. **Data Preprocessing**:
   - Handle missing or inconsistent data.
   - Encode categorical variables.
   - Standardize numerical features for modeling.

3. **Exploratory Data Analysis (EDA)**:
   - Visualize the distribution of medical charges.
   - Analyze correlations between variables using heatmaps and pair plots.
   - Explore the impact of categorical variables (e.g., smoking status, region) on medical charges.

4. **Model Development**:
   - Train multiple regression models to predict medical costs.
   - Evaluate model performance using metrics such as Mean Squared Error (MSE), R-squared, and Mean Absolute Error (MAE).

## Models Used
The following regression models were implemented in the analysis:
1. **Linear Regression**:
   - A simple linear approach to predict medical charges based on independent variables.

2. **Lasso Regression**:
   - A linear regression model with L1 regularization to shrink less important coefficients to zero, improving model simplicity.

3. **Ridge Regression**:
   - A linear regression model with L2 regularization to reduce multicollinearity and improve prediction accuracy.

4. **ElasticNet Regression**:
   - Combines L1 and L2 regularization to balance sparsity and penalty, offering a robust model for feature selection and prediction.

### Model Evaluation Metrics
- **R-squared**: Measures the proportion of variance explained by the model.
- **Mean Squared Error (MSE)**: Captures the average squared difference between predicted and actual values.
- **Mean Absolute Error (MAE)**: Measures the average magnitude of prediction errors.


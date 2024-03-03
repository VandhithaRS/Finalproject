# Finalproject

# Regression Problem
## Overview
This project focuses on predicting the current health of an organism based on measurements from two biological sensors measuring their biomarkers. The target variable represents the health status, where negative values indicate health lesser than the average case. Linear regression models are applied to the training data, and metrics such as Mean Squared Error (MSE) and Mean Absolute Error (MAE) are evaluated on the test split.

## Dataset
The dataset can be found in the shared folder:
- Training data: `p1-train.csv`
- Test data: `p1-test.csv`
The last column in both datasets represents the target variable, i.e., the current health of the organism.

## Procedure
1. **Data Preparation**:
   - Load the training and test datasets from the provided CSV files.
2. **Model Application**:
   - Apply the following regression models:
     - Linear Regression
     - Support Vector Regression (SVR)
3. **Metrics Evaluation**:
   - Calculate Mean Squared Error (MSE) and Mean Absolute Error (MAE) for each model.

## Dependencies
- Python 3.x
- Libraries:
  - numpy
  - pandas
  - scikit-learn
  - matplotlib

## Conclusion
This project involves predicting organism health using regression techniques. By applying linear regression and SVR models, the goal is to accurately estimate health status based on biomarker measurements. Evaluation metrics such as MSE and MAE will provide insights into the performance of these models on the test dataset.

# Decision-Trees-and-Random-Forests
This project is about applying basic machine learning models on the diabetes dataset, using tree-based models like Decision Tree and Random Forest. It’s nothing too complicated — just training, checking results, and understanding performance.

# About the Dataset
The file is named diabetes.csv

It has around 442 rows and 10 input features like age, bmi, bp, s1 to s6

The target column is disease_progression, which is a numeric score

This dataset comes from scikit-learn’s built-in diabetes dataset.

# Models Used
# 1. Decision Tree Regressor
First, a simple Decision Tree model is trained.

It works by splitting the data step by step.

It can overfit easily if we don’t control its depth.

# 2. Random Forest Regressor
This uses many decision trees and averages their results.

It gives more stable results and handles overfitting better.

# Evaluation Metrics
R² Score: Shows how well the model fits the data. Closer to 1 is better.

RMSE (Root Mean Squared Error): Lower is better — it tells how far predictions are from actual values.

# What Was Done
The data was split into train and test sets

Decision Tree and Random Forest models were trained

Their performance was checked using R² and RMSE

Feature importance was also checked to see which inputs matter most.

# What Can Be Improved (Next Steps)
Use GridSearchCV to tune Random Forest parameters

Convert the target to a classification task and try classifier models

Use tools like SHAP or permutation importance to explain model results better.

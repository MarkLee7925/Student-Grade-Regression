# Student-Grade-Regression

The purpose of this Machine Learning regression project is to predict the final grades of students in Math and Portuguese class based on a variety of features. This was achieved using four different regression models to predict the final grades (out of 20). Each model was cross-validated and tuned to achieve the best possible accuracy with their optimal hyperparameters.

## Dataset:

Both datasets were retrieved from the UCI Machine Learning Repository (link: https://archive.ics.uci.edu/ml/datasets/student+performance). The Math dataset (student-mat.csv) contained 395 samples whereas the Portuguese dataset (student-por.csv) contained 649 samples.

Additional information about each feature can be found in the student_features.txt file.

## Models:

The following Machine Learning models were implemented:

- Decision Tree Regression (DT)
- Random Forest Regression (RF)
- LightGBM (LGB)
- XGBoost (XGB)

## Results

The accuracies of each model were measured using R-Squared (R^2) Goodness-of-Fit and Root Mean Squared Error (RMSE) scoring.

### Math

- Decision Tree - **R^2:** 0.869, **RMSE:** 1.483
- Random Forest - **R^2:** 0.880, **RMSE:**	1.451
- LightGBM - **R^2:** 0.883, **RMSE:**	1.451
- XGBoost - **R^2:** 0.904, **RMSE:**	1.311

### Portuguese

- Decision Tree - **R^2:** 0.842, **RMSE:** 1.275
- Random Forest - **R^2:** 0.845, **RMSE:**	1.278
- LightGBM - **R^2:** 0.841, **RMSE:** 1.306
- XGBoost - **R^2:** 0.851, **RMSE:** 1.263

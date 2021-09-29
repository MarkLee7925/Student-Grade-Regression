# Student-Grade-Regression

The purpose of this Machine Learning regression project is to predict the final grades of students in Math and Portuguese class based on a variety of features. This was achieved using four different regression models to predict the final grades (out of 20). Each model was cross-validated and tuned to achieve the best possible accuracy with their optimal hyperparameters.

## Dataset:

Both datasets were retrieved from the UCI Machine Learning Repository (link: https://archive.ics.uci.edu/ml/datasets/student+performance). The Math dataset (student-mat.csv) contained 395 samples whereas the Portuguese dataset (student-por.csv) contained 649 samples. Thus, here are 1044 samples each representing a single student.

Additional information about each feature can be found in the student_features.txt file.

## Models:

The following models were implemented in this project:

- Logistic Regresion (LR)
- Decision Tree (DT)
- Random Forest (RF)
- XGBoost (XGB)
- LightGBM (LGB)

## References:

1. https://archive.ics.uci.edu/ml/datasets/student+performance
2. P. Cortez and A. Silva. Using Data Mining to Predict Secondary School Student Performance. In A. Brito and J. Teixeira Eds., Proceedings of 5th FUture BUsiness TEChnology Conference (FUBUTEC 2008) pp. 5-12, Porto, Portugal, April, 2008, EUROSIS, ISBN 978-9077381-39-7.

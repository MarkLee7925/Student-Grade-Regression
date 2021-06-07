# Student-Grade-Regression

The purpose of this Machine Learning regression project is to predict the final grades of students in Math and Portuguese class based on a variety of features. This was achieved using four different regression models to predict the final grades (out of 20). Each model was cross-validated and tuned to achieve the best possible accuracy with their optimal hyperparameters.

## Dataset:

Both datasets were retrieved from the UCI Machine Learning Repository (link: https://archive.ics.uci.edu/ml/datasets/student+performance). The Math dataset (student-mat.csv) contained 395 samples whereas the Portuguese dataset (student-por.csv) contained 649 samples.

Additional information about each feature can be found in the student_features.txt file.

## Results:

The accuracies of each model were measured using R-Squared (R^2) Goodness-of-Fit and Root Mean Squared Error (RMSE) scoring.

### Math

<table border = "1">
  <thead>
    <th colspan = "3">Regression Scores - Math</th>
  </thead>
  <tbody>
    <tr>
      <td><b>Model</b></td>
      <td><b>R^2</b></td>
      <td><b>RMSE</b></td>
    </tr>
    <tr>
      <td><b>Decision Tree (DT)</b></td>
      <td>0.869</td>
      <td>1.483</td>
    </tr>
    <tr>
      <td><b>LightGBM (LGB)</b></td>
      <td>0.883</td>
      <td>1.451</td>
    </tr>
    <tr>
      <td><b>Random Forest (RF)</b></td>
      <td>0.880</td>
      <td>1.451</td>
    </tr>
    <tr>
      <td><b>XGBoost (XGB)</b></td>
      <td>0.904</td>
      <td>1.311</td>
    </tr>
  </tbody>
</table>

### Portuguese

<table border = "1">
  <thead>
    <th colspan = "3">Regression Scores - Portuguese </th>
  </thead>
  <tbody>
    <tr>
      <td><b>Model</b></td>
      <td><b>R^2</b></td>
      <td><b>RMSE</b></td>
    </tr>
    <tr>
      <td><b>Decision Tree (DT)</b></td>
      <td>0.842</td>
      <td>1.275</td>
    </tr>
    <tr>
      <td><b>LightGBM (LGB)</b></td>
      <td>0.841</td>
      <td>1.306</td>
    </tr>
    <tr>
      <td><b>Random Forest (RF)</b></td>
      <td>0.845</td>
      <td>1.278</td>
    </tr>
    <tr>
      <td><b>XGBoost (XGB)</b></td>
      <td>0.851</td>
      <td>1.263</td>
    </tr>
  </tbody>
</table>

## References:

1. https://archive.ics.uci.edu/ml/datasets/student+performance
2. P. Cortez and A. Silva. Using Data Mining to Predict Secondary School Student Performance. In A. Brito and J. Teixeira Eds., Proceedings of 5th FUture BUsiness TEChnology Conference (FUBUTEC 2008) pp. 5-12, Porto, Portugal, April, 2008, EUROSIS, ISBN 978-9077381-39-7.

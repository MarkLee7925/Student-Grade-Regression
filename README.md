# Student-Grade-Regression

The purpose of this Machine Learning regression project is to predict the final grades of students in Math and Portuguese class based on a variety of features. This was achieved using four different regression models to predict the final grades (out of 20). Each model was cross-validated and tuned to achieve the best possible accuracy with their optimal hyperparameters.

## Dataset:

Both datasets were retrieved from the UCI Machine Learning Repository (link: https://archive.ics.uci.edu/ml/datasets/student+performance). The Math dataset (student-mat.csv) contained 395 samples whereas the Portuguese dataset (student-por.csv) contained 649 samples.

Additional information about each feature can be found in the student_features.txt file located in the data folder.

## Results:

The accuracies of each model were measured using the R-Squared (R^2) Goodness-of-Fit and Root Mean Squared Error (RMSE) metrics.

### Math:

<table border = "1">
  <thead>
    <th colspan = "5">Final Regression Scores - Math</th>
  </thead>
  <tbody>
    <tr>
      <td><b>Model</b></td>
      <td colspan='2'><b>R^2</b></td>
      <td colspan='2'><b>RMSE</b></td>
    </tr>
    <tr>
      <td><b></b></td>
      <td><b>CV</b></td>
      <td><b>Val.</b></td>
      <td><b>CV</b></td>
      <td><b>Val.</b></td>
    </tr>
    <tr>
      <td><b>Linear Regression (LR)</b></td>
      <td>0.815</td>
      <td>0.792</td>
      <td>1.833</td>
      <td>2.398</td>
    </tr>
    <tr>
      <td><b>Decision Tree (DT)</b></td>
      <td>0.869</td>
      <td>0.721</td>
      <td>1.483</td>
      <td>2.774</td>
    </tr>
    <tr>
      <td><b>Random Forest (RF)</b></td>
      <td>0.880</td>
      <td>0.732</td>
      <td>1.451</td>
      <td>2.718</td>
    </tr>
    <tr>
      <td><b>XGBoost (XGB)</b></td>
      <td>0.904</td>
      <td>0.740</td>
      <td>1.311</td>
      <td>2.679</td>
    </tr>
    <tr>
      <td><b>LightGBM (LGB)</b></td>
      <td>0.883</td>
      <td>0.711</td>
      <td>1.451</td>
      <td>2.823</td>
    </tr>
  </tbody>
</table>

### Portuguese:

<table border = "1">
  <thead>
    <th colspan = "5">Final Regression Scores - Portuguese </th>
  </thead>
  <tbody>
    <tr>
      <td><b>Model</b></td>
      <td colspan = "2"><b>R^2</b></td>
      <td colspan = "2"><b>RMSE</b></td>
    </tr>
    <tr>
      <td><b></b></td>
      <td><b>CV</b></td>
      <td><b>Val.</b></td>
      <td><b>CV</b></td>
      <td><b>Val.</b></td>
    </tr>
    <tr>
      <td><b>Linear Regression (LR)</b></td>
      <td>0.834</td>
      <td>0.818</td>
      <td>1.334</td>
      <td>1.136</td>
    </tr>
    <tr>
      <td><b>Decision Tree (DT)</b></td>
      <td>0.842</td>
      <td>0.833</td>
      <td>1.275</td>
      <td>1.088</td>
    </tr>
    <tr>
      <td><b>Random Forest (RF)</b></td>
      <td>0.845</td>
      <td>0.843</td>
      <td>1.278</td>
      <td>1.056</td>
    </tr>
    <tr>
      <td><b>XGBoost (XGB)</b></td>
      <td>0.851</td>
      <td>0.833</td>
      <td>1.263</td>
      <td>1.090</td>
    </tr>
    <tr>
      <td><b>LightGBM (LGB)</b></td>
      <td>0.841</td>
      <td>0.840</td>
      <td>1.306</td>
      <td>1.066</td>
    </tr>
  </tbody>
</table>

## References:

1. https://archive.ics.uci.edu/ml/datasets/student+performance
2. P. Cortez and A. Silva. Using Data Mining to Predict Secondary School Student Performance. In A. Brito and J. Teixeira Eds., Proceedings of 5th FUture BUsiness TEChnology Conference (FUBUTEC 2008) pp. 5-12, Porto, Portugal, April, 2008, EUROSIS, ISBN 978-9077381-39-7.

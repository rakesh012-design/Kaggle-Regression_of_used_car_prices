# Used Car Price Prediction (Regression)

This project predicts used car prices using machine learning on the Kaggle dataset.
The workflow is built with scikit-learn Pipelines to ensure clean preprocessing and model training, with hyperparameter tuning using GridSearchCV.

## Key Steps

Preprocessed data using ColumnTransformer for:<br>
Scaling numerical features.<br>
Encoding categorical features.<br>
Implemented XGBRegressor for regression<br>
Evaluated the model using RMSE<br>
Automated preprocessing & model training using Pipelines<br>
Performed hyperparameter tuning with GridSearchCV to optimize the predictions<br>

## RMSE-After Optimization 
![Score](/grid_searchcv.png)

## RMSE-Before Optimization
![Score](/base_acc.png)

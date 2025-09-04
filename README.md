# Used Car Price Prediction (Regression)

This project predicts used car prices using machine learning on the Kaggle dataset.
The workflow is built with scikit-learn Pipelines to ensure clean preprocessing and model training, with hyperparameter tuning using GridSearchCV.

## Key Steps

Preprocessed data using ColumnTransformer for:
Scaling numerical features
Encoding categorical features
Implemented XGBRegressor for regression
Evaluated the model using RMSE
Automated preprocessing & model training using Pipelines
Performed hyperparameter tuning with GridSearchCV to optimize the predictions

## RMSE-After Optimization 
![Score](/grid_searchcv.png)

## RMSE-Before Optimization
![Score](/base_acc.png)

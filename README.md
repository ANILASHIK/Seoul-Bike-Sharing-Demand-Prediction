# Seoul-Bike-Sharing-Demand-Prediction

This repository contains the code and resources for predicting bike rentals in Seoul using various machine learning models. The project involves data preprocessing, feature engineering, model training, hyperparameter tuning, and model evaluation to identify key factors influencing bike rentals.

## Project Overview

The primary objective of this project is to develop a predictive model for bike rentals in Seoul, leveraging historical data on bike rentals along with various weather and seasonal features. The final model aims to help businesses and city planners optimize bike rental operations and improve resource allocation.

## Dataset

The dataset used in this project includes the following features:
- Date
- Rented bike count
- Hour
- Temperature (°C)
- Humidity (%)
- Wind speed (m/s)
- Visibility (10m)
- Dew point temperature (°C)
- Seasons (Autumn, Spring, Summer, Winter)
- Holiday (Yes/No)
- Functioning day (Yes/No)


## Key Steps

### Data Preprocessing and Feature Engineering

1. **Missing Values**: Identified and handled missing values.
2. **Feature Manipulation**: Selected and engineered features relevant to bike rental prediction.
3. **Transformation**: Applied log transformation to the target variable (rented bike count) to handle skewness.

### Model Training and Evaluation

1. **Model Selection**: Trained multiple models including Linear Regression, Lasso Regression, Random Forest, and XGBoost Regressor.
2. **Evaluation**: Assessed model performance using Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared metrics.
3. **Cross-Validation**: Performed cross-validation and hyperparameter tuning to optimize model performance.

### Feature Importance

Used python libraries to identify the most significant features influencing bike rentals, such as seasonality, dew point temperature, and overall temperature.

## Final Model

The XGBoost Regressor was chosen as the final model due to its superior performance:
- **MSE**: 0.022244
- **RMSE**: 0.149143
- **R-squared**: 0.911024

## Conclusion

This project successfully developed a robust predictive model for bike rentals in Seoul. The insights gained can help businesses and city planners optimize operations and improve customer satisfaction.

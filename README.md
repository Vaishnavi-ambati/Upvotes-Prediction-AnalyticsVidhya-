# Upvotes-Prediction-AnalyticsVidhya-
Crowd sourced online content platforms have a constant need to identify the best content in time to appropriately promote and thereby improve the engagement at the website. This challenge involves a similar problem of predicting the up vote count for a queries posted and identify the parameters that affect it the most.   
1. In the first notebook file following tasks are performed:
    * Understanding the data
    * Finding outliers 
    * Finding required columns
    * Null values check
    * Skweness check
    * Handling categorical variables
    * Trained the model using different Regression algorithms
    * Used GradientBoostingRegressor and RandomForestRegressor to predict the values for Test data.
    * Reduced skewness
    * Used RandomForestRegressor after reducing skewness to predict the values for Test data.
    * Observed the correlation between the independent columns and independent columns with target column.
   
2. In the first notebook file following tasks are performed:
   PART 1:
    * Dropped ['Tag','ID','Username'] columns because of low correlation value with the target variable.
    * Applied PolynomialFeatures of degree 3.
    * Traind the models with Linear regression.
    * Also used Ensemble learning.
   PART 2:
    * Dropped ['Tag','ID','Username'] columns because of low correlation value with the target variable.
    * Applied PolynomialFeatures of degree 3.
    * Used StandardScaler to standardize the values.
    * Traind the models with Linear regression.
    * Also used Ensemble learning.
  
    

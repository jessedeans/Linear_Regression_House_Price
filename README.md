# Predicting Home Prices Using Linear Regression
This repository contains a [notebook](https://github.com/jessedeans/Linear_Regression_House_Price/blob/master/Linear%20Regression%20Pipeline%20for%20House%20Price%20Prediction.ipynb) and datset used to build a pipeline of functions to run scikit-learn's linear regression model to predict a home's sale price.

The pipeline contains three main functions to quickly iterate on different models.
- `transform_features` function is for feature engineering
- `select_features` function is used to select features 
- `train_and_test` function trains and tests the model using linear regression and returns the RMSE error metric


I am going to work with housing data for the city of Ames, Iowa, in the United States from 2006 to 2010. The data set contains 2930 observations and a 80 explanatory variables (23 nominal, 23 ordinal, 14 discrete, and 20 continuous) involved in assessing home values. For information on why the data was collected go [here](https://doi.org/10.1080/10691898.2011.11889627). More information about the different columns in the data can be found [here](https://s3.amazonaws.com/dq-content/307/data_description.txt).


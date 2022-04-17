# Apparal Production Quantities Forecasting

The goal of this study is to produce a production plan for a apparal manufacturer. As the problem suggests, this is a supervised learning problem as we will likely have labeled datasets for us to learn patterns and forecast. This is also likely going to be a regression problem. The Y variable is going to be a continuous variable and not a categorical variable. We have been given the definition of a few X variables but we have not been specified a Y variable.

## Summary

In order to forecast to quantities, we have run a multinomial OLS regression, random forest model and a gradient boosting model (GBM). We have done data cleaning, outlier treatment, visualizing, feature engineering, scaling in order to create an appropriate dataset for model training. We used root mean squared error (RMSE) of the test set in order to decide the best model. The GBM model provides the least RMSE thus proving to be the most appropriate model. 

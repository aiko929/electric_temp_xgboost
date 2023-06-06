# Predicting Electric Vehicle Temperature

We are using data from the university in paderborn (https://www.kaggle.com/datasets/wkirgsn/electric-motor-temperature). 
We fit a XGBoost regressor to predict the temperature of the permanent magnet in °C.
Although we didnt tune any hyperparameters, the prediction performance is quite good.

## Results:

The MSE was: 6.932819018488115

![image](https://github.com/aiko929/electric_temp_xgboost/assets/26790700/8c8743eb-0801-47e8-9028-dd6d6bf12d06)
*Showing the first 10 prediction vs real labels*

### Feature Selection:

At the end we looked at the feature importances of the trained model. We found a highly correlated column.

![image](https://github.com/aiko929/electric_temp_xgboost/assets/26790700/7828de9e-01c0-405a-a5b9-a3ffdfb10703)

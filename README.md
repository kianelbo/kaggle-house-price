# kaggle-house-price
My solution for [Kaggle's "House Prices: Advanced Regression Techniques"](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)  
Best submitted score: **0.11851** (Top 5%)

## Preprocessing Steps
* Detecting skew and applying log transform
* Anylizing the data and detecting correlated and redundant features
* Detecting outliers and removing them
* Filling  missing values
* Feature engineering and encoding
## Models
_The voting regressor is chosen as the final model_  
Tested models:
* [Gradient Boosting Regressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.HistGradientBoostingRegressor.html)
* [Ridge CV](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.RidgeCV.html)
* [ElasticNet CV](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.ElasticNetCV.html)
* [Lasso CV](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LassoCV.html)
* [SVR](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVR.html)
* [Random Forest](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html)
* [Multi-layer Perceptron](https://scikit-learn.org/stable/modules/generated/sklearn.neural_network.MLPRegressor.html)
* [Voting Regressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.VotingRegressor.html) of Ridge, ElasticNet and GBR  

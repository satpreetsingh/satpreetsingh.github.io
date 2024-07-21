## Checklist/Gotchas for Applied Machine Learning Projects

* Data leakage: Is prediction accuracy >99%? You probably have data-leakage! 
Check if the training data is leaking into the test data (i.e. train-test split is broken) 
Alternatively, check if the target variable is included in the features. (This would show up in training accuracy of >99% too)

* Time-series: Train-test split should be such that test data is later in time compared to training data.

* Random Forest Feature Importances:
** Noise floor 
** Correlated input features

* Interpreting regression coefficients


* Using test accuracy to make decisions

* 
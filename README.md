# Code_examples

## 1. House Prices
from Kaggle.com https://www.kaggle.com/c/house-prices-advanced-regression-techniques

### 1.1 Linear models: Ridge and Lasso
- Parameter selection - with the cross validation (number of folds = 3).
The best model choice and overfitting control - with a delayed sample.
- Metric - Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price.
- Encoding categorical features with one-hot encoding.
- Numeric features will be scaled, as we're going to use an l1 and l2 regularization.
- Handling missing data - a zero for numeric features, a new label for categorical ones.

### 1.2 Random Forest and Gradient Boosting

- Parameter selection - with GridSearchCV and RandomizedSearchCV.
- The best model choice - with a delayed sample.
- Metric - Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price.
- Encoding categorical features with the special method for decision trees.
Handling missing data - a median for numeric features, a new label for categorical ones.

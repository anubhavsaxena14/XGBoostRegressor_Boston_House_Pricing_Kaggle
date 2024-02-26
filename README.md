# XGBoostRegressor_Boston_House_Pricing_Kaggle

1. Boston House Pricing:

Each record in the database describes a Boston suburb or town. The data was drawn from the Boston Standard Metropolitan Statistical Area (SMSA) in 1970. The attributes are deﬁned as follows (taken from the UCI Machine Learning Repository1): CRIM: per capita crime rate by town

ZN: proportion of residential land zoned for lots over 25,000 sq.ft.

INDUS: proportion of non-retail business acres per town

CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)

NOX: nitric oxides concentration (parts per 10 million)

1https://archive.ics.uci.edu/ml/datasets/Housing
123
20.2. Load the Dataset 124

RM: average number of rooms per dwelling

AGE: proportion of owner-occupied units built prior to 1940

DIS: weighted distances to ﬁve Boston employment centers

RAD: index of accessibility to radial highways

TAX: full-value property-tax rate per $10,000

PTRATIO: pupil-teacher ratio by town 12. B: 1000(Bk−0.63)2 where Bk is the proportion of blacks by town 13.

LSTAT: % lower status of the population

MEDV: Median value of owner-occupied homes in $1000s

We can see that the input attributes have a mixture of units.

2. XGBoostRegressor:

It is an implementation of the XGBoost algorithm specifically designed for regression tasks in machine learning.

It's an ensemble learning method that combines the predictions of multiple decision trees to improve accuracy and generalization. XGBoost is known for its efficiency, speed, and performance, making it a popular choice for regression problems.

It utilizes gradient boosting, where weak learners (decision trees) are built sequentially, each correcting the errors of the previous one. Parameters like learning rate, number of trees, and tree-specific settings can be tuned to optimize performance for a given regression problem.

## Goal of the Project

In this project, we will evaluate the performance and predictive power of a model that has been trained and tested on data collected from homes in the suburbs of Boston,
Massachusetts. A model trained on this data that is seen as a good fit could then be used to make certain predictions about a home — in particular, its monetary value.

## About the Dataset:

* The Boston housing data was collected in 1978 and each of the 506 entries represents aggregated data about 14 features for homes from various suburbs in Boston,
  Massachusetts.
* First we have to explore the dataset and get to know about each data point and what they are related to.

### Below are the 14 features that we are going to consider from the dataset:
We can see that the input attributes have a mixture of units.

* ZN: proportion of residential land zoned for lots over 25,000 sq. ft.
* INDUS: proportion of non-retail business acres per town
* CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
* NOX: nitric oxides concentration (parts per 10 million)
* RM: average number of rooms per dwelling
* AGE: proportion of owner-occupied units built prior to 1940
* DIS: weighted distances to ﬁve Boston employment centers
* RAD: index of accessibility to radial highways
* TAX: full-value property-tax rate per $10,000
* PTRATIO: pupil-teacher ratio by town 12. B: 1000(Bk−0.63)2 where Bk is the proportion of blacks by town 13. LSTAT: % lower status of the population
* MEDV: Median value of owner-occupied homes in $1000s

### Note:
* TARGET -- The target variable is also known as an independent variable or label.
* FEATURES -- Input features are also known as dependent variables.

In our dataset,  the features, 'RM', 'LSTAT', and 'PTRATIO', give us quantitative information about each data point. The target variable, 'MEDV', will be the variable we seek to predict. These are stored in features and prices, respectively.

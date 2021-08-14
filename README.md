# Multiple-linear-regression

**Goal**

To build a multiple linear regression model to predict mileage of the car based on various attributes of the car.

**Data source**

This dataset contains various attributes of cars that were produced in US,Europe and japan.
It has 9 attributes and 398 records. I took this dataset from UCI machine learning repository.

The link to the dataset:
[https://archive.ics.uci.edu/ml/datasets/auto+mpg](https://archive.ics.uci.edu/ml/datasets/auto+mpg)

**Description**

This dataset contains eight independent variables and one dependent variable. predictor variables are different attributes of car.
Our target variable is mpg(miles per gallon). we need to predict mileage of the car based on various attributes.

I one hot encoded categorical variable to turn them into numerical variable.
I used scikit learn library to build the model.
I developed a regression model that predicts the target variable with 79% accuracy.

*Regression line*

![](https://github.com/thennarasur/Multiple-linear-regression/blob/main/best%20fit%20line.png)

Accuracy   = 0.79    
RMSE value = 2.89    
R2 Score   = 0.79

I use RMSE value and R2 score as evaluation metrics. Both the values indicate this is a good fit data.

**Conclusion**

Thus we have developed a multiple linear regression model that predicts the mileage(mpg) of the car with 79% accuracy.
we can improve the models accuracy with feature engineering. once we have necessary accuracy we can deploy the model.

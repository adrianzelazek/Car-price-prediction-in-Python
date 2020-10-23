# Prediction of car price using Linear Regression in Python
### Author: Adrian Żelazek

In this project was used dataset concerning particular features of cars as well as their prices. The dataset contains 205 observations as well as 26 variables. The target of the project is to predict car price (target variable) using Linear Regression models based on the available set of their features for instance: engine size, fuel type, door number and so on. The project includes Exploratory Data Analysis, grouping, visualization, splitting the training and testing data, predictions as well as model evaluation. Furthermore, results of training and test datasets were compared with each other to exclude possible of overfitting.

This project was developed for the purpose of practicing machine learning technology
and data mining in Python. Predictions were exported to Excel.

##### It is preferred to run/view the project via Jupyter Notebook (.ipynb) than via a browser (HTML). To see the HTML version you first need to download the HTML file and then run it in your browser.

### Programming language and platform
* Python - version : 3.7.4
* Jupyter Notebook

### Libraries
* Scikit-learn - version: 0.22.2.post1
* Pandas - version: 0.25.1
* NumPy - version: 1.16.5
* Matplotlib - version: 3.1.2
* Seaborn - version: 0.9.0

### Algorithms
* Linear Regression
* Pearson correlation coefficient
* RFE (Recursive Feature Elimination)
* LASSO regularization
* Dummy coding and binary coding of categorical variables

### Methods of model evaluation
* MAE - Mean Absolute Error - the mean of the absolute value of the errors
(average error)
* MSE - Mean Squared Error - the mean of the squared errors
* RMSE - Root Mean Squared Error - the square root of the mean of the squared
errors
* R-squared (Coefficient of determination) represents the coefficient of how well
the values fit compared to the original values. The value from 0 to 1
interpreted as percentages. The higher the value is, the better the model is.

### Results
* **Model 1** with data selection using Pearson correlation presents the best
results: MAE: 2112.34 MSE: 11106289.36 RMSE: 3332.61 R-squared: 0.83
Rest models present the following results:
* **Model 2:** MAE: 2528.14, MSE: 14208288.23, RMSE: 3769.39, R-squared: 0.66. Model
2 could be overfit, results on training and test datasets differ significantly
from each other.
* **Model 3:** MAE: 2465.99, MSE: 11528276.95, RMSE: 3395.33, R-squared: 0.85


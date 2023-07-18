# latte-cls1

https://pypi.org/project/Latte-cls1/

for python installation  "pip install Latte-cls1"

Project description

This is a simple package for data classification

#Contents/functions
# Linear Regression

The linear(filename, cl1, cl2, predict_value) function performs linear regression on a given dataset and predicts the value for a given input. It takes the following parameters: - filename: The name of the CSV file containing the dataset. - cl1: The column index of the independent variable (x). - cl2: The column index of the dependent variable (y). - predict_value: The input value for which the prediction is to be made.

The function calculates the slope and intercept of the regression line using the least squares method. It then plots the data points, regression line, and prediction. The function returns the slope, intercept, and prediction as results.

# Logistic Regression

The logistic(filename, cl1, cl2, predict_value) function performs logistic regression on a given dataset and predicts the probability and class for a given input. It takes the following parameters: - filename: The name of the CSV file containing the dataset. - cl1: The column index of the independent variable (x). - cl2: The column index of the dependent variable (y). - predict_value: The input value for which the prediction is to be made.

The function uses scikit-learn’s LogisticRegression class to fit the logistic regression model and predict the probability and class for the input. It plots the data points, logistic regression curve, and prediction. The function returns the probability and prediction as results.

# Decision Tree Classification

The dtree(filename, cl1, cl2, predict_value) function performs decision tree classification on a given dataset and predicts the class for a given input. It takes the following parameters: - filename: The name of the CSV file containing the dataset. - cl1: The column index of the independent variable (x). - cl2: The column index of the dependent variable (y). - predict_value: The input value for which the prediction is to be made.

The function uses scikit-learn’s DecisionTreeClassifier class to fit the decision tree model and predict the class for the input. It plots the data points, decision tree boundary, and prediction. The function returns the prediction as a result.

# Matrix Operations

The matrix_ml(matrix1, matrix2) function performs matrix multiplication on two given matrices. It takes the following parameters: - matrix1: The first matrix. - matrix2: The second matrix.

The function uses numpy’s dot function to perform matrix multiplication and returns the result.

The matrix_add(matrix1, matrix2) function performs matrix addition on two given matrices. It takes the following parameters: - matrix1: The first matrix. - matrix2: The second matrix.

The function uses numpy’s add function to perform matrix addition and returns the result.

Change Log
0.0.3 (15/07/2023)

-First Release






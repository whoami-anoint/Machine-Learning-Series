# Unit 1 : 
### Chapter 2 : Regression

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Share on Twitter](https://img.shields.io/badge/-Share%20on%20Twitter-blue?logo=twitter&style=flat-square)](https://twitter.com/intent/tweet?text=https%3A%2F%2Fgithub.com%2Fwhoami-anoint%2FMachine-Learning-Series)
[![GitHub discussions](https://img.shields.io/github/discussions/whoami-anoint/Machine-Learning-Series)](https://github.com/whoami-anoint/Machine-Learning-Series/discussions)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/whoami-anoint/Machine-Learning-Series)](https://github.com/whoami-anoint/Machine-Learning-Series/pulls)
[![Code of Conduct](https://img.shields.io/badge/Code%20of%20Conduct-Contributor%20Covenant-blue.svg)](CODE_OF_CONDUCT.md)

Regression is a statistical method that is used to predict a continuous dependent variable from a set of independent variables.

### 1. **Linear Regression:**

* This is the most common type of regression, and it assumes that the relationship between the independent and dependent variables is linear.
* This means that the dependent variable can be represented as a linear combination of the independent variables.
* The linear regression model is typically represented by the following equation:
    * **y = mx + b**
    * where y is the dependent variable, m is the slope of the line, b is the y-intercept, and x is the independent variable.
* The linear regression model can be fit to the data using least squares.
* Least squares minimizes the sum of the squared residuals, which are the differences between the predicted values and the actual values.

### 2. **Logistic Regression:**

* This type of regression is used when the dependent variable is categorical.
* It assumes that the relationship between the independent and dependent variables is logistic.
* This means that the probability of the dependent variable taking on a particular value can be represented as a logistic function.
* The logistic regression model is typically represented by the following equation:
    * **p(y = 1 | x) = 1 / (1 + e^(-(mx + b)))**
    * where p(y = 1 | x) is the probability of the dependent variable taking on the value of 1, m is the slope of the line, b is the y-intercept, and x is the independent variable.
* The logistic regression model can be fit to the data using maximum likelihood estimation.
* Maximum likelihood estimation maximizes the likelihood of the data being generated by the model.

### 3. **Polynomial Regression:**

* This type of regression is used when the relationship between the independent and dependent variables is not linear.
* It fits a polynomial curve to the data.
* The polynomial regression model is typically represented by the following equation:
    * **y = ax^2 + bx + c**
    * where y is the dependent variable, a, b, and c are the coefficients of the polynomial, and x is the independent variable.
* The polynomial regression model can be fit to the data using least squares.

### 4. **Decision Tree Regression:**

* This type of regression uses a decision tree to predict the dependent variable.
* The decision tree is trained on a set of labeled data, and it learns to map the independent variables to the dependent variable.
* The decision tree is made up of a series of nodes, and each node represents a decision.
* The decision tree is traversed from the root node to a leaf node, and the predicted value is the value associated with the leaf node.

### 5. **Random Forest Regression:**

* This type of regression is an ensemble method that combines multiple decision trees.
* It is often more accurate than a single decision tree.
* The random forest regression model is created by training multiple decision trees on different subsets of the data.
* The predictions of the individual decision trees are then combined to get the final prediction.

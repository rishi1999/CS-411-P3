# README for Problem \#1: Linear Regression

## Part 1
### normalization_factors(xss)
Computes mean and standard deviation of input data `xss`.

### normalized_input(xss)
Returns normalized version of input data `xss`.

### read_input_file(filename)
Processes file `filename` and returns lists of normalized training input (x) and output (y) values. 
This function processes a file with any number of input variables.  

### linear_regression(x, y)
Performs gradient descent and returns weights (w) and bias (b) for the linear regression model.

### read_test_file(test_file, stats)
Processes file `test_file` and returns the list of normalized testing input (t) values.


## Part 2
### normalization_factor(xs)
Computes mean and standard deviation of input data `xs`.

### normalized_input(xs)
Returns normalized version of input data `xs`.

### read_input_file(filename)
Processes file `filename` and returns lists of normalized training input (x) and output (y) values.
This function only processes a file with a single input variable.

### linear_regression(x, y)
Performs gradient descent and returns weights (a) and bias (b) for the linear regression model.

### read_test_file(test_file, stats)
Processes file `test_file` and returns the list of normalized testing input (t) values.

### plot(x, y, t, a, b)
Plots the unnormalized training data points, trained linear function, and predicted output values.
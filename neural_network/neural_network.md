# README for Problem \#2: Neural Network

### normalization_factors(xss)
Returns the mean and standard deviation for each feature in dataset `xss`.

### normalized_input(xss, stats)
Returns a transformed version of dataset `xss` with mean 0 and standard deviation 1.

### n_factors_test()
Unit test for normalization factor code.

### read_train(filename)
Read training data from file `filename` and normalize the values.

### read_test(filename, stats)
Read testing data from file `filename` and normalize the values using statistics `stats` from training data.

### sigmoid(xs)
Applies sigmoid activation function to every element in list `xs`.

### sigmoid_prime(x)
Applies derivative of sigmoid activation function to `x`.

### softmax(xs)
Applies softmax activation function to every element in list `xs`.

### sel(network_output, label)
Calculates squared error loss with final layer `network_output` and label `label`.

### softmax_sel_prime(k, layer, label)
Calculates derivative of squared error loss with respect to node `k` in final layer `layer` before activation function has been applied with label `label`.

### activation_test()
Unit test for activation function.

### forward(layer_sizes, activation, final_act, weights, x)
Performs forward propagation.

### forward_test()
Unit test for forward propagation (forward pass).

### classify(class_idx_to_name, layer_sizes, activation, final_act, weights, x)
Classifies input `x`.

### backward(layer_sizes, activation_prime, final_act_loss_prime, old_weights, weights, layers, layers_pre_act, step, y)
Performs backpropagation (backward pass). One gradient descent step happens during this function's execution.

### train_one_epoch(weights, layer_sizes, activation, activation_prime, final_act, final_act_loss_prime, batch_size, step, train_data)
Trains neural network for one epoch.

### run_tests()
Runs all unit tests.
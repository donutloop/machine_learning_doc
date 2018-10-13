# Neural networks

![neuron](images/neuron.jpg)

## Legend
* Input wries == Dendrite 
* Output wire == Axon

## Neuron model: Logistic unit

![machine_neuron](images/machine_neuron.png)

## Neural Network

![machine_neural_network.png](images/machine_neural_network.png)

![machine_neural_network.png](images/machine_neural_network_equation.png)

if network has sj units in layer j, sj + 1 units in layer j + 1, 0j then will be of diemension sj+1 * (sj +1). 

### Housing Price Prediction Example 

![neuron_example](images/neuron_example.png)

### Other Neural Network Architectures

![other_neural_network_architectures](images/other_neural_network_architectures.png)


### Binary Neural Network (AND)

![binary_neural_network](images/binary_neural_network.png)

### Binary Neural Network (XNOR)

![all_binary_operations_comb](images/all_binary_operations_comb.png)

### Neural network logistic regression cost function

![neural_network_logistic_regression_cost_function](images/neural_network_logistic_regression_cost_function.png)

### Back propagation 

![backpropagation](images/backprogagation.png)

### Gradient decent

![gd](images/gd.png))

### Training a neural network 

Pick a network architecture (connecctivity pattern between neurons)

* No. of input uints: Dimension of features x
* No. of output uints: number of classes 
* Reasonable default: 1 hidden layer, or if > 1 hidden layer, have same no. of hidden units in every layer (usually the more the better)

1. Randomly initialize weights
2. Implement forward propagation to get h(theta)(xte) for any xte
3. Implement code to compute cost j(theta)
4. Implement back propagagtion to compute partial derivatives
5. Perform forward propagation and back propagation using (xte and yte)
6. Get activations a(l) and delta(l) terms for l =2.....,L
7. Use gradient checking to compare partial derivatives computed using back propagation vs using numerical estimate of gradient decent of j(theta) then disable gradient checking code 
8. Use gradient descent or advanced optimization method with back propagation to try to minimize j(theta) as a function of parameters (theta)

### Neural network computing graph

![compunting_neural_network](images/compunting_neural_network.png)

## Activation functions

![activation_functions](images/activation_functions.png)

## Derivatives of activation functions

![activation_functions](images/derivatives_of_activation_functions.png) 

## Gradient descent for Neural Networks

![Gradient descent for Neural Networks](images/gradient_descent_for_neural_networks.png)

# Matrix dimensions 

![neural_network_dimension](images/neural_network_dimension.png)

# Building blocks of Deep Neural Networks

![building_blocks_of_deep_neural_networks](images/building_blocks_of_deep_neural_networks.png)

## Normalizing inputs

![normalizing_inputs](images/normalizing_inputs.png)

### Why normalzing inputs 

![why_normlizing](images/why_normlizing.jpg)

### Batch normalizing 

![Normalizing activations in a network](images/normalizing_activations_in_a_network.png)
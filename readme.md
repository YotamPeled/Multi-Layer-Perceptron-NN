Multi-Layer Perceptron (MLP) Implementation Using Numpy
Overview
In this exercise, we've developed a basic three-layer Multi-Layer Perceptron (MLP), a type of neural network, using only Numpy for numerical computation. This implementation is aimed at understanding the fundamentals of neural network operations, including forward pass and backpropagation, in a multi-class classification context.

Objectives
To implement a neural network from scratch using Numpy.
To understand the architecture of a simple MLP, including input, hidden, and output layers.
To grasp the concept and mathematics behind the forward pass and backpropagation algorithms.
To apply the neural network for multi-class classification problems.
Implementation Details
Network Architecture: The MLP consists of an input layer, one hidden layer, and an output layer. Each layer is fully connected to the next one.
Activation Functions: We use the ReLU (Rectified Linear Unit) activation function for the hidden layers to introduce non-linearity and the softmax function for the output layer to handle multi-class classification.
Loss Function: The Cross-Entropy loss function is employed to evaluate the performance of the model in predicting the class labels.
Backpropagation: We've implemented the backpropagation algorithm to calculate gradients of the loss function with respect to the weights and biases. This is crucial for updating the parameters of the network during training.
Optimization: Gradient descent is used as the optimization technique to minimize the loss by updating the network's weights and biases based on the calculated gradients.
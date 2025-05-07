Project Description

This project implements a neural network from scratch to classify the Iris dataset. The Iris dataset contains 150 samples of iris flowers, with 4 features (sepal length, sepal width, petal length, and petal width) used to classify the flowers into 3 species: Setosa, Versicolor, and Virginica.

Key Objectives:
To understand the core principles of neural networks by building one from scratch.
To implement forward propagation, backpropagation, and gradient descent without relying on high-level libraries.
To evaluate the performance of the neural network on the Iris dataset.
The dataset is split into training and testing sets to evaluate the network's performance.

Model Implementation

The neural network consists of the following components:

Input Layer: 4 input features (sepal length, sepal width, petal length, and petal width).
Hidden Layer(s): One hidden layer with ReLU activation function.
Output Layer: 3 output neurons, each representing one class (Setosa, Versicolor, Virginica) with a softmax activation to produce probabilities.
The model is trained using gradient descent to minimize the cross-entropy loss.

Steps Implemented:
Forward Propagation: Calculating the activations at each layer.
Loss Function: Cross-entropy loss is used to measure the difference between the predicted and actual outputs.
Backpropagation: Gradient computation and weight update using the chain rule.
Training: The model is trained iteratively using the training dataset.

# SGD-and-CNN-implementationation
This project aims to implement a flexible Neural Network framework in Python. Training a specific Convolutional Neural Network (CNN) architecture on the MNIST dataset

This project aims to implement a flexible Neural Network framework in Python. The provided classes allow for the creation of custom neural network architectures with various activation functions and loss functions. Additionally, it includes functionality for training these networks using Stochastic Gradient Descent (SGD) on different datasets.

The key features include:
1. Definition of a Neural Network class capable of handling custom architectures composed of different layers, activation functions, and loss functions.
2. Creation and training of various network configurations on different datasets:
   - Linear regression network with one output neuron and linear activation function.
   - Multilayer networks with different architectures and activation functions trained on the california dataset for regression tasks.
   - Multilayer networks trained on the MNIST dataset for classification tasks using both mean squared loss and softmax with cross-entropy loss.
3. Implementation of convolutional layers with forward and backward passes, as well as flattening operations.
4. Training a specific Convolutional Neural Network (CNN) architecture on the MNIST dataset:
   - Layer 1: Convolutional layer with 16 output channels, followed by flattening and tanh activation.
   - Layer 2: Fully connected layer with 10 output neurons and linear activation.
   - Utilization of softmax cross-entropy loss for classification.

This project serves as a comprehensive framework for experimenting with neural network architectures and training them on different datasets, providing a solid foundation for further research and experimentation in machine learning and deep learning.


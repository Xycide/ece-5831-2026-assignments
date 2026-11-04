# ece-55831-2026-assignments-A_02

Author: Errick Lisk
Class: ECE 55831
Date - 10/20/2026

This repo contains the files required for the assignments in ECE 55831 that are authored by Errick Lisk.

### A02 [Assignment 02]
The numpy-tutorials.ipynb is written in Python and is an executable format of the Python Numpy tutorials found on https://cs231n.github.io/python-numpy-tutorial/

* numpy-tutorials.ipynb

### A03 [Assignment 03]
Contains 3 files to create, test and display 5 logic gates (OR, AND, NAND, NOR, XOR) using numpy.

* logic_gate.py
* module3.py
* module3.ipynb

### A04 [Assignment 04]
Implements and tests a Multilayer Perceptron with Sigmoid and ReLU activation functions, demonstrating forward propagation using random and manual weights and biases.

* multilayer_perceptron.py
* module4.py
* module4.ipynb

### A05 [Assignment 05]
Contains two problems which use trained neural networks to recognize hand gestures and handwritten digits.

* P_01/rock-paper-scissors.ipynb - Loads a model trained using Teachable Machine and tests Rock, Paper, and Scissors images, displaying the predicted classes and confidence scores
* P_01/model - Contains the trained gesture recognition model and class labels
* P_01/images - Contains the three gesture test images
* P_02/mnist.ipynb - Implements the Mnist class, trains and evaluates a neural network on MNIST, saves and reloads the model, and tests 50 handwritten digit images
* P_02/mnist_model - Contains the saved MNIST model
* P_02/images - Contains five handwritten images for each digit from 0 through 9


### A06 [Assignment 06]
Implements a TwoLayerNet trained with numerical gradients on the Iris and MNIST datasets. The saved notebook shows training, model loading, and test results: 96.67% accuracy on Iris and 87.86% on MNIST.

* module6.ipynb - Implements, trains, saves, reloads, and tests both networks
* lisk_iris_nn_model.pkl - Trained Iris model
* lisk_mnist_nn_model.pkl - Trained MNIST model
* data/iris/iris.data - Iris dataset
* data/mnist.npz - MNIST dataset
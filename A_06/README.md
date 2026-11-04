# Assignment 06: Numerical Gradient

This project implements a TwoLayerNet trained with numerical gradients for Iris and MNIST classification. The network has one hidden layer and uses centered finite differences to calculate gradients.

## Files

- `module6.ipynb` — training code and saved test results
- `lisk_iris_nn_model.pkl` — trained Iris model
- `lisk_mnist_nn_model.pkl` — trained MNIST model
- `data/iris/iris.data` — Iris dataset
- `data/mnist.npz` — MNIST training and test datasets

## Results

The Iris model correctly classified 29 of 30 test samples, achieving 96.67% accuracy. The MNIST model achieved 87.86% accuracy on the full test set and correctly classified 19 of the 20 displayed samples.
# Assignment 07: Neural Network with Backpropagation

Author: Errick Lisk  
Class: ECE 55831  
Date: 11/10/2026

Implements `TwoLayerNetBackprop` and compares it with Keras using the MNIST dataset.
The NumPy model implements forward propagation and backpropagation, while Keras handles the gradient calculations automatically. Both models use the same network structure and training settings, with plots and sample predictions showing the results.

## Files

- `module7.ipynb` — implementation, training, testing, and results for both models

## Results

Both models were trained for 10 epochs.

| Approach | Training accuracy | Test accuracy |
| --- | ---: | ---: |
| NumPy backpropagation | 98.30% | 97.21% |
| Keras | 98.31% | 97.25% |

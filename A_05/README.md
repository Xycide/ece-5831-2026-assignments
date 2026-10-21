# ece-5831-2026-assignments
# A_05

Author: Errick Lisk
Class: ECE 55831
Date - 10/20/2026

This folder contains the files required for the 5th assignment in ECE 5831.

### P_01/rock-paper-scissors.ippynb
Jupyter notebook which loads a Rock, Paper, Scissors model trained using the webcam option in Teachable Machine and tests it with stock images of each gesture. The notebook demonstrates:
* Loading the trained Keras model and class labels
* Using CustomDepthwiseConv2D to remove the unsupported groups parameter when loading the model
* Resizing the test images to 224 x 224 pixels and normalizing the pixel values between -1 and 1
* Predicting each gesture and printing the predicted class and confidence score
* Discussing the differences between webcam results and the stock image test results

### P_01/model
Contains keras_model.h5, the trained Teachable Machine model, and labels.txt which lists the rock, paper and scissors classes.

### P_01/images
Contains the rock_test.png, paper_test.png, and scissors_test.png used tot est gestures recognition model.

### P_02/mnist.ipynb
Jupyter notebook which contains the Mnist class with 5 functions to create or load a neural network, train it on the MNIST dataset, and test handwritten digit images. The network has a flatten layer, a hidden dense layer that has 128 neurons and ReLU activation, and an output dense layer with 10 neurons and softmax activation.

* __init__(self, model_path=None) - Loads a saved model or creates and compiles a new neural network
* train(self, images, labels, epochs=5) - Trains the network using normalized images and integer digit labels
* predict(self, input_data) - Performs forward propagation and returns the class scores
* load_image(self, image_path, invert=False) - Checks that an image is 28 x 28 pixels, converts it to grayscale, optionally inverts it, and normalizes it for prediction
* test_image(self, image_path, invert=False) - Displays the image, compares the predicted digit with the digit in its filename, and prints a success or failure message

The notebook demonstrates:
* Loading and normalizing the MNIST training and testing datasets
* Training the network for 5 epochs and evaluating its MNIST test loss and accuracy
* Saving and reloading the trained model
* Testing individual handwritten digit images
* Testing all 50 handwritten images and reporting the successes, failures, and overall accuracy

### P_02/mnist_model
Contains model.keras, the saved neural network trained on the MNIST dataset.

### P_02/images
Contains 50 handwritten digit images, with 5 images for each digit from 0 through 9. Files are named using the digit and sample number, such as 2_1.png. The notebook inverts the dark digits on light backgrounds before testing them.

# ece-5831-2026-assignments
# A_08

This folder contains the files required for the 8th assignment in ECE 5831.

### [Two_layer_net.ipynb](Two_layer_net.ipynb)

Contains the `TwoLayerNetKeras` class to train and test a two-layer neural network on handwritten digits. The notebook shows the loss and accuracy over 10 epochs and the output for 10 test images. The network reached 97.41% test accuracy with a test loss of 0.0870.

### [CNN_cat_dog.ipynb](CNN_cat_dog.ipynb)

Jupyter notebook which uses a convolutional neural network to classify cat and dog images. It reads `data_from_kaggle.zip` from the assignment folder. A fresh clone needs a copy of this file from Canvas.

* Prepares the training, validation, and test images
* Trains the CNN for 10 epochs
* Tests the CNN on the validation images (85.04% accuracy, 0.3470 loss) and test images (86.04% accuracy, 0.3339 loss)
* Displays 10 images with the actual and predicted labels

Both notebooks use TensorFlow, NumPy, and Matplotlib.

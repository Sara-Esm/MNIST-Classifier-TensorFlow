# MNIST Classifier with TensorFlow

Implementing a machine learning model using TensorFlow and Keras to classify handwritten digits from the MNIST dataset.

## Overview

The MNIST Classifier with TensorFlow is a straightforward neural network model trained to recognize and classify handwritten digits from the MNIST dataset. Leveraging TensorFlow, this project serves as a practical example of creating, compiling, and training a basic deep-learning model for image classification.

## Load and Preprocess Data:

Loads the MNIST dataset, discards the test set, and normalizes pixel values to facilitate effective training.

## Define Callback:

A custom callback, myCallback, is implemented to monitor training and halt the process when accuracy surpasses 99%.

## Train the Model

The model architecture includes a flattened input layer, a dense hidden layer with ReLU activation, and an output layer with softmax activation. The model is compiled with the Adam optimizer and sparse categorical crossentropy loss. Training occurs for 9 epochs, with the custom callback ensuring early stopping if the accuracy threshold is met.

## License

This project is licensed under the [MIT License](LICENSE).

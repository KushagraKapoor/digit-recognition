# digit-recognition
MNIST DIGIT RECOGNITION USING NEURAL NETWORK


This is a basic neural network designed to recognize a number from a given image based on the MNIST digit dataset
reference:https://www.youtube.com/watch?v=w8yWXqWQYmU


The project involves a from scratCh implementation without importing pre made libraries.

Description:

This repository contains a Python implementation of a neural network designed for recognizing handwritten digits from the MNIST dataset. The neural network is trained to classify images of handwritten digits into their corresponding numerical labels (0-9).

### How it works:

1. **Architecture:**
   The neural network consists of an input layer, a hidden layer, and an output layer. The input layer takes flattened pixel values of 28x28 images from the MNIST dataset. The hidden layer utilizes a set of weights (W1) and biases (b1) followed by a nonlinear activation function to capture complex patterns in the data. The output layer employs another set of weights (W2) and biases (b2) with a softmax activation function for multi-class classification.

2. **Forward Propagation:**
   The `forward_prop` function computes the forward propagation through the neural network. It calculates the weighted sums and applies activation functions to produce the final predictions.

3. **Prediction:**
   The `make_predictions` function utilizes the trained weights and biases to make predictions for a given input. It returns the class probabilities using the softmax function.

4. **Testing:**
   The `test_prediction` function allows you to test the performance of the neural network on a specific image from the MNIST training set. It prints the predicted label alongside the actual label and displays the corresponding image for visual inspection.

### Usage:
1. **Training:**
   Train the neural network by providing the MNIST training data to optimize the weights and biases. Ensure you have suitable hyperparameters like learning rate, number of epochs, and batch size.

2. **Prediction:**
   Use the trained model to make predictions on new or test images. The `make_predictions` function can be employed for batch predictions.

3. **Testing:**
   Use the `test_prediction` function to evaluate the model's performance on specific examples from the training set.

Feel free to explore and modify the code to experiment with different neural network architectures, hyperparameters, or datasets. This repository serves as a practical implementation of a neural network for digit recognition, providing insights into the fundamentals of deep learning and its application to image classification tasks.


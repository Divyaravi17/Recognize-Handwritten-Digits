# Recognize-Handwritten_Digits

## Overview

This is a simple prediction problem to identify the handwritten digits using Neural Networks with Tensorflow. 
Tensorflow - open source library used for Machine Learning and Deep Learning applications.
The trained model uses dataset from MNIST. 
MNIST is generally used for Machine learning and Deep learning models.

## Technical Aspect

### a) Input
The trained model uses the mnist dataset of Handwritten digits. Its a dataset of 60,000 grayscale images of single handwritten digits from 0 to 9.

### b) Output
Predicts the Handwritten digits from 0 to 9.

### c) Data Preprocessing - Normalization
We need to normalize the data before feeding it to the Neural network. Pixel values of the dataset will be in the range of 0 to 255, so Normalization happens by scaling these pixel values from 0 to 1 instead of 255. The purpose of this is to make the Neural networks to use less computational power.

### d) Build Model

--> Sequential() - We use Sequence of Neural network layers
--> Flatten() - Changes the dimension of the image
--> Dense() - Adds layers of Neurons
--> Relu Activation function - Passes only 0 or greater to next layer
--> Softmax Activation function - Passes only greatest of value

### e) Compile Model

Optimization algorithms are responsible for reducing the loss and increasing the accuracy of the model.
Here, Adam Optimizer is used because it is efficient, easy to implement and occcupies little memory.

Accuracy is used as Metrics as we need to evaluate the accuracy of the model.

### f) Train the Model

We train our model using the training images and training labels for the number of epochs.

Epoch--> To decrease loss in each iteration.

### g) Evaluate the Model

After training, evaluate our model using test images and obtain the accuracy of our model. Based on the accuracy, we make predictions of the input images and verify it using Data Visualization (Matplot library).


# Recognize-Handwritten_Digits

## Overview

This is a simple prediction problem to identify the handwritten digits using Neural Networks with Tensorflow. The trained model uses dataset from MNIST. MNIST is generally used for Machine learning and Deep learning models.

## Technical Aspect

### a) Input
The trained model uses the mnist dataset of Handwritten digits. Its a dataset of 60,000 grayscale images of single handwritten digits from 0 to 9.

### b) Output
Predicts the Handwritten digits from 0 to 9.

### c) Data Preprocessing - Normalization
We need to normalize the data before feeding it to the Neural network. Pixel values of the dataset will be in the range of 0 to 255, so Normalization happens by scaling these pixel values from 0 to 1 instead of 255. The purpose of this is to make the Neural networks to use less computational power.

### d) Build Model



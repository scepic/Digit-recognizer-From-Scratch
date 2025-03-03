# Digit-recognizer-From-Scratch

Done by: Darin Joseph, Sara Cepic

This project implements a neural network from scratch to recognize hand-written digits from the MNIST dataset. The goal is to demonstrate the fundamentals of neural networks without relying on deep learning frameworks.

Data :

train.csv.zip: Training dataset containing images of hand-written digits and their labels.

test.csv.zip: Test dataset for evaluating the model.

Code :

digit_recognizer_from_scratch.ipynb: Jupyter notebook implementing the neural network from scratch, including data preprocessing, model training, and evaluation.

Project Overview

1. Data Preprocessing

- Loaded the MNIST dataset from the provided CSV files.
- Normalized the pixel values to fall within the range [0, 1].
- Split the data into training and test sets.

2. Model Implementation

- Built a simple neural network with an input layer, two hidden layers, and an output layer.
- Implemented forward and backward propagation manually without using any deep learning libraries.
- Used gradient descent for training the model.

3. Results

- Achieved an accuracy of 94% on the training set and 92% on the test set.
- Visualized the model's predictions on a few test samples.

References

AstroDave and Will Cukierski. Digit Recognizer. https://kaggle.com/competitions/digit-recognizer, 2012. Kaggle.

Acknowledgements

More details about the dataset, including algorithms that have been tried on it and their levels of success, can be found at http://yann.lecun.com/exdb/mnist/index.html. The dataset is made available under a Creative Commons Attribution-Share Alike 3.0 license.

# Digit Classification with PyTorch

## Overview

This project demonstrates a simple implementation of a digit classification model using the `load_digits` dataset from `scikit-learn`. The dataset consists of 8x8 grayscale images of handwritten digits (0–9). The goal is to train a neural network using PyTorch to accurately classify these digits.

## Technologies Used

- **Python**: Core programming language for model development and data manipulation.
- **PyTorch**: Used to build and train a fully connected neural network (FCN) with one hidden layer.
- **NumPy**: For numerical operations and dataset manipulation.
- **scikit-learn**: Used to load the `digits` dataset and split data into training and test sets.
- **Matplotlib**: For visualizing example digits and potentially training results.

## Model Architecture

- Input Layer: 64 neurons (for 8x8 images)
- Hidden Layer: 32 neurons, ReLU activation
- Output Layer: 10 neurons (for classes 0–9)

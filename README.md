# MNIST Digit Recognition using PyTorch

## Overview

This project implements a simple digit recognition model using the MNIST dataset. The model is built using PyTorch and follows a feedforward neural network architecture. The network is trained to classify handwritten digits from 0 to 9 based on images of size 28x28 pixels.

## Table of Contents

- Installation
- Model Architecture
- Training and Evaluation
- Logging and Visualization


## Installation

To run this project, you need to have Python and the following packages installed:

- PyTorch
- torchvision
- matplotlib
- Pillow
- TensorBoard

## Model Architecture

The model is defined in the MyFirstNetwork class, which consists of the following layers:

- Input Layer: Accepts input images of size 28x28 pixels, flattened to a vector of size 784.
- Hidden Layer: Contains 100 neurons with ReLU activation.
- Output Layer: Outputs predictions for 10 classes (digits 0-9). 

## Training and Evaluation

The training process includes the following steps:

- Data Loading: The MNIST dataset is downloaded and split into training, validation, and test sets.
- Training Loop: For each epoch, the model performs a forward pass, computes loss, performs backpropagation, and updates model parameters.
- Evaluation: The model's performance is evaluated on the validation and test datasets at the end of each epoch.

## Logging and Visualization

Logging is handled through Python's built-in logging library, which saves training progress and metrics to a file. Additionally, TensorBoard is used to visualize training loss and accuracy over epochs.


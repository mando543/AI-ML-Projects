# AI-ML-Projects

# KMNIST Classification with PyTorch (R)

This project implements a neural network classifier for the Kuzushiji-MNIST dataset using the torch and luz libraries in R.

## Features
- PyTorch-style neural network in R
- Train/validation/test pipeline
- Fully connected model (MLP)
- Evaluation on unseen data

## Tech Stack
- R
- torch
- torchvision
- luz
- ggplot2

## Model
- Input: 784 features (28x28 images flattened)
- Hidden: 128 neurons (ReLU)
- Output: 10 classes

## Training
- Optimizer: Adam
- Loss: Cross entropy
- Epochs: 10

## Results
Model achieves moderate classification accuracy on KMNIST test set.

## How to Run
Open `kmnist_model.Rmd` in RStudio and knit.

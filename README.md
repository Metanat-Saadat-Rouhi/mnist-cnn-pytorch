# Handwritten Digit Classification with CNN in PyTorch

This project builds a Convolutional Neural Network (CNN) in PyTorch to classify handwritten digits from the MNIST dataset.

It started as part of my PyTorch learning journey and was extended with my own experiments, evaluation, and documentation to make it a portfolio project.

## Project Goal

The goal is to train a CNN that can recognize images of handwritten digits (0–9) and classify them correctly.

## Dataset

This project uses the MNIST dataset:
- 28x28 grayscale handwritten digit images
- 10 classes (digits 0 to 9)
- Training set and test set loaded with `torchvision.datasets.MNIST`

## Model Architecture

The model is a simple CNN with:
- 1 convolution layer
- ReLU activation
- max pooling
- flatten layer
- fully connected output layer

Example flow:

`Input Image -> Conv2D -> ReLU -> MaxPool -> Flatten -> Linear -> Class Scores`

## Tools and Libraries

- Python
- PyTorch
- TorchVision
- Google Colab
- Matplotlib

## Results

### Final Metrics
- Training loss: 0.1738
- Test accuracy: 0.9688


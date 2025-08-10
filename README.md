# Recognizing-a-digit-using-Tensor-flow-Pytorch
Hand-Written-Digit-Classification:
Creating a project which can classify Hand Written Digits into 10 classes (from 0-9) as per the hand written values. The model is implemented using neural network and the dataset used in this project is MNIST dataset.

Implementation Process:
Load the MNIST dataset using Tensorflow. 
Build a simple neural network model.
Train model on training data.
Test modelon test data to see accuracy.
Predicts some sample digits.

Forward pass configuration:
Input_layer => 784 (28*28) grayscale neurons.
Hidden_layer1 => 16 neurons.
Hideen_layer2 => 16 neurons.
Output_layer => 10 neurons (0-9).

Training Configuration:
Optimizer => Adam.
Loss Calculation => Categorical Cross Entropy.
Metrics => Accuracy.

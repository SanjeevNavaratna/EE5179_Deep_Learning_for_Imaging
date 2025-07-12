# EE5179: Deep Learning for Imaging

This repository contains coursework submissions for **EE5179 - Deep Learning for Imaging**, offered at IIT Madras, during the Fall 2024.

## 📘 Course Description

EE5179 covers the foundational and advanced techniques in deep learning specifically applied to imaging tasks. Topics include:

- Neural networks and backpropagation
- Convolutional Neural Networks (CNNs)
- Autoencoders and Unsupervised Learning
- Generative Models (GANs)
- Transfer Learning
- Vision Transformers (ViTs)

## Assignment Overview
🔹 **Assignment 1 (PA1)**: MLP from Scratch
Built a multi-layer perceptron (MLP) from scratch using NumPy.

Tasks included: forward/backward propagation, Glorot initialization, and experimentation with activation functions (Sigmoid, Tanh, ReLU).

Evaluated with training/test loss plots, accuracy, and confusion matrix.

Implemented the same architecture using PyTorch + Adam optimizer + L2 regularization.

➡️ Dataset: MNIST

🔹 **Assignment 2 (PA2)**: Convolutional Neural Networks

Designed a CNN for digit classification with:

Two convolutional layers

Two max-pooling layers

Fully connected layers

Added batch normalization and plotted training/validation/test metrics.

Visualized learned filters and intermediate activations.

Explored adversarial examples (targeted and non-targeted attacks).


🔹 **Assignment 3 (PA3)**: Autoencoders

Compared PCA vs. Autoencoder performance on MNIST.

Trained:

Standard Autoencoder

Sparse Autoencoder (L1 regularization)

Denoising Autoencoder

Convolutional Autoencoder

Visualized reconstructed images and learned filters.

Investigated manifold learning using latent space manipulation.


🔹 **Assignment 4 (PA4)** : Recurrent Neural Networks

Implemented RNN-based digit classification on MNIST by unrolling images across rows/columns.

Compared Vanilla RNNs, LSTMs, GRUs, and Bidirectional RNNs.

Experimented with hyperparameters and evaluated performance on custom hand-drawn digits.

Built an RNN-based binary adder model for bit-by-bit sequence prediction.


## License
This repository is for academic use only as part of coursework.

## Acknowledgements
Thanks to Prof. A.N Rajagopalan and the EE5179 TA's for the excellent material and guidance.

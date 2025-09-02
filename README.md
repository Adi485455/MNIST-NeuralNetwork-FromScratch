# MNIST Neural Network from Scratch

This project demonstrates the implementation of a **neural network from scratch in Python using NumPy** to classify handwritten digits from the **MNIST dataset**. Unlike high-level frameworks like TensorFlow or PyTorch, this project builds every component manually, providing a deep understanding of how neural networks learn.

## Project Overview

The MNIST dataset contains **70,000 grayscale images** of handwritten digits (0–9), each 28x28 pixels. The goal of this project is to train a neural network to correctly classify these digits. This project covers:  

- **Forward propagation**: Calculating outputs layer by layer.  
- **Backward propagation**: Computing gradients to update weights and biases.  
- **Gradient descent**: Optimizing network parameters to reduce loss.  
- **One-hot encoding**: Transforming labels into a format suitable for neural networks.  
- **Data normalization**: Scaling input features for better convergence.  

By building the network manually, this project offers a strong understanding of the underlying mathematics and training mechanics of neural networks.

## Features

- Fully **implemented forward and backward propagation**.  
- **Manual gradient descent** for weight and bias updates.  
- Training achieved **~85% accuracy** on the MNIST training set.  
- Visualizations of predictions for individual digits using **Matplotlib**.  
- Demonstrates practical applications of **NumPy** for linear algebra operations in machine learning.

## Dataset

- [MNIST dataset](https://www.kaggle.com/datasets/hojjatk/mnist-dataset), consisting of:  
  - **60,000 training images**  
  - **10,000 test images**  

The dataset was preprocessed to normalize pixel values and split into training and validation sets.


## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/Adi485455/MNIST-NeuralNetwork-FromScratch.git
   2.	Open the Jupyter notebook (.ipynb) in your preferred environment (Jupyter Lab, VS Code, Google Colab).
	3.	Run all cells to train the network and visualize predictions.

Requirements
	•	Python 3.x
	•	NumPy
	•	Matplotlib

Visuals
You can visualize the network predictions for individual digits. Example:
Prediction: 5
Label: 5

Author

Aditya Jalindar Turkunde – Third-year CSE student passionate about Machine Learning and Deep Learning fundamentals.
GitHub: 
LinkedIn: 


License

This project is licensed under the MIT License – see the LICENSE file for details.






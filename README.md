# MNIST Neural Network from Scratch

A feedforward neural network built from scratch using only NumPy, trained on the MNIST handwritten digit dataset.

Built as a learning project to understand how neural networks actually work under the hood — the math, the matrix operations, and the training loop — without relying on frameworks like PyTorch or TensorFlow.

## What I learned

- How forward propagation works — matrix multiplications, activation functions, softmax
- How backpropagation works — chain rule, computing gradients layer by layer
- How gradient descent updates weights over time
- Why choices like weight initialization and learning rate matter

## Network architecture

- Input layer — 784 neurons (28×28 pixels flattened)
- Hidden layer — 128 neurons with ReLU activation
- Output layer — 10 neurons with Softmax activation (one per digit)

## Implementation

Built entirely from scratch in NumPy:
- Forward pass
- ReLU and Softmax activation functions
- Cross entropy loss
- Backpropagation
- Gradient descent weight updates

The only external library used is TensorFlow — solely to load the MNIST dataset.

## Results
<img width="697" height="601" alt="image" src="https://github.com/user-attachments/assets/8d9e5195-84e4-41af-9936-1bfdcec01d66" />

<img width="748" height="369" alt="image" src="https://github.com/user-attachments/assets/0ba9226a-8b32-4a32-9e73-553e9f6e8f1f" />



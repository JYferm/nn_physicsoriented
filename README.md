# Neural Network MNIST Classification

This project uses a simple neural network to classify handwritten digits from the MNIST dataset using TensorFlow and Keras.

## Dataset

The MNIST dataset consists of 60,000 training images and 10,000 testing images of handwritten digits (0-9).

## Model

The model is a simple neural network with one hidden layer:
- Input layer: Flatten (28x28)
- Hidden layer: Dense (128 units, ReLU activation)
- Output layer: Dense (10 units, Softmax activation)

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/neural_network_mnist.git
   cd neural_network_mnist

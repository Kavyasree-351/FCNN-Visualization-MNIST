# Fully Connected Neural Network (FCNN) Visualization and MNIST Forward Pass

This project demonstrates the structure and basic operation of a **fully connected neural network (FCNN / Multi-Layer Perceptron)** using Python. It provides both a **visualization of the network architecture** and a **forward pass on the MNIST dataset** to illustrate how data flows through the network.

---

## Features

### 1. FCNN Visualization
- Uses **NetworkX** and **Matplotlib** to draw the architecture of a neural network.
- Supports arbitrary layer sizes (input, hidden, output).
- Fully connected layers are visualized with edges connecting all nodes from one layer to the next.
- Optionally limits the number of neurons displayed per layer for clarity in large networks.

### 2. MNIST Image Processing and Forward Pass
- Loads the **MNIST dataset** of handwritten digits.
- Displays a sample image.
- Normalizes pixel values and flattens the image for network input.
- Performs a forward pass through a simple **Keras neural network** with one hidden layer.
- Outputs predicted probabilities for each digit class (0–9).

> **Note:** The network is not trained, so outputs are random. This is intended for demonstration purposes.

---

## Technologies and Libraries Used
- **Python 3**
- **NetworkX** – Graph representation for network visualization
- **Matplotlib** – Visualization of the network and MNIST images
- **NumPy** – Numerical computations
- **TensorFlow / Keras** – Neural network modeling

---

## Installation
1. Clone the repository:

```bash
git clone https://github.com/your-username/FCNN-Visualization-MNIST.git
cd FCNN-Visualization-MNIST


# PyTorch Learning Repository

This repository contains Jupyter notebooks I created to learn and explore core concepts of PyTorch and how it's used in deep learning. Each notebook is focused on a specific topic or project, with hands-on implementations and explanations.

## Contents

- **`basics.ipynb`**  
  Intro to PyTorch: tensors, operations, autograd, and a basic network structure.

- **`linear-regression.ipynb`**  
  Manual and module-based implementation of linear regression using gradient descent and PyTorch’s `nn.Module`.

- **`mnist.ipynb`**  
  A simple feedforward neural network trained on the MNIST dataset for digit classification.

- **`cifar10.ipynb`**  
  Image classification on the CIFAR-10 dataset using a custom convolutional neural network.

## Getting Started

To run these notebooks locally:

1. **Clone the repo**
   ```bash
   git clone https://github.com/john-thomas-ml/pytorch.git
   cd pytorch
   ```

2. **Install dependencies**  
   Make sure Python 3.x is installed. Then run:
   ```bash
   pip install torch torchvision matplotlib
   ```

3. **Run Jupyter**
   ```bash
   jupyter notebook
   ```

## What I Covered

- The basics of PyTorch: tensor operations, autograd, layers.
- Implementing and training neural networks from scratch and using `nn.Module`.
- Using datasets like MNIST and CIFAR-10 for classification.
- Building convolutional neural networks and saving/loading models.

Each notebook is meant to build understanding from the ground up—starting with tensors and linear regression, then moving to deep learning tasks.

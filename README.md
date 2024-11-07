# MicroGrad - Lightweight Autograd Engine

## Overview
MicroGrad is an autograd engine that implements the core functionality of backpropagation for automatic differentiation. This project aims to provide a simplified version of the autograd mechanisms found in larger deep learning frameworks like PyTorch and TensorFlow. 

## Installation
1. Clone this repository
2. Install the required packages:
```
pip install micrograd
```

## Example usage:
```
from micrograd import nn
n = nn.Neuron(2)
x = [Value(1.0), Value(-2.0)]
y = n(x)
dot = draw_dot(y)
```
![Screenshot 2024-11-07 001645](https://github.com/user-attachments/assets/8b75cc20-9cee-4f98-9e2e-3e3e4e088bb3)



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
![Screenshot 2024-09-05 175942](https://github.com/user-attachments/assets/58fd2689-a6c5-4248-b7e0-f25f7c03e4b1)

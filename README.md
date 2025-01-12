# Transformer_implementation
Transformer Homework Assignment

This repository contains the implementation of the Transformer assignment, designed for the CMPE-259 course. It includes a hands-on approach to understanding and building Transformer models using PyTorch.

Course Information

Professor: Jorjeta Jetcheva
T.A.: Hardy Leung
Year: 2023
This assignment was developed to provide students with practical experience in implementing the Transformer architecture.

Repository Content

transformer_implementation.py: Contains the implementation of the Transformer model, including:
Tensor operations.
PyTorch fundamentals.
Detailed walkthrough of the Transformer architecture.
Features

Implementation of a Transformer model as per the Attention is All You Need paper.
Exercises to deepen understanding of PyTorch and the Transformer architecture.
Modular design, allowing extensions for further experiments.
Prerequisites

Ensure you have the following software installed:

Python 3.8+
PyTorch 1.9.0+
NumPy
tqdm (optional, for progress tracking)
Setup Instructions

Clone the repository:
git clone https://github.com/karthikg10/transformer_implementation.git
cd transformer-homework
Install dependencies:
pip install torch numpy tqdm
Usage

To run the Transformer implementation:

Open the transformer_implementation.py file.
Follow the in-file documentation and exercise prompts.
Modify the provided code sections to complete the Part IV exercises.
Example Usage
from transformer_implementation import TransformerModel

# Create a Transformer model
model = TransformerModel(num_layers=6, d_model=512, num_heads=8, d_ff=2048, vocab_size=10000)

# Train the model with your data
model.train(train_data)

# Evaluate the model
model.evaluate(test_data)
Goals of the Assignment

Gain hands-on experience with tensors and PyTorch.
Understand the internals of the Transformer architecture.
Implement and test a working Transformer model.
License

This project is part of the CMPE-259 coursework and is licensed under educational use. Any other use requires explicit permission.

References

Professor Jorjeta Jetcheva, CMPE-259 Course Material, SJSU
Attention is All You Need by Vaswani et al.
PyTorch Documentation

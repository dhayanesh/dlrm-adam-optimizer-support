# DLRM with Adam Optimizer Support

This repository provides an enhanced version of the [Deep Learning Recommendation Model (DLRM)](https://github.com/facebookresearch/dlrm) with support for **Adam** and **SparseAdam** optimizers. This allows for more efficient training of dense and sparse parameters, making it suitable for a variety of recommendation system tasks.

## Features
- **Support for Adam Optimizer**: Use the Adam optimizer for dense parameters like MLP layers.
- **Support for SparseAdam Optimizer**: Use SparseAdam for sparse parameters like embeddings, enabling efficient training.
- **Compatible with PyTorch**: Integrates seamlessly with PyTorch-based DLRM implementations.

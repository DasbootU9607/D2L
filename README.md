# D2L Learning Notes

This repository contains my personal notes and code practice while studying *Dive into Deep Learning* (D2L) and related PyTorch/deep learning materials. The goal is to keep executable notebooks, explanations, and step-by-step walkthroughs in one place for review.

## Repository Structure

```text
.
├── Notes/
│   ├── 1.Data Operation.ipynb
│   ├── 2.Linear Algebra.ipynb
│   ├── 3.Linear Regression.ipynb
│   └── 4.Softmax Regression.ipynb
├── notes4d2l/
│   └── Notes/
│       ├── 1.Data Operation.ipynb
│       ├── 2.Linear Algebra.ipynb
│       ├── 3.Linear Regression.ipynb
│       ├── 4.Softmax Regression.ipynb
│       ├── 5.Perceptron.ipynb
│       ├── 6.Models Training.ipynb
│       └── Step by Step Walkthrough/
│           ├── 5.Perceptron Walkthrough.md
│           └── 6.Models Training Walkthrough.md
└── README.md
```

`Notes/` contains the earlier notebook set. `notes4d2l/Notes/` contains the updated D2L notes, including newer notebooks and English walkthrough documents.

## Notebook Guide

### `Notes/`

- `1.Data Operation.ipynb`: Introduces basic tensor creation, indexing, reshaping, and common data manipulation operations. It builds the foundation for working with numerical data in deep learning.
- `2.Linear Algebra.ipynb`: Covers vectors, matrices, tensor operations, norms, dot products, and matrix multiplication. These concepts support the math used throughout neural networks.
- `3.Linear Regression.ipynb`: Explains linear regression, squared loss, minibatch stochastic gradient descent, and both from-scratch and concise implementations. It is the first full supervised learning workflow.
- `4.Softmax Regression.ipynb`: Introduces multi-class classification, logits, softmax, cross-entropy loss, and Fashion-MNIST classification. It extends linear models from regression to classification.

### `notes4d2l/Notes/`

- `1.Data Operation.ipynb`: Reviews tensor operations and data handling in the D2L/PyTorch workflow. It serves as a practical warm-up for later model notebooks.
- `2.Linear Algebra.ipynb`: Reviews the linear algebra tools needed for deep learning, including matrix operations and vectorized computation. It connects mathematical notation with tensor code.
- `3.Linear Regression.ipynb`: Builds linear regression from data generation through training and evaluation. It emphasizes loss functions, gradient-based optimization, and implementation details.
- `4.Softmax Regression.ipynb`: Covers softmax regression for multi-class classification. It explains how raw model outputs become probabilities and how cross-entropy trains the classifier.
- `5.Perceptron.ipynb`: Moves from the perceptron to multilayer perceptrons. It introduces hidden layers, activation functions, and Fashion-MNIST classification with both from-scratch and PyTorch implementations.
- `6.Models Training.ipynb`: Explains model selection, underfitting, overfitting, weight decay, and dropout. It uses polynomial regression and Fashion-MNIST experiments to show how regularization affects generalization.

### `notes4d2l/Notes/Step by Step Walkthrough/`

- `5.Perceptron Walkthrough.md`: Provides an English step-by-step explanation of the perceptron and multilayer perceptron notebook. It focuses on the intuition behind decision boundaries, hidden layers, activations, and the two MLP implementations.
- `6.Models Training Walkthrough.md`: Provides an English step-by-step explanation of model training, overfitting, weight decay, and dropout. It is written as a readable companion to the notebook rather than executable code.

## Learning Focus

- PyTorch tensor operations
- Linear algebra for deep learning
- Linear regression and softmax regression
- Perceptrons and multilayer perceptrons
- Model selection, regularization, and generalization
- From-scratch implementations compared with concise PyTorch APIs

## Status

This repository is a work in progress. I will keep adding notes, code, and walkthroughs as I move through the course.

## References

- D2L official website: https://d2l.ai/
- D2L Chinese version: https://zh.d2l.ai/
- D2L GitHub repository: https://github.com/d2l-ai/d2l-en
- D2L Chinese GitHub repository: https://github.com/d2l-ai/d2l-zh

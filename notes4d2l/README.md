# D2L Learning Notes

This directory is the main project root for the D2L learning notes. All notebooks, walkthroughs, and future experiments for this study track should live here.

## Structure

```text
notes4d2l/
├── Notes/
│   ├── 1.Data Operation.ipynb
│   ├── 2.Linear Algebra.ipynb
│   ├── 3.Linear Regression.ipynb
│   ├── 4.Softmax Regression.ipynb
│   ├── 5.Perceptron.ipynb
│   ├── 6.Models Training.ipynb
│   └── Step by Step Walkthrough/
│       ├── 5.Perceptron Walkthrough.md
│       └── 6.Models Training Walkthrough.md
└── README.md
```

## Notebook Guide

- `1.Data Operation.ipynb`: Introduces tensor creation, indexing, reshaping, and basic data manipulation. It builds the practical foundation for handling numerical data in PyTorch.
- `2.Linear Algebra.ipynb`: Covers vectors, matrices, tensor operations, norms, dot products, and matrix multiplication. These concepts provide the mathematical language used by neural networks.
- `3.Linear Regression.ipynb`: Explains linear regression, squared loss, minibatch stochastic gradient descent, and implementation from scratch. It is the first complete supervised learning workflow in the notes.
- `4.Softmax Regression.ipynb`: Introduces multi-class classification, logits, softmax, cross-entropy loss, and Fashion-MNIST classification. It extends linear models from predicting numbers to predicting classes.
- `5.Perceptron.ipynb`: Moves from the perceptron to multilayer perceptrons. It introduces hidden layers, activation functions, and both from-scratch and PyTorch MLP implementations.
- `6.Models Training.ipynb`: Explains model selection, underfitting, overfitting, weight decay, and dropout. It uses polynomial regression and Fashion-MNIST examples to show how regularization affects generalization.

## Walkthrough Guide

- `5.Perceptron Walkthrough.md`: Provides a step-by-step English explanation of the perceptron and multilayer perceptron notebook. It focuses on intuition, formulas, and how the from-scratch code maps to PyTorch layers.
- `6.Models Training Walkthrough.md`: Provides a step-by-step English explanation of model training, overfitting, weight decay, and dropout. It is a readable companion to the notebook rather than executable code.

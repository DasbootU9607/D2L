# D2L Learning Notes

This repository contains my D2L learning notes directly at the repo root. The main study notebooks live in `Notes/`, and selected notebooks have English step-by-step walkthroughs in `Notes/Step by Step Walkthrough/`.

## Repository Structure

```text
.
├── Notes/
│   ├── 1.Data Operation.ipynb
│   ├── 2.Linear Algebra.ipynb
│   ├── 3.Linear Regression.ipynb
│   ├── 4.Softmax Regression.ipynb
│   ├── 5.Perceptron.ipynb
│   ├── 6.Models Training.ipynb
│   ├── 7.Neural Network.ipynb
│   └── Step by Step Walkthrough/
│       ├── 5.Perceptron Walkthrough.md
│       └── 6.Models Training Walkthrough.md
├── data/
├── d2l/
└── README.md
```

`Notes/` contains the executable study notebooks. `Notes/Step by Step Walkthrough/` contains English Markdown walkthroughs that explain selected notebooks in a slower, more readable format. `data/` and `d2l/` are local supporting materials and are ignored by Git by default.

## Notebook Guide

- `1.Data Operation.ipynb`: Introduces tensor creation, indexing, reshaping, and basic data manipulation. It builds the practical foundation for handling numerical data in PyTorch.
- `2.Linear Algebra.ipynb`: Covers vectors, matrices, tensor operations, norms, dot products, and matrix multiplication. These concepts provide the mathematical language used by neural networks.
- `3.Linear Regression.ipynb`: Explains linear regression, squared loss, minibatch stochastic gradient descent, and implementation from scratch. It is the first complete supervised learning workflow in the notes.
- `4.Softmax Regression.ipynb`: Introduces multi-class classification, logits, softmax, cross-entropy loss, and Fashion-MNIST classification. It extends linear models from predicting numbers to predicting classes.
- `5.Perceptron.ipynb`: Moves from the perceptron to multilayer perceptrons. It introduces hidden layers, activation functions, and both from-scratch and PyTorch MLP implementations.
- `6.Models Training.ipynb`: Explains model selection, underfitting, overfitting, weight decay, and dropout. It uses polynomial regression and Fashion-MNIST examples to show how regularization affects generalization.
- `7.Neural Network.ipynb`: Reserved for the next neural network notes. It is currently a placeholder for future material.

## Walkthrough Guide

- `5.Perceptron Walkthrough.md`: Provides a step-by-step explanation of the perceptron and multilayer perceptron notebook. It focuses on intuition, formulas, and how the from-scratch code maps to PyTorch layers.
- `6.Models Training Walkthrough.md`: Provides a step-by-step explanation of model training, overfitting, weight decay, and dropout. It is a readable companion to the notebook rather than executable code.

## Learning Focus

- PyTorch tensor operations
- Linear algebra for deep learning
- Linear regression and softmax regression
- Perceptrons and multilayer perceptrons
- Model selection, regularization, and generalization
- From-scratch implementations compared with concise PyTorch APIs

## Status

This repository is a work in progress. I will keep adding notes, code, walkthroughs, and experiments as I move through the course.

## References

- D2L official website: https://d2l.ai/
- D2L Chinese version: https://zh.d2l.ai/
- D2L GitHub repository: https://github.com/d2l-ai/d2l-en
- D2L Chinese GitHub repository: https://github.com/d2l-ai/d2l-zh

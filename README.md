# Grokking Deep Learning

**Author:** Andrew W. Trask  
**Publisher:** Manning Publications  
**Year:** 2019

## About This Repository

This repository contains the code reproduction and theoretical summaries of *Grokking Deep Learning* by Andrew W. Trask. The project aims to improve understanding of fundamental deep learning concepts through practical coding exercises and theoretical explanations based on the book.

The book introduces deep learning from the fundamentals of machine learning and neural networks to more advanced architectures and techniques. It emphasizes understanding how neural networks work by implementing core concepts and examining their learning processes.

## Objectives

- Reproduce the code examples from each chapter of the book.
- Summarize the main concepts discussed in every chapter.
- Explain the theory behind the implemented code and algorithms.
- Understand how neural networks make predictions and learn from errors.
- Build a foundation for studying more advanced deep learning techniques.

## Chapter Summaries

### Chapter 1 — Introducing Deep Learning: Why You Should Learn It

Introduces deep learning, its applications, and its importance in modern technology. It also discusses the prerequisites for learning deep learning, including basic mathematics, Python programming, Jupyter Notebook, and NumPy.

### Chapter 2 — Fundamental Concepts: How Do Machines Learn?

Explains the fundamental concepts of machine learning and deep learning. It introduces supervised and unsupervised learning, as well as parametric and nonparametric models, and describes how machines learn patterns from data.

### Chapter 3 — Introduction to Neural Prediction: Forward Propagation

Introduces neural networks and explains how they make predictions using input data and weights. It covers single-input and multiple-input networks, multiple outputs, and the basic principles of forward propagation using Python and NumPy.

### Chapter 4 — Introduction to Neural Learning: Gradient Descent

Explains how neural networks learn by comparing predictions with actual target values and reducing prediction errors. It introduces error measurement, weight adjustments, hot and cold learning, derivatives, and gradient descent.

### Chapter 5 — Learning Multiple Weights at a Time: Generalizing Gradient Descent

Extends gradient descent to neural networks with multiple inputs, outputs, and weights. It explains how multiple weights are updated during learning and how weighted sums and weight values contribute to predictions.

### Chapter 6 — Building Your First Deep Neural Network: Introduction to Backpropagation

Introduces the construction of a deep neural network through the streetlight prediction problem. It covers data preparation, matrices, learning from datasets, overfitting, indirect correlations, and backpropagation for updating weights across multiple layers.

### Chapter 7 — How to Picture Neural Networks: In Your Head and on Paper

Explains ways to visualize neural networks using simplified diagrams and representations. It helps readers understand the relationships between network inputs, weights, neurons, and predictions.

### Chapter 8 — Learning Signal and Ignoring Noise: Introduction to Regularization and Batching

Introduces techniques for improving neural network generalization. It discusses overfitting, early stopping, dropout, ensemble learning, and batch gradient descent, including their application to the MNIST dataset.

### Chapter 9 — Modeling Probabilities and Nonlinearities: Activation Functions

Explains activation functions and their role in modeling nonlinear relationships and probabilities. It covers hidden-layer and output-layer activation functions, softmax computation, derivatives, and improvements to a neural network for MNIST classification.

### Chapter 10 — Neural Learning About Edges and Corners: Introduction to Convolutional Neural Networks

Introduces convolutional neural networks (CNNs), focusing on weight sharing and convolutional layers. It explains how these techniques help neural networks learn spatial patterns such as edges and corners.

### Chapter 11 — Neural Networks That Understand Language: King – Man + Woman == ?

Introduces natural language processing (NLP) using neural networks. It covers supervised NLP, movie review sentiment prediction, word embeddings, word relationships, and vector arithmetic for exploring semantic similarities and analogies.

### Chapter 12 — Neural Networks That Write Like Shakespeare: Recurrent Layers for Variable-Length Data

Explains how recurrent neural networks process variable-length sequences. It discusses word embeddings, transition matrices, sentence representations, forward propagation, backpropagation, and weight updates for sequence-based learning.

### Chapter 13 — Introducing Automatic Optimization: Let's Build a Deep Learning Framework

Explores the development of a deep learning framework from scratch. It introduces tensors, automatic gradient computation (autograd), optimization, layer types, loss functions, nonlinearities, embedding layers, and recurrent neural network layers.

### Chapter 14 — Learning to Write Like Shakespeare: Long Short-Term Memory

Introduces long short-term memory (LSTM) networks for character-level language modeling. It discusses truncated backpropagation, vanishing and exploding gradients, LSTM gates, model training, and tuning.

### Chapter 15 — Deep Learning on Unseen Data: Introducing Federated Learning

Explores privacy challenges in deep learning and introduces federated learning. It discusses distributed learning, spam detection, secure aggregation, and homomorphic encryption as approaches related to privacy-preserving machine learning.

### Chapter 16 — Where to Go From Here: A Brief Guide

Provides guidance for continuing to learn deep learning. It recommends exploring PyTorch, taking additional courses, studying mathematical foundations, writing technical blogs, implementing academic papers, accessing GPUs, and contributing to open-source projects.

## Tools and Technologies

- Python
- Jupyter Notebook
- NumPy
- GitHub

## Repository Structure

The repository is organized into individual Jupyter Notebook files for each chapter, along with this README file.

```text
Grokking-Deep-Learning/
├── README.md
├── Chapter_01.ipynb
├── Chapter_02.ipynb
├── Chapter_03.ipynb
├── Chapter_04.ipynb
├── Chapter_05.ipynb
├── Chapter_06.ipynb
├── Chapter_07.ipynb
├── Chapter_08.ipynb
├── Chapter_09.ipynb
├── Chapter_10.ipynb
├── Chapter_11.ipynb
├── Chapter_12.ipynb
├── Chapter_13.ipynb
├── Chapter_14.ipynb
├── Chapter_15.ipynb
└── Chapter_16.ipynb
```

## Expected Outcomes

Through this project, the expected outcomes are a better understanding of deep learning fundamentals, practical experience implementing neural networks, and knowledge of how different learning algorithms and neural network architectures operate.

## Reference

Trask, A. W. (2019). *Grokking Deep Learning*. Manning Publications.


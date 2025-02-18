# Deep Learning Tutorials  

## Overview  
This repository contains a collection of **deep learning tutorials** focusing on neural network training, visualization, and explainability. The implementations are done in both **NumPy** and **PyTorch**, with an emphasis on mathematical understanding and manual gradient computation.  

## Contents  

### 1. Training a Deep Neural Network Classifier for MNIST digits from Scratch  without using autograd
- Implements a **one-hidden-layer neural network** with **Batch Normalization** for **MNIST digit classification**.  
- Training is done **without using autograd**—gradients are computed **mathematically**.  
- Implemented in both:  
  - **NumPy**: [`numpy_mnist.ipynb`](numpy_mnist.ipynb)  
  - **PyTorch**: [`torch_mnist.ipynb`](torch_mnist.ipynb)  

### 2. Neural Network Visualization & Explainability  
- **Visualization of weights, pre-activations, and gradients** to verify the effectiveness of different initializations.  
- Basic **XAI (Explainable AI)** techniques:  
  - Analyzing which **neurons are activated** for different digit classes.  
  - Investigating whether the **same digits activate the same neurons**.  
- Implemented in: [`layers.ipynb`](layers.ipynb)  

## Inspiration  
These tutorials are inspired by **Andrej Karpathy’s** deep learning lessons:  
- 📖 Website: [karpathy.ai](https://karpathy.ai)  
- 🎥 YouTube Series: [Neural Networks](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ)  
# Building Your Deep Neural Network: Step by Step

This Jupyter Notebook is part of Week 4 of the Deep Learning Specialization (Course 1) by DeepLearning.AI. It provides the fundamental building blocks for implementing a deep neural network from scratch using NumPy.

In this assignment, you will implement and test all the essential components for forward and backward propagation through an arbitrary number of layers. This notebook lays the foundation for building a full deep learning system in the next assignment.

---

## 📘 Overview

This notebook is designed to transition learners from building a shallow two-layer neural network to a general-purpose **L-layer deep neural network**. You will build modular functions that will be used later in an image classification task.

---

## 🧠 What You'll Learn

By the end of this notebook, you will:

- Understand and use **ReLU** and **Sigmoid** activation functions
- Implement **parameter initialization** for deep networks
- Build forward propagation logic using modular blocks
- Compute the **binary cross-entropy cost function**
- Implement **backward propagation** through multiple layers
- Update parameters using gradient descent
- Combine all steps into a reusable `L_model_forward()` and `L_model_backward()` architecture

---

## 🧪 Topics Covered

### 1. Initialization
- `initialize_parameters` for 2-layer network
- `initialize_parameters_deep` for deep networks

### 2. Forward Propagation
- `linear_forward`
- `linear_activation_forward`
- `L_model_forward`

### 3. Cost Function
- `compute_cost` (cross-entropy)

### 4. Backward Propagation
- `linear_backward`
- `linear_activation_backward`
- `L_model_backward`

### 5. Parameter Updates
- `update_parameters`

Each function is implemented from scratch using NumPy for maximum transparency and understanding.

---

### 🧑‍💻 Who This Is For
Learners transitioning from shallow networks to deeper architectures

Anyone interested in understanding how deep neural networks work at the implementation level

Developers and students who want to build a customizable DNN framework in Python


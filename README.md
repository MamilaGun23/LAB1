# Perceptron Lab

## Overview
This lab is based on the perceptron learning algorithm, one of the earliest supervised learning models for binary classification. The notebook implements a perceptron from scratch, applies it to datasets, and analyzes its behavior during training and testing.

In this hands-on lab, you will:

- Implement the perceptron learning algorithm in Python.
- Train the perceptron on different datasets.
- Visualize decision boundaries.
- Evaluate classification performance and convergence behavior.

---

## Objectives
- Understand how the perceptron updates its weights based on misclassifications.
- Explore the role of learning rate and epochs in convergence.
- Visualize decision regions in 2D feature space.
- Compare performance on linearly separable vs. non-separable data.

---

## Prerequisites
- Python 3.x  
- Libraries: `numpy`, `matplotlib`, `pandas`, `scikit-learn`  

# Perceptron Lab

## Install Dependencies
```bash
pip install numpy matplotlib pandas scikit-learn
```

## Setup
```bash
# Clone this repository
git clone <repo-url>

# Navigate to the lab directory
cd perceptron-lab

# Launch Jupyter
jupyter notebook
```
Open **LAB1.ipynb** and run the cells.

---

## Part 1: Perceptron Implementation
- Define the perceptron class with methods for initialization, training (`fit`), and prediction.  
- Update weights iteratively using the perceptron rule.

---

## Part 2: Training on a Dataset
- Apply the perceptron to synthetic or real datasets (e.g., Iris dataset features).  
- Visualize decision regions and track misclassification errors across epochs.

---

## Part 3: Analysis Questions
### Convergence Behavior
- The perceptron converges when the data is **linearly separable**.  
- If the data is not linearly separable, the algorithm may fail to converge, cycling indefinitely with errors.  

### Effect of Learning Rate (η)
- A very small learning rate slows convergence significantly.  
- A very large learning rate can overshoot and prevent convergence.  
- Moderate values (e.g., 0.01 or 0.1) typically balance stability and speed.  

### Decision Boundaries
- For linearly separable data, the perceptron finds a hyperplane that separates the classes.  
- For non-separable data, the decision boundary oscillates and misclassifications persist.  

### Limitations
- The perceptron cannot handle non-linearly separable problems (e.g., XOR).  
- It is sensitive to feature scaling.  
- Convergence is not guaranteed unless the dataset is separable.  

---

## About
This lab demonstrates the perceptron learning algorithm as an introduction to supervised learning and linear classifiers.

---

## Resources
- Rosenblatt, F. (1958). *The Perceptron: A probabilistic model for information storage and organization in the brain*.  
- Scikit-learn Documentation: [https://scikit-learn.org](https://scikit-learn.org)


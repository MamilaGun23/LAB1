# Lab 1 – Machine Learning Basics (Iris Dataset)

This lab introduces the **fundamentals of machine learning** using the **Iris dataset**.  
It covers **supervised learning**, **unsupervised learning**, and **core ML concepts**.

---

##  Setup

Install required libraries:

```bash
pip install numpy pandas matplotlib scikit-learn

```

# 🌸 Iris Dataset

Features: sepal length, sepal width, petal length, petal width
Target: species (Setosa, Versicolor, Virginica)
A small, well-balanced dataset ideal for learning ML basics.

 Exercise 1 – Import Libraries

NumPy, Pandas → Data handling
Matplotlib → Visualization
scikit-learn → ML models

 Exercise 2 – Logistic Regression (Supervised Learning)

Steps:
Load the Iris dataset.
Perform train-test split (80% train, 20% test).
Train a Logistic Regression classifier.
Evaluate using accuracy and classification report.

# Key Insight

Logistic Regression is used for classification, not regression.
It models probabilities with a sigmoid/logit function.

Exercise 2 (Part B) – K-Means Clustering (Unsupervised Learning)

Steps:

Apply K-Means with 3 clusters.
Assign each flower to a cluster.
Visualize and compare with true species labels.

# Key Insight

K-Means groups data based on similarities.
Does not use target labels during training.

Exercise 3 – K-Nearest Neighbors (KNN)

Steps:

Train-test split (70% train, 30% test).
Train KNN classifier (k = 3).
Predict species and evaluate accuracy.

# Key Insight

KNN is a lazy learner – it stores data and classifies based on nearest neighbors.
Performance depends on k value and feature scaling.

Exercise 4 – Conceptual Knowledge
 
# Supervised Learning

Uses labeled data.
Examples: Logistic Regression, KNN.

Applications:
spam detection
price prediction
medical diagnosis

# Unsupervised Learning

Uses unlabeled data.
Example: K-Means.

Applications:
customer segmentation
anomaly detection.

# Reinforcement Learning

Learns from feedback/rewards.
Applications:
robotics
game AI
self-driving cars.

# Why Train-Test Split?

Prevents overfitting (memorizing training data).
Ensures the model can generalize to unseen data.
Mimics real-world predictive tasks.

# Factors Affecting Model Performance

Dataset size & quality
Feature selection
Algorithm choice & hyperparameters




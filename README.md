# Support Vector Machine (SVM) Classifier

## Overview

This repository contains an implementation of a Support Vector Machine (SVM) Classifier tailored for analyzing a small dataset. The classifier is designed to test and compare the performance of different kernel types—linear, polynomial, and radial basis function (RBF)—for optimal data separation.

### Dataset

The `dataset.mat` file serves as the dataset for the SVM classifier.

### Code

The SVM classifier code is available in the `svm-classifier.ipynb` file. This notebook contains the implementation, configuration, training, and evaluation of the SVM classifier using different kernel types.

---

## What is SVM?
SVM (Support Vector Machine) is a powerful supervised learning algorithm used for classification and regression tasks. It works by finding the optimal hyperplane that separates data points into different classes while maximizing the margin between the classes.

### Linear Kernel Function
The linear kernel function in SVM represents a linear relationship between input features and is suitable for linearly separable data. It calculates the inner product of input features in the original space.

### Polynomial Kernel Function
The polynomial kernel function in SVM allows the algorithm to handle non-linearly separable data by mapping the original features into a higher-dimensional space using polynomial functions.

### RBF Kernel Function
The radial basis function (RBF) kernel in SVM is a popular choice for handling non-linear data. It computes similarity between data points based on their Euclidean distance in the original space, effectively transforming the data into an infinite-dimensional space.

---

## Dependencies
- Python 3.x
- Scikit-learn
- Matplotlib
- NumPy
- SciPy

# Codebasics Machine Learning Exercise

This repository contains code for a machine learning exercise provided by Codebasics. The exercise focuses on practicing K-nearest neighbors (KNN) classification using the digit dataset from the scikit-learn library.

# K Nearest Neighbors Classification

K Nearest Neighbors (KNN) classification is a supervised machine learning algorithm used for classification tasks. It is a non-parametric algorithm that makes predictions based on the majority vote of the K nearest neighbors to a given data point.
The main idea behind KNN classification is that similar data points tend to belong to the same class. When a new data point is presented for classification, the algorithm finds the K closest training samples to that point based on a distance metric (e.g., Euclidean distance) and assigns the class label that appears most frequently among those K neighbors.
KNN classification has several applications and is often used for pattern recognition, image classification, and recommendation systems. It is a simple yet powerful algorithm, but it can be computationally expensive for large datasets.

## Dataset

The dataset used in this exercise is the digit dataset, which is a built-in dataset in scikit-learn. It consists of images of handwritten digits, each represented by a 8x8 pixel matrix. The task is to classify these images into their corresponding digit labels (0-9).

## Model Configuration

In this exercise, the K-nearest neighbors algorithm is used for classification. The KNN algorithm assigns a class to an input sample based on the majority vote of its k nearest neighbors in the feature space. For this particular implementation, the value of `n_neighbors` is set to 7.

## Results

After training the KNN model on the digit dataset, it achieved a model score of 0.9972222222222222. The model score represents the accuracy of the model in predicting the correct digit labels for the test samples.

## Repository Structure

- `K nearest neighbors classification.ipynb`: Jupyter Notebook containing the code for the exercise
- `README.md`: This file, providing an overview of the exercise and the repository


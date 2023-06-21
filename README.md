# Codebasics Machine Learning Exercise

This repository contains code for a machine learning exercise provided by Codebasics. The exercise focuses on practicing K-nearest neighbors (KNN) classification using the digit dataset from the scikit-learn library.

## Dataset

The dataset used in this exercise is the digit dataset, which is a built-in dataset in scikit-learn. It consists of images of handwritten digits, each represented by a 8x8 pixel matrix. The task is to classify these images into their corresponding digit labels (0-9).

## Model Configuration

In this exercise, the K-nearest neighbors algorithm is used for classification. The KNN algorithm assigns a class to an input sample based on the majority vote of its k nearest neighbors in the feature space. For this particular implementation, the value of `n_neighbors` is set to 7.

## Results

After training the KNN model on the digit dataset, it achieved a model score of 0.9972222222222222. The model score represents the accuracy of the model in predicting the correct digit labels for the test samples.

## Repository Structure

- `K nearest neighbors classification.ipynb`: Jupyter Notebook containing the code for the exercise
- `README.md`: This file, providing an overview of the exercise and the repository


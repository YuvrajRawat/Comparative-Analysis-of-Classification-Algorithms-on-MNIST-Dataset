# Comparative-Analysis-of-Classification-Algorithms-on-MNIST-Dataset

This repository contains an implementation of digit classification using various machine-learning algorithms on the MNIST dataset. The goal of this project is to explore and compare the performance of different algorithms for digit recognition.

Overview:
In this project, we implement and compare the performance of the following machine-learning algorithms on the MNIST dataset:

K-Nearest Neighbors (KNN)
Support Vector Machine (SVM)
Random Forest
Multi-Layer Perceptron (MLP)
The accuracy of each algorithm is evaluated on a test dataset, and the final accuracy results are displayed and visualized for comparison.

Dataset:
The MNIST dataset consists of handwritten digit images and their corresponding labels. Each image is a 28x28 grayscale image, and the goal is to classify each image into one of the 10 possible digit classes (0-9).

Implementation:
The implementation can be found in the main.py file. Here's a brief overview of the key steps:

Data Loading and Preprocessing: The MNIST dataset is loaded using the fetch_openml function from sci-kit-learn. The data is split into training and testing sets, and pixel values are normalized to the range [0, 1].

Algorithm Implementation and Evaluation: The following algorithms are implemented and evaluated:

K-Nearest Neighbors (KNN)
Support Vector Machine (SVM)
Random Forest
Multi-Layer Perceptron (MLP)
Accuracy Evaluation: The accuracy of each algorithm is calculated using the accuracy_score function from sci-kit-learn.

Visualization: Accuracy results are displayed using both line and bar graphs. Line graphs show how the accuracy of the MLP classifier changes with the number of training epochs, while bar graphs compare the accuracy of different algorithms.

Results
The accuracy results for each algorithm on the test dataset are as follows:

KNN Accuracy: 0.9701
SVM Accuracy: 0.9351
Random Forest Accuracy: 0.9675
MLP Accuracy: 0.9775

Usage:
To run the code and reproduce the results, follow these steps:

Install the required dependencies by running: pip install -r requirements.txt
Run the main script: python main.py
The accuracy results will be displayed in the console, and graphs will be generated to visualize the performance.
Visualization
Graphs visualizing the accuracy results are generated using Matplotlib and can be found in the visualization directory.

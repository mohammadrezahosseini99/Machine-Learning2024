# Mini Project 2: Implementing and Comparing MLP, Decision Trees, Random Forest, and Naive Bayes

This repository contains the implementation of various machine learning classifiers, including Multi-layer Perceptron (MLP), Random Forest, and Naive Bayes using Python. The project aims to provide a comparative analysis of these classifiers on different datasets. The objective is to evaluate and contrast their performance on specific datasets, identifying their strengths and weaknesses.

## Project Summary

### Classifiers Implemented
- **Multi-layer Perceptron (MLP):** Implemented with diverse architectures and activation functions.
- **Decision Tree and Random Forest:** Compared to assess the performance enhancement provided by ensemble methods.
- **Naive Bayes:** Applied assuming Gaussian distribution of features in the datasets.

### Objectives
- Evaluate the performance of different classifiers on the given datasets.
- Examine the impact of various hyperparameters on classifier performance.
- Identify the strengths and weaknesses of each classifier.

### Project Tasks

#### Task 1: Multi-layer Perceptron (MLP)
1. **Activation Functions:** Compare the sigmoid and ReLU activation functions in a binary classification problem.
2. **Custom Activation Function:** Implement and assess a custom activation function (ELU).
3. **Neuron Design:** Design a simple neuron (McCulloch-Pitts) to classify regions within a triangle.

#### Task 2: Multi-layer Perceptron (MLP) on CWRU Dataset
1. **CWRU Dataset Extension:** Augment the CWRU dataset by adding additional fault classes.
2. **Feature Extraction and Preparation:** Conduct feature extraction and prepare the extended dataset.
3. **MLP Training:** Train an MLP model on the prepared dataset, evaluate accuracy, and plot loss and accuracy curves.
4. **Cross-Validation:** Implement K-Fold and Stratified K-Fold cross-validation methods.

#### Task 3: Decision Tree and Random Forests
1. **Dataset Selection:** Use a dataset related to drug classification or forest cover type.
2. **Decision Tree Training:** Train a decision tree classifier and evaluate its performance.
3. **Parameter Tuning:** Analyze the effect of hyperparameters on the decision tree's performance and apply pruning.
4. **Ensemble Methods:** Compare the decision tree with ensemble methods like Random Forest and AdaBoost.

#### Task 4: Naive Bayes
1. **Heart Disease Dataset:** Use the Heart Disease dataset to train a Gaussian Naive Bayes classifier.
2. **Cross-Validation:** Compare performance using Micro and Macro average methods.
3. **Prediction Analysis:** Analyze the differences between the predicted and actual values. 

## Data Information

### Synthetic Classification Dataset
- **Details:** A synthetic dataset generated using `sklearn.datasets` for binary and multi-class classification tasks.

### CWRU Bearing Dataset
- **Details:** Vibration data collected from a motor under various fault conditions and speeds, used for bearing fault diagnosis.

### Heart Disease Dataset
- **Details:** Medical data used to predict the presence of heart disease, applied for training a Gaussian Naive Bayes classifier.

## About Me

I am a student at K. N. Toosi University of Technology, specializing in Digital Electronics. This repository reflects my work on training and evaluating machine learning models, applying techniques across classification and regression tasks. Throughout this project, I've developed skills in data preprocessing, model training, and evaluation using Python.
# Mini Project 3: SVM and Dimensionality Reduction Techniques

This repository contains the implementation and analysis of Support Vector Machines (SVM) and various dimensionality reduction techniques. The project aims to assess the impact of these techniques on the performance of SVMs using different datasets. The goal is to understand how dimensionality reduction affects classifier performance and to compare the results of SVM with different kernels.

## Project Summary

### Techniques Implemented
- **Support Vector Machines (SVM):** Implemented with linear and polynomial kernels.
- **Dimensionality Reduction:** Applied techniques like t-SNE, PCA, and LDA to the datasets.
- **Data Preprocessing:** Used autoencoders for data denoising and SMOTE for addressing class imbalance.

### Objectives
- Evaluate the impact of dimensionality reduction techniques on SVM performance.
- Compare SVM performance with different kernels on reduced datasets.
- Analyze the effectiveness of data preprocessing methods.

### Project Tasks

#### Task 1: Dimensionality Reduction Techniques
1. **t-SNE Implementation:** Apply t-SNE for visualization and dimensionality reduction.
2. **PCA and LDA:** Implement PCA and LDA to reduce the number of features and retain the most significant ones.
3. **Performance Comparison:** Compare the classification performance before and after applying dimensionality reduction.

#### Task 2: SVM with Different Kernels
1. **Linear Kernel SVM:** Train and evaluate SVM with a linear kernel on the original and reduced datasets.
2. **Polynomial Kernel SVM:** Train and evaluate SVM with a polynomial kernel on the original and reduced datasets.
3. **Custom Kernel Implementation:** Develop and test a custom kernel for SVM and compare its performance.

#### Task 3: Data Preprocessing
1. **Autoencoders for Denoising:** Implement autoencoders to denoise the data before applying SVM.
2. **SMOTE for Class Imbalance:** Apply SMOTE to balance the class distribution in the datasets.
3. **Impact Analysis:** Assess the impact of these preprocessing techniques on the overall performance of SVM.

## Data Information

### Synthetic Dataset
- **Details:** A synthetic dataset generated using `sklearn.datasets` for binary and multi-class classification tasks.

### Real-world Dataset
- **Details:** Various real-world datasets used to demonstrate the effectiveness of dimensionality reduction and SVM techniques.

## About Me

I am a student at K. N. Toosi University of Technology, specializing in Digital Electronics. This repository showcases my work on implementing and evaluating machine learning models, focusing on dimensionality reduction and SVM performance. Through this project, I have gained experience in data preprocessing, model training, and performance evaluation using Python.
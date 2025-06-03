## Breast Cancer Tumor Classification

# Overview

This project analyzes the UCI Breast Cancer Wisconsin Diagnostic dataset to classify tumors as malignant or benign. Using multiple machine learning models — Decision Trees, K-Nearest Neighbors (KNN), and Gaussian Naive Bayes — the project evaluates their performance on tumor classification and explores model interpretability through metrics and visualizations.

# Objectives

Preprocess and explore the breast cancer dataset to identify key predictive features.
Implement and compare classification models: Decision Tree, KNN, and Naive Bayes.
Evaluate models using accuracy, precision, recall, F1-score, and confusion matrices.
Visualize decision boundaries and model outcomes for interpretability.

# Approach

1. Data Preprocessing

Cleaned and prepared the UCI Breast Cancer dataset.
Removed non-informative columns and standardized features for KNN.
Split data into training and testing sets.

2. Modeling

Trained Decision Tree classifier, tuning tree depth for optimal performance.
Trained K-Nearest Neighbors with hyperparameter tuning for best k.
Applied Gaussian Naive Bayes assuming feature independence and Gaussian distributions.

3. Evaluation and Visualization

Computed classification metrics: accuracy, precision, recall, F1-score.
Generated confusion matrices for error analysis.
Plotted decision boundaries for top features to visualize classification regions.

# Key Learnings about the Data
Key features such as mean radius, mean texture, and mean perimeter are strong predictors of malignancy.
The dataset is well-balanced, facilitating robust model training and evaluation.
Standardization significantly improves distance-based model (KNN) performance.

# Key Learnings about the Approach
Decision Trees offer interpretability but can overfit without pruning.
KNN achieves high accuracy when features are scaled properly and k is tuned carefully.
Naive Bayes performs well despite its strong independence assumptions, providing a fast baseline.
Visualization of decision boundaries helps in understanding how models separate tumor classes.

# Tools Used:
Python

scikit-learn for machine learning algorithms and evaluation metrics

pandas, numpy for data handling and preprocessing

matplotlib, seaborn for visualizations

# Notebook Guide

This guide provides a concise overview of each Jupyter notebook in the **Machine Learning Notebook Hub** repository. Use it to choose which notebooks to study and to recall what each one covers.

## Foundations

### data_preprocessing.ipynb
- **Objective:** Introduce essential data cleaning and preprocessing techniques.
- **Key steps:** Handling missing values, encoding categorical variables, scaling numerical features and preparing data for modeling.
- **Outcome:** You’ll understand how to transform raw data into a machine learning–ready dataset.

### data_analysis.ipynb
- **Objective:** Perform exploratory data analysis to uncover patterns and relationships.
- **Key steps:** Calculating summary statistics, exploring distributions, and creating visualizations such as histograms and scatter plots.
- **Outcome:** You’ll gain insights into the structure and characteristics of the dataset before modeling.

## Regression

### simple_linear_regression.ipynb
- **Objective:** Demonstrate how to model the relationship between one feature and a continuous target.
- **Key steps:** Fit a simple linear regression model, visualize the regression line, interpret slope and intercept, evaluate model performance.
- **Outcome:** Learn how to predict a numerical outcome from a single explanatory variable.

### multiple_linear_regression.ipynb
- **Objective:** Extend linear regression to include multiple features.
- **Key steps:** Build a multivariate linear regression model, examine coefficients, evaluate assumptions and interpret results.
- **Outcome:** Understand how multiple factors influence a continuous target.

### polynomial_regression.ipynb
- **Objective:** Show how polynomial terms capture non-linear relationships.
- **Key steps:** Create polynomial features, fit polynomial regression models of varying degrees, compare overfitting and underfitting.
- **Outcome:** Recognize when and how to use polynomial regression to improve predictions.

## Classification

### simple_logistic_regression.ipynb
- **Objective:** Introduce logistic regression for binary classification.
- **Key steps:** Fit a logistic regression model, convert linear outputs to probabilities using the sigmoid function, evaluate predictions using metrics.
- **Outcome:** Understand how to predict binary outcomes and interpret model coefficients.

### knn_classification.ipynb
- **Objective:** Explain the K‑Nearest Neighbors algorithm for classification.
- **Key steps:** Implement K‑NN using scikit‑learn, explore the effect of the number of neighbors (k), evaluate the classifier using accuracy.
- **Outcome:** Learn a non-parametric method based on similarity to classify observations.

### decision_tree_classification.ipynb
- **Objective:** Teach decision tree classifiers.
- **Key steps:** Build a decision tree using information gain or Gini impurity, visualize the tree, prune to prevent overfitting.
- **Outcome:** Understand how hierarchical decisions can separate classes.

### svm_classification.ipynb
- **Objective:** Introduce Support Vector Machines for classification.
- **Key steps:** Train SVM models with linear and radial basis function kernels, experiment with hyperparameters (C, gamma), evaluate results.
- **Outcome:** Learn how SVMs find maximal-margin hyperplanes to classify data.

## Model Evaluation

### cross_validation_example.ipynb
- **Objective:** Illustrate the need for cross-validation in model evaluation.
- **Key steps:** Perform k-fold cross-validation using scikit‑learn, compare results to a single train/test split, discuss bias–variance trade-off.
- **Outcome:** Develop reliable estimates of model performance and understand when to use cross-validation.

### confusion_matrix_example.ipynb
- **Objective:** Explain confusion matrices and related metrics.
- **Key steps:** Compute a confusion matrix from classification predictions, derive accuracy, precision, recall, F1-score, visualize results.
- **Outcome:** Learn how to interpret classification results beyond simple accuracy.

## Unsupervised Learning

### k_means_clustering.ipynb
- **Objective:** Demonstrate k-means clustering for grouping unlabeled data.
- **Key steps:** Initialize centroids, assign points to clusters, update centroids iteratively, choose the optimal number of clusters with the elbow method.
- **Outcome:** Understand how clustering can reveal structure in data without labels.

### pca_example.ipynb
- **Objective:** Introduce Principal Component Analysis for dimensionality reduction.
- **Key steps:** Standardize data, compute principal components, project data onto a lower-dimensional space, visualize explained variance.
- **Outcome:** Learn how to reduce dimensionality while retaining most of the variance.

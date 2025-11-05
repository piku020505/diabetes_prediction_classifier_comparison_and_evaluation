 Diabetes Prediction — Classifier Comparison and Evaluation
 Overview

This project focuses on comparing two popular machine learning algorithms — K-Nearest Neighbors (KNN) and Support Vector Machine (SVM) — for predicting diabetes using real-world datasets.
It also extends the comparison to the Titanic dataset, highlighting how preprocessing and feature scaling impact model performance.

 Objectives

Implement and compare KNN and SVM models on medical and non-medical datasets.

Evaluate model performance using metrics like accuracy, precision, recall, and F1-score.

Understand the effects of data preprocessing, normalization, and encoding.

Identify which model generalizes better across datasets.

 Methodology

Data Loading & Exploration – Inspection of dataset shape, datatypes, and statistical summaries using pandas.

Data Cleaning – Handling missing and biologically implausible values (like zero BMI or glucose).

Feature Scaling – Applying StandardScaler to normalize numerical attributes.

Model Training – Training KNN and SVM models using scikit-learn.

Model Evaluation – Evaluating with accuracy, precision, recall, F1-score, and confusion matrices.

Comparison – Analyzing which classifier performs better on each dataset.

 Results Summary
Dataset	Model	Accuracy	Best Performing
Diabetes	KNN – 70.13%	SVM – 72.08%	SVM
Titanic	KNN – 65.36%	SVM – 68.15%	SVM

 SVM consistently outperformed KNN in both datasets, offering better accuracy and balanced F1-scores.

 Tools & Libraries

Python

Pandas

Scikit-learn

Matplotlib

Seaborn

 Key Insights

SVM provides better generalization in both linear and non-linear datasets.

KNN, while intuitive, is sensitive to scaling and struggles with high-dimensional data.

Proper data preprocessing significantly improves model performance.

Diabetes Prediction – Classifier Comparison and Evaluation
Overview

This project focuses on comparing two popular machine learning algorithms – K-Nearest Neighbors (KNN) and Support Vector Machine (SVM) – for predicting diabetes using real-world datasets.
It also extends the comparison to the Titanic dataset, highlighting how preprocessing and feature scaling impact model performance.

Objectives

Implement and compare KNN and SVM models on medical and non-medical datasets.

Evaluate model performance using metrics like accuracy, precision, recall, and F1-score.

Understand the effects of data preprocessing, normalization, and encoding.

Identify which model generalizes better across datasets.

Methodology

Data Loading & Exploration – Inspection of dataset shape, datatypes, and statistical summaries using Pandas.

Data Cleaning – Handling missing and biologically implausible values (like zero BMI or glucose).

Data Preprocessing – Encoding categorical variables and applying feature scaling using StandardScaler.

Data Splitting – Dividing data into training (80%) and testing (20%) sets for unbiased evaluation.

Model Training – Implementing SVM (using SVC) and KNN (using KNeighborsClassifier) with Scikit-learn.

Model Evaluation – Comparing accuracy, precision, recall, and F1-score through confusion matrices.

Results
Diabetes Dataset

KNN Model Accuracy: 70.13%

SVM Model Accuracy: 72.08%

SVM showed better performance with more balanced precision and recall across classes.

Titanic Dataset

KNN Model Accuracy: 65.36%

SVM Model Accuracy: 68.15%

SVM achieved higher accuracy and recall, indicating stronger generalization.

Conclusion

SVM consistently outperformed KNN across both datasets.

Proper data preprocessing (imputation and scaling) significantly improved model results.

Both models showed limitations in recall for positive classes, suggesting further optimization potential.

SVM is better suited for high-dimensional data and non-linear classification tasks.

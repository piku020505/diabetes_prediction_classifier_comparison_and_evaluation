Diabetes Prediction: Classifier Comparison and Evaluation
Overview

This project presents a comparative analysis of two supervised machine learning algorithms — K-Nearest Neighbors (KNN) and Support Vector Machine (SVM) — for the prediction of diabetes using the Pima Indians Diabetes Dataset.
The same methodology is also extended to the Titanic Dataset to analyze algorithmic performance across different domains.

The primary objective is to evaluate the performance of these algorithms using accuracy, precision, recall, and F1-score, and determine the most suitable model for predictive classification tasks.

Objectives

To implement and compare KNN and SVM models.

To evaluate each model using performance metrics such as accuracy, precision, recall, and F1-score.

To understand the impact of data preprocessing (handling missing values, normalization, encoding) on model accuracy.

To determine the algorithm better suited for structured, real-world datasets.

Tools and Libraries

Python

Pandas – For data loading, cleaning, and manipulation

Scikit-learn (sklearn) – For data preprocessing, model implementation, and evaluation

Matplotlib and Seaborn – For visualization and graphical analysis

Methodology

Data Loading and Exploration

Imported dataset into Pandas DataFrame.

Performed initial exploration using .info(), .describe(), and summary statistics.

Data Preprocessing

Identified and replaced biologically implausible zero values with mean imputation.

Encoded categorical variables where necessary.

Applied StandardScaler to normalize numerical features.

Data Splitting

Split data into 80% training and 20% testing sets using train_test_split().

Model Development

Implemented SVM using SVC() and KNN using KNeighborsClassifier() from Scikit-learn.

Trained both models on the preprocessed training data.

Model Evaluation

Evaluated models using accuracy, precision, recall, and F1-score.

Generated confusion matrices to analyze classification performance.

Results
Diabetes Dataset
Model	Accuracy	Key Observations
KNN	70.13%	Struggled slightly with recall for diabetic patients.
SVM	72.08%	Achieved higher accuracy and balanced performance across metrics.
Titanic Dataset
Model	Accuracy	Key Observations
KNN	65.36%	Performed moderately with lower recall.
SVM	68.15%	Outperformed KNN in accuracy and recall balance.

Overall Observation:
Across both datasets, SVM outperformed KNN, providing better generalization and stability in performance metrics.

Conclusion

Support Vector Machine (SVM) achieved higher accuracy compared to K-Nearest Neighbors (KNN).

Data preprocessing (imputation and scaling) played a vital role in improving model results.

Both algorithms showed limitations in recall for positive classes, indicating potential for further optimization.

SVM is more suitable for high-dimensional and linearly/non-linearly separable datasets.

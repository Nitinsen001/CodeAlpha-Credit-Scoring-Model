# CodeAlpha-Credit-Scoring-Model
Credit Risk Analysis and Classification
This project develops and evaluates a credit risk classification model to predict whether a person is "creditworthy" or "not creditworthy" based on the German Credit Data from the UCI Machine Learning Repository.

The project follows a standard machine learning workflow, from data loading and preprocessing to model training and evaluation. It compares the performance of two popular classification algorithms: Logistic Regression and Random Forest.

Features
Data Loading and Preparation: Fetches the German Credit Data directly using the ucimlrepo library.

Preprocessing: Handles both numerical and categorical features.

Numerical features are scaled using StandardScaler.

Categorical features are converted into a numerical format using OneHotEncoder.

Model Training: Uses scikit-learn pipelines to streamline the workflow for:

Logistic Regression: A simple yet effective linear model.

Random Forest: A powerful ensemble method for better accuracy.

Model Evaluation: Assesses model performance using:

classification_report: Provides precision, recall, and F1-score.

roc_auc_score: Measures the area under the receiver operating characteristic curve.

Simplified Predictions: Demonstrates how to make and interpret predictions on new data, mapping the model's output to "Creditworthy" or "Not Creditworthy" for easy understanding.

How to Run the Code
Dependencies: Make sure you have the required libraries installed.

Bash

pip install scikit-learn pandas ucimlrepo
Run Script: Execute the main Python script.

Bash

python your_script_name.py
Results
The script will print the performance metrics for both models on the test data. The results will show the classification_report and the ROC-AUC score for Logistic Regression and Random Forest, respectively.

It will also display a sample of simplified predictions to show the final output.

Conclusion
This project provides a clear example of a complete credit scoring pipeline. It shows how to preprocess a mixed-type dataset and train different classification models to solve a real-world problem. The use of pipelines ensures the process is efficient and reproducible.

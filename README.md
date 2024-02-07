# Caltech101-Analysis
Utilize classification methods on the "Caltech101" dataset with pre-extracted Edge Histogram features, train three models, find optimal hyperparameters, and submit results as CSV files. Include confusion matrices, hyperparameter lists, and detailed experiment setup documentation in CSV format for evaluation.

# README.txt

## Program Overview:

This Jupyter Notebook conducts a machine learning experiment using three classifiers: Support Vector Machine (SVM), XGBoost, and Decision Tree. The dataset combines 'EdgeHistogram.csv' and 'Images.csv', aiming to classify images based on edge histogram features.

## Installation:

1. Ensure Python (version 3.6 or higher) is installed on your system.
2. Install required libraries:


3. Install Jupyter Notebook:


4. Download 'EdgeHistogram.csv' and 'Images.csv', placing them in the same directory as this notebook.

## Execution:

1. Open a terminal, navigate to the notebook's directory.
2. Start Jupyter Notebook:


3. Open `Spurce-Code.ipynb`.
4. Execute cells sequentially. Ensure libraries are imported, and datasets are loaded before running models.
5. The notebook generates classification reports, confusion matrices, and saves hyperparameters for each classifier.

## Operation:

- Demonstrates SVM, XGBoost, and Decision Tree classifiers for image classification.
- Datasets are preprocessed, features are extracted, and data is split into training and testing sets.
- Each classifier is trained on the training set and evaluated on the test set, with results saved in CSV files.
- Hyperparameters for each classifier are also saved in separate CSV files.
- Visualization of confusion matrices is provided using Plotly Express.

Note: Ensure necessary permissions for reading and writing files in the execution directory.

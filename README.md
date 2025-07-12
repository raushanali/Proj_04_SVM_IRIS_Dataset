# Proj_04_SVM_IRIS_Dataset

This project applies a Support Vector Machine (SVM) classifier to the Iris dataset using the scikit-learn library. The Iris dataset, first used by R.A. Fisher in 1936, is a classic example in machine learning. It contains 50 samples each from three different species of Iris:

Iris Setosa

Iris Versicolor

Iris Virginica

Purpose
The purpose of this project is to distinguish between two species (Setosa and Versicolor) based on their sepal length and width using SVM.

Key Features
Data Loading: Loads the built-in Iris dataset from scikit-learn.

Data Selection: Selects only the first 100 samples (Setosa and Versicolor) and two features (Sepal Length, Sepal Width).

Model Training: Trains an SVM classifier with a linear kernel.

Visualization: Plots the data points and the decision boundary computed by the SVM.

Performance Metrics: Computes and displays the confusion matrix and accuracy score.

Usage Instructions
Run the Code:

Execute the code with Python 3. Make sure numpy, matplotlib, and scikit-learn are installed.

Understand the Output:

A graph will be displayed showing the data points and the SVM decision line.

The console will print the confusion matrix and accuracy score.

The ConfusionMatrixDisplay will also show a graphical display of the confusion matrix.

Output Explanation
Confusion Matrix: Shows how many samples were correctly or incorrectly classified.

Accuracy Score: Displays the model's accuracy as a percentage.

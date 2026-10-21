# Experiment 8: Comparison of Classification Algorithms

## Aim

To implement and compare different classification algorithms using a labelled dataset.

## Dataset

**Iris Dataset**

The Iris dataset contains measurements of iris flowers, including sepal length, sepal width, petal length, and petal width. The target variable represents the flower species.

Dataset source: Use the same Iris CSV file used in the notebook.

## Algorithms Used

### 1. Logistic Regression

Logistic Regression estimates class probabilities and assigns an input to a class.

### 2. Decision Tree Classifier

A Decision Tree classifies data using a series of feature-based decision rules.

### 3. Random Forest Classifier

Random Forest combines predictions from multiple decision trees and selects the final class using voting.

### 4. Support Vector Machine (SVM)

SVM finds a decision boundary that separates classes while aiming to maximize the margin between them.

### 5. K-Nearest Neighbors (KNN)

KNN predicts the class of a sample using the majority class among its nearest data points.

### 6. Gaussian Naive Bayes

Gaussian Naive Bayes uses Bayes' theorem and assumes that each feature follows a Gaussian distribution within each class.

## Implementation

1. Import the required Python libraries.
2. Load and inspect the dataset.
3. Handle missing values and prepare the target labels.
4. Split the dataset into training and testing sets.
5. Scale the features where required.
6. Train the six classification models.
7. Predict the classes for the test data.
8. Calculate the evaluation metrics.
9. Compare model performance using a graph.

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

## Libraries Used

* Pandas
* NumPy
* Matplotlib
* Scikit-learn

## Result

Six classification algorithms were implemented and evaluated. Their performance was compared using classification metrics, and the results are presented in the notebook.


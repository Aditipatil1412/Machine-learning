# Experiment 5: Support Vector Machine for Classification

## Aim

To implement a Support Vector Machine (SVM) algorithm for classification and evaluate its performance on a suitable dataset.

## Objectives

* To understand the working principle of SVM.
* To identify the role of support vectors and the decision boundary.
* To train an SVM classification model.
* To evaluate classification performance using suitable metrics.

## Theory

Support Vector Machine (SVM) is a supervised machine learning algorithm used for classification and regression. In classification, it attempts to find a decision boundary, called a hyperplane, that separates different classes.

SVM aims to maximize the margin between the decision boundary and the nearest data points from each class. These nearest points are called support vectors.

For data that cannot be separated effectively using a straight line or hyperplane, SVM can use kernel functions such as the linear, polynomial, and Radial Basis Function (RBF) kernels.

Feature scaling is generally important for SVM because the algorithm is sensitive to the scales of input features.

Classification performance can be evaluated using accuracy, precision, recall, F1-score, and a confusion matrix.

## Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## Algorithm

1. Import the required libraries.
2. Load the classification dataset.
3. Separate the input features and target variable.
4. Split the dataset into training and testing sets.
5. Standardize the input features.
6. Create and train the SVM classifier.
7. Predict the class labels for the test data.
8. Calculate classification evaluation metrics.
9. Display the results and visualize the decision boundary if appropriate.

## Expected Output

* Trained SVM classification model.
* Predicted class labels.
* Classification accuracy.
* Confusion matrix and classification report.
* Decision boundary visualization, if applicable.

## Result

The SVM classification algorithm was implemented and evaluated using suitable classification metrics.


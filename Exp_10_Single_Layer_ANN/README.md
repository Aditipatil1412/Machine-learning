# Single-Layer Artificial Neural Network

## Aim

To build a single-layer artificial neural network for a binary classification problem.

## Dataset

**Student Performance Dataset**

The dataset contains student-related information, such as previous grades, study time, and absences. In this experiment, the target is created to classify students as pass or fail based on their final grade.

A student with a final grade of 10 or above is labelled as pass, while a grade below 10 is labelled as fail.

Dataset source: Use the same Student Performance CSV file used in the notebook.

## Concepts Used

### 1. Artificial Neural Network

An Artificial Neural Network is a machine learning model inspired by the connections between neurons in the human brain.

### 2. Sigmoid Activation Function

The sigmoid function converts the weighted sum of the inputs into a value between 0 and 1. This value can be interpreted as the estimated probability of the positive class.

### 3. Binary Cross-Entropy Loss

Binary cross-entropy measures the difference between the predicted probabilities and the actual binary labels.

### 4. Gradient Descent

Gradient descent updates the model weights and bias to reduce the loss during training.

## Implementation

1. Import the required libraries.
2. Load the Student Performance dataset.
3. Select the input features and create the pass/fail target.
4. Split the dataset into training and testing sets.
5. Normalize the input features.
6. Initialize the weights and bias.
7. Implement the sigmoid activation function.
8. Train the network using gradient descent.
9. Generate predictions.
10. Evaluate the model and plot the training loss.

## Evaluation Metrics

* Accuracy
* Confusion Matrix
* Precision
* Recall
* F1-score
* Training Loss Curve

## Libraries Used

* Pandas
* NumPy
* Matplotlib
* Scikit-learn

## Result

A single-layer neural network was implemented using NumPy for binary classification. The model was evaluated using classification metrics, and its training loss was visualized.


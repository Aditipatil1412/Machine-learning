# Data Preprocessing on a Raw Dataset

## Aim

To perform data preprocessing on a raw dataset by handling missing values, normalization, and standardization.

## Objectives

* To understand the importance of data preprocessing in machine learning.
* To identify and handle missing values in a dataset.
* To apply normalization and standardization techniques.
* To prepare clean data for further analysis and model training.

## Theory

Data preprocessing is an important step in machine learning. Raw datasets may contain missing values, inconsistent data, or features with different numerical scales. These problems can affect the performance of machine learning algorithms.

**1. Handling Missing Values:** Missing values can be identified using functions such as `isnull()` and handled using techniques such as mean, median, or mode imputation.

**2. Normalization:** Normalization scales numerical values to a fixed range, usually between 0 and 1. Min-Max scaling is a commonly used normalization technique.

**3. Standardization:** Standardization transforms data so that its mean is approximately 0 and its standard deviation is approximately 1. StandardScaler is commonly used for this purpose.

## Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## Algorithm

1. Import the required libraries.
2. Load the raw dataset.
3. Display the first few rows and inspect the dataset.
4. Identify missing values.
5. Handle missing values using a suitable imputation technique.
6. Apply normalization to numerical features.
7. Apply standardization to numerical features.
8. Display and compare the processed data.

## Expected Output

* Original dataset information.
* Missing-value count before and after handling.
* Normalized numerical values.
* Standardized numerical values.

## Result

Data preprocessing was performed on the raw dataset by handling missing values and applying normalization and standardization techniques.


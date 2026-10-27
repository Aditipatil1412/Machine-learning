# Principal Component Analysis (PCA)

## Aim

To apply Principal Component Analysis (PCA) to a multivariate dataset to reduce its dimensionality, visualize the data in lower dimensions, and evaluate the variance retained after transformation.

## Objectives

* To understand dimensionality reduction.
* To reduce the number of features in a dataset.
* To transform the original features into principal components.
* To visualize high-dimensional data in two dimensions.
* To calculate the amount of variance retained after PCA transformation.

## Theory

Principal Component Analysis (PCA) is an unsupervised dimensionality reduction technique. It transforms a dataset containing multiple correlated features into a smaller set of new features called principal components.

The first principal component captures the maximum possible variance in the data. The second principal component captures the maximum remaining variance while being orthogonal to the first component.

Before applying PCA, numerical features are commonly standardized because features with larger scales can otherwise dominate the transformation.

The explained variance ratio indicates the proportion of the total variance captured by each principal component. The cumulative explained variance helps evaluate how much information is retained after reducing the dimensions.

## Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## Algorithm

1. Import the required libraries.
2. Load the multivariate dataset.
3. Select the numerical features.
4. Handle missing values, if present.
5. Standardize the selected features.
6. Apply PCA to transform the original features.
7. Calculate the explained variance ratio and cumulative variance.
8. Visualize the transformed data using the first two principal components.
9. Analyze the amount of variance retained.

## Expected Output

* Standardized feature data.
* Principal component values.
* Explained variance ratio.
* Cumulative explained variance.
* Two-dimensional PCA scatter plot.

## Result

PCA was applied to reduce the dimensionality of the dataset. The transformed data was visualized in lower dimensions, and the variance retained after transformation was evaluated.


# Experiment 9: K-Means Clustering

## Aim

To implement the K-Means clustering algorithm to group data into multiple clusters based on similarity.

## Dataset

**Mall Customer Segmentation Dataset**

The dataset contains customer information, including annual income and spending score. These features can be used to identify groups of customers with similar characteristics.

Dataset source: Kaggle. Use the same CSV file downloaded for the notebook.

## Algorithm Used: K-Means Clustering

K-Means is an unsupervised machine learning algorithm that divides data into K clusters.

The algorithm works as follows:

1. Select the number of clusters, K.
2. Initialize K cluster centroids.
3. Assign each data point to its nearest centroid.
4. Recalculate the centroids.
5. Repeat the assignment and centroid update steps until the clusters stabilize.

## Implementation

1. Import the required libraries.
2. Load and inspect the dataset.
3. Handle missing values.
4. Select annual income and spending score as input features.
5. Scale the selected features.
6. Use the Elbow Method to help determine a suitable number of clusters.
7. Apply the K-Means algorithm.
8. Assign each customer to a cluster.
9. Visualize the clusters and centroids.
10. Calculate the Silhouette Score.

## Evaluation Methods

* **Elbow Method:** Uses within-cluster sum of squares (WCSS) to help choose the number of clusters.
* **Silhouette Score:** Measures how well-separated and cohesive the clusters are.

## Libraries Used

* Pandas
* NumPy
* Matplotlib
* Scikit-learn

## Result

The K-Means algorithm groups customers according to similarities in annual income and spending score. The resulting clusters are visualized in the notebook.


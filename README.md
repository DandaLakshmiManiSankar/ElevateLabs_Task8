# ElevateLabs_Task8_K-Means Clustering - Mall_Customer Segmentation
## Objective
Perform unsupervised customer segmentation using K-Means Clustering on the Mall Customer Segmentation dataset. The goal is to group customers based on their characteristics like age, income, and spending behavior.

## Dataset
Source: Kaggle
File: Mall_Customers.csv[https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python]

## Features:
-CustomerID
-Gender
-Age
-Annual Income (k$)
-Spending Score (1-100)

## Tools Used
-Python
-Pandas
-Matplotlib
-Seaborn
-Scikit-learn

## Tasks Performed
-Data Preprocessing
-Removed CustomerID
-Encoded Gender as binary
-Standardized the features
-Dimensionality Reduction
-Applied PCA for 2D visualization
-K-Means Clustering
-Fit K-Means with selected K
-Assigned cluster labels
-Finding Optimal K
-Used Elbow Method
-Evaluated with Silhouette Score

## Visualization
-2D PCA-based cluster plot
-Elbow plot for K
-Pairplots (optional)

## Evaluation
-Silhouette Score reported: 0.272

## Elbow Method Plot
-The elbow plot helps identify the optimal number of clusters by observing the point where the inertia curve starts to flatten.

## Cluster Visualization
-Clusters were visualized using the first two principal components (PCA), with each customer represented as a point colored by its assigned cluster.

## Evaluation Metric
1.Silhouette Score:
-Measures how similar a point is to its own cluster vs. other clusters.
-Score obtained: 0.272
-Indicates some cluster structure, though not very well separated.

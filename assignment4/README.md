# Customer Segmentation using Agglomerative Hierarchical Clustering

## Problem Statement:
Perform customer segmentation on a dataset collected from a cosmetics shop to identify distinct customer groups based on their purchasing behavior. The cosmetics shop aims to tailor marketing strategies for each segment to enhance customer engagement and satisfaction.

## Objective:
The main objective is to apply Agglomerative Hierarchical Clustering to cluster customers into homogeneous groups based on their purchasing patterns. By doing so, the shop can gain insights into customer preferences and behaviors, allowing for targeted marketing campaigns and personalized recommendations.

## Software and Hardware:
### Software used:
- Python 3.x
- Google Colab
### Libraries and packages used: 
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Agglomerative Hierarchical Clustering:
- **Unsupervised Learning Algorithm:** Agglomerative Hierarchical Clustering is an unsupervised learning algorithm that groups similar data points into clusters without requiring labeled data for training.
- **Bottom-Up Approach:** This algorithm follows a bottom-up approach, where each data point initially represents a separate cluster. It then iteratively merges the closest clusters until all data points belong to a single cluster.
- **Dendrogram:** A dendrogram is often used to visualize the hierarchical clustering process, displaying the merging of clusters at each step.
- **Distance Metrics:** Various distance metrics such as Euclidean distance, Manhattan distance, or cosine similarity can be used to measure the similarity between data points.
- **Cluster Fusion:** Different fusion criteria, such as single linkage, complete linkage, or average linkage, determine how clusters are merged at each step.

## Working of Agglomerative Hierarchical Clustering:
- Initially, each data point is treated as a separate cluster.
- At each iteration, the algorithm merges the two closest clusters based on a specified distance metric.
- This process continues until all data points belong to a single cluster or until a stopping criterion is met.
- The resulting dendrogram can be used to determine the optimal number of clusters by observing the heights of the fusion points.

## Conclusion:
In conclusion, Agglomerative Hierarchical Clustering is a versatile algorithm for customer segmentation and other clustering tasks. By grouping similar data points into clusters, it enables businesses to gain valuable insights into their customer base and tailor their strategies accordingly. However, it's essential to preprocess the data appropriately, choose suitable distance metrics and fusion criteria, and interpret the clustering results effectively to derive actionable insights.

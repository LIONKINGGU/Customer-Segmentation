# Customer-Segmentation
Objective:
This project aims to cluster customers based on their purchasing behavior using the K-means clustering algorithm. The goal is to uncover distinct segments within the customer base.

The project starts by loading customer data from 'customersdata.csv' and exploring the data types to understand the nature of the features.

Irrelevant columns ('Channel' and 'Region') are dropped, as they are not needed for clustering. The dataset is then standardized to ensure uniform scales for accurate clustering.

The optimal number of clusters is determined using the elbow method. This technique helps find the point where the within-cluster sum of squares (WCSS) no longer decreases significantly, indicating a suitable number of clusters.

The K-means algorithm is employed with the chosen number of clusters (5 in this case). The model is fitted to the data, and predictions are made to assign each customer to a specific cluster.

Results are visually presented using a scatter plot. Each cluster is differentiated by a unique color, and centroids are marked in yellow. This visualization provides a clear representation of how customers are grouped based on their 'Frozen' and 'Milk' purchases.

The clusters and centroids reveal insights into customer segments. Businesses can use this information for targeted marketing strategies, product recommendations, and tailored services for each customer cluster.

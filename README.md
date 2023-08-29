# Customer Segmentation


## Introduction

This project focuses on customer segmentation, a crucial task in data-driven businesses. Customer segmentation helps in understanding customer behavior, which in turn aids in making informed marketing and product development decisions. In this project, we have explored customer segmentation using various clustering algorithms and identified the most suitable model.


## Dataset

The dataset used for this project was obtained from Kaggle. It contains relevant customer data that is crucial for segmentation. The dataset includes features such as income, spending score, and more.


## Project Structure

The project is organized into two Jupyter notebooks:


* **Data Exploration**: This notebook explores the dataset, visualizes key features, and performs initial data analysis. It lays the foundation for understanding the dataset and its characteristics.

* **Cluster_Models**: In this notebook, we delve into the heart of the project. We apply four different clustering algorithms - K-means, Mean Shift, DBSCAN, and Agglomerative Clustering - to segment the customers. We calculate two important metrics, Silhouette Score and Davies-Bouldin Score, to evaluate the quality of the clusters produced by each algorithm. Finally, we identify the best-performing model.


## Clustering Algorithms

The clustering algorithms applied in this project:

* **K-means**: This algorithm partitions the data into K distinct clusters, where each data point belongs to the cluster with the nearest mean. It aims to minimize the variance within each cluster.

* **Mean Shift**: Mean Shift is a density-based clustering algorithm. It shifts data points towards the mode (peak) of the data distribution to identify clusters.

* **DBSCAN**: Density-Based Spatial Clustering of Applications with Noise (DBSCAN) groups together data points that are close to each other based on a density criterion. It identifies noise points as well.

* **Agglomerative Clustering**: This is a hierarchical clustering method. It starts with each data point as a single cluster and then merges clusters until a stopping criterion is met.


## Model Evaluation

We evaluated the clustering models using two key metrics:

* **Silhouette Score**: This metric measures how similar an object is to its own cluster compared to other clusters. It ranges from -1 (a poor clustering) to +1 (a perfect clustering). A higher Silhouette Score indicates better-defined clusters.

* **Davies-Bouldin Score**: This score measures the average similarity between each cluster and its most similar cluster. It is bounded between 0 and +∞, with lower values indicating better clustering.


## Dependencies

The project was implemented using Python and popular data science libraries such as pandas, numpy, scikit-learn, and matplotlib.


## Usage

To replicate the results, follow the steps outlined in the notebooks: Data Exploration and Cluster_Models.
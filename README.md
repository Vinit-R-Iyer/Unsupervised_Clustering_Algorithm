# Unsupervised_Clustering_Algorithm

**About the Project**
<br>
    This Unsupervised Clustering Algorithm was one of the projects completed during my course with Internshala on Machine Learning using Python. This project uses actual data gathered and uses it to segregate the given regions of the provided data into different groups so that the Marketing team of a firm can plan their resources accordingly to launch their promotional campaign.
<br>
<br>

**Languages and Libraries used**
<br>
<br>
<img src = "https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue">
<img src = "https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white">
<img src = "https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white">
<img src = "https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white">
<br>
<br>

**About the Machine Learning Model**
<br>
    Cluster analysis or clustering is the task of grouping a set of objects in such a way that objects in the same group (called a cluster) are more similar (in some sense) to each other than to those in other groups (clusters).
    
  Unsupervised learning is a type of algorithm that learns patterns from untagged data. In contrast to supervised learning where data is tagged by a human, e.g., as "car" or "fish" etc, Unsupervised Learning exhibits self-organization that captures patterns as probability densities, etc. Clustering can be considered the most important unsupervised learning problem; so, as every other problem of this kind, it deals with finding a structure in a collection of unlabelled data. 
  
  K-means is one of the simplest unsupervised learning algorithms that solves the wellknown clustering problem. The procedure follows a simple and easy way to classify a given data set through a certain number of clusters (assume k clusters) fixed a priori. The main idea is to define k centres, one for each cluster. These centroids should be placed in a smart way because of different location causes different result. The next step is to take each point belonging to a given data set and associate it to the nearest centroid. When no point is pending, the first step is completed and an early groupage is done. At this point we need to re-calculate k new centroids of the clusters resulting from the previous step. After we have these k new centroids, a new binding has to be done between the same data set points and the nearest new centroid. A loop has been generated. As a result of this loop we may notice that the k centroids change their location step by step until no more changes are done. In other words centroids do not move any more. In the following Clustering algorithm, we have utilized the K-means as a type of algorithm.
<br>
<br>

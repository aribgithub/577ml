Introduction of K-Means Clustering
In this file, we will introduce K-means clustering. Data is extracted from Kaggle. The data is the customers data from a shopping mall. It included many variables as following: customer ID, gender, age, annual Income, Spending score and education level. We will determine the optimal number of clusters and cluster the data. In the end, I also introduce PCA and combine PCA and K-means clustering.

K-means clustering is one of the simplest and popular unsupervised machine learning algorithms.

K refers to the number of centroids you need in the dataset.
The ‘means’ in the K-means refers to averaging of the data.
A cluster refers to a collection of data points aggregated together because of certain similarities.
The K-means algorithm identifies k number of centroids, and then allocates every data point to the nearest cluster, while keeping the centroids as small as possible.

Algorithm

We start data mining with a first group of randomly selected centroids, which are used as the beginning points for every cluster. Then perform calculations iterativly to optimize the positions of the centroids.

How to determine the number of clusters?

Calute the mean square error of each points to the centroids. Then plot the MSE. The plot looks like the shape of elbow. We can apply "Elbow" method to select the optimal number of clusters. Before 4 cluster, the curve decrease sharply. After 4 clusters, the curve decreases slowly and smoother. We choose 4 clusers as the number of clusters.

Clustering VS. Classification

Classification and clustering are two methods to indentify the pattern in machine learning. Both of them are used to categorize objects into one or more classes based on their features.

Classfication:
Used for supervised learning.
Need Labeled data
Need training and testing dataset for verifying the model created.
More complex as compared to clustering
Ex: Logistic regression, Naive Bayes classifier, Support vector machines, etc.
Clustering:
Used for unsupervised learning
Need unlabeled data
No need of training and testing dataset
Less complex as compared to classification
Ex: K-means clustering algorithm, Fuzzy c-means clustering algorithm, etc.


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


Project:
This project will build K-means clustering from scratch, then implement it with the reduced workforcedataset. We will then implement sklearn's principle component and k-means clustering algorithms on the same dataset.

Preprocess the data by removing variables with zero variance

The next step is to select which features we want to use with logistic regression and standardize them.

then executes the algorithm calculates the distance from each feature vector to each centroid and assigns each datapoint to a centroid. It then updates the clusters and recalculates the centroids, and updates the assignment of datapoints until it reaches maximum iterations.

Considering plt.xlabel('MonthlyIncome')
plt.ylabel("YearsAtCompany")

then ran k means with 2 clusters, reports the centroids and graphs the color-coded results in a scatterplot.

**Using sklearn's functions**
we will create training and testing sets. Then we will use PCA to simplify the data.



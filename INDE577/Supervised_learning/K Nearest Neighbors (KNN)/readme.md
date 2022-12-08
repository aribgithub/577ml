
K-Nearest Neighbors
(KNN is a non-parametric classification method. It can be used for classification or regression problems.

In KNN, the distance between the test data and the training points is used to predict the correct class. Select the K number of points that are closest to the test data, and the KNN algorithm will calculate the probability that the training data belongs to the K number of classes and the class with the greatest probability will be selected. As for the regression problem, regression values are determined by the mean of the K selected training points.

The output depends on whether K-NN is used for classification or regression:

In K-NN classification, the output is a class membership. An object is classified by a plurality vote of its neighbors, with the object being assigned to the class most common among its k nearest neighbors (k is a positive integer, typically small). If k = 1, then the object is simply assigned to the class of that single nearest neighbor.
In K-NN regression, the output is the property value for the object. This value is the average of the values of k nearest neighbors.
K-NN is a type of classification where the function is only approximated locally and all computation is deferred until function evaluation. Since this algorithm relies on distance for classification, if the features represent different physical units or come in vastly different scales then normalizing the training data can improve its accuracy dramatically. The smaller the K, the more complex of the model.

![687474703a2f2f7265732e636c6f7564696e6172792e636f6d2f6479643931316b6d682f696d6167652f75706c6f61642f665f6175746f2c715f6175746f3a626573742f76313533313432343132352f4b4e4e5f66696e616c315f6962646d38612e706e67](https://user-images.githubusercontent.com/119718873/205557109-be625596-636b-4158-bea8-799406295a23.png)

**Project**:

This project will demonstrate an application of Decision Trees on the reduced workforce dataset dataset, first without principle component analysis, then adding it in for comparison.

Before we can create decision trees, we need to **pre-process** the data and encode labels. We will do this using sklearn's preprocessing package.

**First and foremost, we remove variables with zero variance**
we picked Job Level, Total Working Years, Years in Current Role, Years with Current Manager, and Percent Salary Hike to drop.

The next step is to select which features we want to use with decision trees and standardize them.


To **apply decision trees**, the data must be split into "**training"** and **"test"** data.

**Performance Analysis**
The next step is to conduct a performance analysis of the model. We do this by examining the confusion matrix and the Receiver Operating Characteristic (ROC) curve.

**Fit the PCA on the training set**







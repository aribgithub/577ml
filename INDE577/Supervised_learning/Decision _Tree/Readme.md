

A decision tree is a flowchart-like structure in which each internal node represents a "test" on an attribute (e.g. whether a coin flip comes up heads or tails), each branch represents the outcome of the test, and each leaf node represents a class label (decision taken after computing all attributes). The paths from root to leaf represent classification rules. In decision analysis, a decision tree and the closely related influence diagram are used as a visual and analytical decision support tool, where the expected values (or expected utility) of competing alternatives are calculated. A decision tree consists of three types of nodes:

Decision nodes – typically represented by squares
Chance nodes – typically represented by circles
End nodes – typically represented by triangles

![68747470733a2f2f616e6e616c797a696e2e66696c65732e776f726470726573732e636f6d2f323031362f30372f6465636973696f6e2d74726565732d6578616d706c652d6d756c7469706c652d63617465676f726965732d7475746f7269616c322e706e67](https://user-images.githubusercontent.com/119718873/205556212-d98607ae-e02a-436e-822c-539577b6d193.png)

**Project**:

This project will demonstrate an application of Decision Trees on the reduced workforce dataset dataset, first without principle component analysis, then adding it in for comparison.

Before we can create decision trees, we need to pre-process the data and encode labels. We will do this using sklearn's preprocessing package.

First, we remove variables with zero variance

we picked Job Level, Total Working Years, Years in Current Role, Years with Current Manager, and Percent Salary Hike to drop.

The next step is to select which features we want to use with decision trees and standardize them.


To apply decision trees, the data must be split into "**training"** and **"test"** data.

**Performance Analysis**
The next step is to conduct a performance analysis of the model. We do this by examining the confusion matrix and the Receiver Operating Characteristic (ROC) curve.

**Fit the PCA on the training set**

EWventually PCA made both decision trees slightly less accurate, and made the algorithm take slightly longer to run. 




Ensemble machine learning

A single algorithm may not make the perfect prediction for a given dataset. Machine learning algorithms have their limitations and producing a model with high accuracy is challenging. If we build and combine multiple models, the overall accuracy could get boosted.

Ensemble models is a machine learning approach to combine multiple other models in the prediction process. Those models are referred to as base estimators. It is a solution to overcome the following technical challenges of building a single estimator:

High variance: The model is very sensitive to the provided inputs to the learned features.

Low accuracy: One model or one algorithm to fit the entire training data might not be good enough to meet expectations.

Features noise and bias: The model relies heavily on one or a few features while making a prediction.

Ensemble learning combines several tree base algorithms which construct a better predictive performance than a single tree base algorithm. The main principle of ensemble model is that several weak learners combined together to form a strong learner resulting in an increasing accuracy model.

![68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f6d61782f313339362f312a75336163546363665a32485957696c67674f6d4643412e6a706567](https://user-images.githubusercontent.com/119718873/205553905-b920e186-ae88-4a91-9bc7-1d166632375e.jpeg)

Bagging

Another esemble learning method is bagging. Bagging is based on a bootstrapping sampling technique. Bootstrapping creates multiple sets of the original training data with replacement. Replacement enables the duplication of sample instances in a set. Each subset has the same equal size and can be used to train models in parallel.

Random Forest

Random Forest is an ensemble of Decision Trees, generally trained via the bagging method. The main difference between the decision tree algorithm and the random forest algorithm is that establishing root nodes and segregating nodes is done randomly in the latter. The random forest employs the bagging method to generate the required prediction.

![68747470733a2f2f7777772e746962636f2e636f6d2f73697465732f746962636f2f66696c65732f6d656469615f656e746974792f323032312d30352f72616e646f6d2d666f726573742d6469616772616d2e737667](https://user-images.githubusercontent.com/119718873/205555158-ac5a5234-069f-4224-82c4-5a32ad0b57fe.svg)

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





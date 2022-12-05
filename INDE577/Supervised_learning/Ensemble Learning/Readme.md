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

![68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f6d61782f313339362f312a75336163546363665a32485957696c67674f6d4643412e6a706567-2](https://user-images.githubusercontent.com/119718873/205555058-03c3d7cf-d6ea-4854-aaab-66d2a6a10c30.jpeg)

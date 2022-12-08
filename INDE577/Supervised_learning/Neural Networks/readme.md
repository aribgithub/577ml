Introduction

A multilayer perceptron (MLP) is a class of feedforward artificial neural network (ANN). The term MLP is used ambiguously, sometimes loosely to mean any feedforward ANN, sometimes strictly to refer to networks composed of multiple layers of perceptrons (with threshold activation); see § Terminology. Multilayer perceptrons are sometimes colloquially referred to as "vanilla" neural networks, especially when they have a single hidden layer. An MLP consists of at least three layers of nodes: an input layer, a hidden layer and an output layer. Except for the input nodes, each node is a neuron that uses a nonlinear activation function. MLP utilizes a supervised learning technique called backpropagation for training. Its multiple layers and non-linear activation distinguish MLP from a linear perceptron. It can distinguish data that is not linearly separable.

**Project**:

This project will demonstrate an application of Decision Trees on the reduced workforce dataset dataset, first without principle component analysis, then adding it in for comparison.

Before we can create decision trees, we need to pre-process the data and encode labels. We will do this using sklearn's preprocessing package.

**First and foremost, we remove variables with zero variance**
we picked Job Level, Total Working Years, Years in Current Role, Years with Current Manager, and Percent Salary Hike to drop.

The next step is to select which features we want to use with decision trees and standardize them.


To **apply decision trees**, the data must be split into "**training"** and **"test"** data.

**Performance Analysis**
The next step is to conduct a performance analysis of the model. We do this by examining the confusion matrix and the Receiver Operating Characteristic (ROC) curve.

**Fit the PCA on the training set**





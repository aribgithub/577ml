Introduction

A multilayer perceptron (MLP) is a class of feedforward artificial neural network (ANN). The term MLP is used ambiguously, sometimes loosely to mean any feedforward ANN, sometimes strictly to refer to networks composed of multiple layers of perceptrons (with threshold activation); see § Terminology. Multilayer perceptrons are sometimes colloquially referred to as "vanilla" neural networks, especially when they have a single hidden layer. An MLP consists of at least three layers of nodes: an input layer, a hidden layer and an output layer. Except for the input nodes, each node is a neuron that uses a nonlinear activation function. MLP utilizes a supervised learning technique called backpropagation for training. Its multiple layers and non-linear activation distinguish MLP from a linear perceptron. It can distinguish data that is not linearly separable.

Contents

In this notebook, we use MLP algorithm to train model to predict the condition of passengers survival according to the different characteristics of different passengers.

Dataset

The dataset called Titanic is from kaggle. The data has been split into two groups: training set (train.csv), test set (test.csv). The dataset contains few columns such as, whether passengers can survive, ticket class, sex, age in years, ticket number, passenger fare, cabin number.


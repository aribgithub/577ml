Gradient Descent

Gradient descent is an optimization algorithm to find a local minimum of a differentiable function. It is most often used to find coefficient values that minimize a cost function.
Imagine you are hiking down into a valley, and this is its topographical map (where lines that are closer together indicate the slope of the valley is steeper between them). In the case below, the valley gets less steep the lower you hike, meaning the reduced gradient correlates with a reduced slope and step size for the hiker.


![68747470733a2f2f692e696d6775722e636f6d2f786e5076456f6b2e676966](https://user-images.githubusercontent.com/119718873/205538561-9cf8c940-d581-403c-af20-6f0bfbc515d7.gif)




There are two main types of gradient descent, both of which are programmed from scratch in the accompanying notebook:
Batch Gradient Descent (aka vanilla gradient descent)
calculates the error for each example within the training dataset, but the model is only updated after all training examples have been updated
the whole process is called a "training epoch"

Advantages: model is computationally efficient, produces stable error gradient, and a stable convergence

Disadvantages: stable error gradient can sometimes result in sub-optimal convergence. It also requires the entire training set to be in memory and available to the algorithm

Stochastic Gradient Descent updates the parameters for each training example one by one
depending on the problem, this can make it faster than batch gradient descent

Advantage: frequent updates allow for a detailed rate of improvement

Disadvantage: frequent updates are more computationally expensive and can result in noisy gradients, which can result in an error graph with spikes rather than steady decrease
When there are one or more inputs you can use a process of optimizing the values of the coefficients by iteratively minimizing the error of the model on your training data.
Mean squared error is a common measure of performance:

![GradientDescentMultiAlpha](https://user-images.githubusercontent.com/119718873/205538650-86a7e698-2463-4019-8ce6-ccbc833bddf5.png)


Project
In this project, I will build a Gradient Descent model from scratch, using the gradient descent algorithm, by changing the learning rate and the number of iterations, to continuously reduce the value of the cost function, to find the most optimal linear equation.

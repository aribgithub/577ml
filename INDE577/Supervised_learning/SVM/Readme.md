![SVM](https://user-images.githubusercontent.com/119718873/205558249-0393fedf-b507-46da-8979-3339ac949211.png)



A Support Vector Machine (SVM) is a supervised learning model first developed at AT&T Bell Laboratories by Vladimir Vapnik. SVMs are based on statistical learning frameworks. An SVM algorithm builds a model that can separate data into binary classifications by drawing a line between the data. SVMs are incredibly powerful and can be used in classification, regression, and outlier detection tasks. Classification SVMs have the following variations:

Linear SVM

attempts separates the data with a straight line
Hard-Margin
If the data is linearly separable, a line can be drawn such that it maximizes the distance between itself and the nearest datapoints on either side.
All instances must be classified on the appropriate side of the line (i.e. 
w
T
x
−
b
≥
1
 produces a label of 1)
Soft-Margin
Allows a balance between "street" violations where a feature vector falls within the established margins of the hyperplane
Less sensitive to outliers which would force the hard margin to compensate for. When using the Sci-kit Learn SVM module, this is the C parameter
Nonlinear SVM

allows a nonlinear function to separate the dataset, called a Kernel
Polynomial Kernel
separates the data using a polynomial function
Gaussian Radial Basis Function (RBF)
ϕ
y
(
x
,
l
)
=
e
x
p
(
−
γ
|
x
−
l
|
2
)
This is a bell-shaped function and can provide great flexibility in separating the data
Kernel Trick

We can implement polynomial functions via a kernel so that we do not actually have to waste resources on computing high order polynomials. This increases the feasibility of calculating high order polynomials in large datasets where otherwise the calculations would consume too many resources and time.

Linear: 
K
(
a
,
b
)
=
a
T
b
Polynomial: 
K
(
a
,
b
)
=
(
γ
a
T
b
+
r
)
d
Gaussian RBF: 
K
(
a
,
b
)
=
e
x
p
(
−
γ
|
a
−
b
|
2
)
Sigmoid: 
K
(
a
,
b
)
=
t
a
n
h
(
γ
a
T
b
+
r
)
The benefits of an SVM are:

works well when there is a clear margin of separation
effective in high dimensions
relatively memory efficient
The issues with an SVM are:

not suitable for large datasets
does not perform well when data is noisy
no probabilistic explanation for the classification
SVMs are incredibly powerful, however care needs to be taken when selecting data and training the model. Outliers and noisy data can cause the model to be ineffective. In SVM Regression, instead of the hyper plane forming a basis for classification, it guides the regression line subject to a minimization and constraints.

Prediction

A prediction with an SVM is made using the central line of the hyperplane. The hyperplane is create by minimizing the following:

$\frac{1}{2}|w|^2 + C\sum_{i=1}^N(\xi_i + \xi_i^)\$ $subject to\$ $y_i - wx_i-b\leq\varepsilon+\xi_i\$ $wx_i+b - y_i\leq\varepsilon+\xi_i^\$ 
ξ
i
,
ξ
i
∗
≥
0

Predict

y
^
=
∑
i
=
1
n
(
a
i
−
a
i
∗
(
ϕ
(
x
i
)
,
ϕ
(
x
)
)
+
b
)


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





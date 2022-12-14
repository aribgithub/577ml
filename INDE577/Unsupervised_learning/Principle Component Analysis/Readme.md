Principal Component Analysis, or PCA, is a dimensionality-reduction method that is often used to reduce the dimensionality of large data sets, by transforming a large set of variables into a smaller one that still contains most of the information in the large set.

Reducing the number of variables of a data set naturally comes at the expense of accuracy, but the trick in dimensionality reduction is to trade a little accuracy for simplicity. Because smaller data sets are easier to explore and visualize and make analyzing data much easier and faster for machine learning algorithms without extraneous variables to process. Geometrically speaking, principal components represent the directions of the data that explain a maximal amount of variance, that is to say, the lines that capture most information of the data.

![687474703a2f2f6f7264696e6174696f6e2e6f6b73746174652e6564752f337661727063612e6a7067](https://user-images.githubusercontent.com/119718873/206083100-2a2975c9-eec5-4c88-b0be-0283a216b378.jpeg)


**Project**:

This notebook will implement Principle Component Analysis with the IBMEmployeeAttrition dataset.

Pre-Processing

Before we can run PCA, we need to pre-process the data and encode labels.

Split into Train and Test data

To apply PCA, the data must be split into "training" and "test" data.


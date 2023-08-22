# PCA-Driven_Optdigits_Classification

This repository focuses on solving the problem of dimension reduction and classification on the Optdigits dataset using machine learning techniques. The Optdigits dataset is provided in separate training and test files (optdigits train.txt and optdigits test.txt), where each row represents an image vector, and the last column denotes the digit class.

*KNN Classifier without PCA*

This section implements the k-Nearest Neighbor (KNN) classifier, developed in Homework 1, to classify the Optdigits dataset. The KNN algorithm is applied with different values of k (1, 3, 5, 7), and the error rate on the test set is printed for each k.

*PCA Implementation*

In this part, a custom implementation of Principal Component Analysis (PCA) is developed. PCA is applied to the Optdigits training data to reduce its dimensionality while retaining essential information.

*KNN Classifier with PCA*

This section begins by generating a proportion of variance plot, illustrating the explained variance by each principal component. The minimum number of eigenvectors (K) required to explain at least 90% of the variance is determined and shown in the report. The training and test data are projected onto the K principal components, and KNN is performed on the projected data for various values of k (1, 3, 5, 7). The error rate on the test set is reported for each k.

*Component Plotting*

Here, the training and test data are projected onto a 2D space using the first two principal components. A visualization is created in which all samples are plotted in the projected space, and each data point is labeled with its corresponding digit class using distinct colors for each of the 10 types of digits. This visualization aims to provide insight into the distribution of the data in the reduced space.

Feel free to explore the code, experiment with different parameter values, and contribute to the repository's growth by improving existing implementations and documentation. Your engagement and enhancements are highly valued and can further enrich the repository's resources!

# Data-Mining
fptminer.java: FP-tree algorithm for generating all association rules whose support is greater than a user-supplied minimum support and whose confidence is greater than a user supplied minimum confidence.

kcluster.java: clustering algorithms based on k-means for clustering objects corresponding to sparse high dimensional vectors. The project consists of multiple components that involve getting the dataset, selecting the subset to cluster, pre-processing the dataset to convert it into a sparse representation, clustering the dataset, and evaluating the quality of the clustering solution. Dataset: "Reuters-21578 Text Categorization Collection Data Set"
preprocess.py:
1.Eliminate any non-ascii characters.
2.Change the character case to lower-case.
3.Replace any non alphanumeric characters with space.
4.Split the text into tokens, using space as the delimiter.
5.Eliminate any tokens that contain only digits.
6.Eliminate any tokens from the stop list
7.Obtain the stem of each token using Porter's stemming algorithm
8.Eliminate any tokens that occur less than 5 times.

Various classifiers for hand-written digit recognition.  The project consists of multiple components that involve using different representations for the dataset, implementing three different classifier models, assessing the performance of each classifier with the different representations, and analyzing some of the models that were estimated. 
knn.java: K Nearest Neighbor
regression.java: Ridge Regression
nn_regression.java: special case of the Ridge Regression approach in which you restrict your model to learn a non-negative regression. Plotted using PlotImage.py

# Data-Mining
fptminer.java: FP-tree algorithm for generating all association rules whose support is greater than a user-supplied minimum support and whose confidence is greater than a user supplied minimum confidence.

kcluster.java: clustering algorithms based on k-means for clustering objects corresponding to sparse high dimensional vectors. The project consists of multiple components that involve getting the dataset, selecting the subset to cluster, pre-processing the dataset to convert it into a sparse representation, clustering the dataset, and evaluating the quality of the clustering solution. Dataset: "Reuters-21578 Text Categorization Collection Data Set"<br/>
preprocess.py:<br/>
1.Eliminate any non-ascii characters.<br/>
2.Change the character case to lower-case.<br/>
3.Replace any non alphanumeric characters with space.<br/>
4.Split the text into tokens, using space as the delimiter.<br/>
5.Eliminate any tokens that contain only digits.<br/>
6.Eliminate any tokens from the stop list<br/>
7.Obtain the stem of each token using Porter's stemming algorithm<br/>
8.Eliminate any tokens that occur less than 5 times.<br/>

Various classifiers for hand-written digit recognition.  The project consists of multiple components that involve using different representations for the dataset, implementing three different classifier models, assessing the performance of each classifier with the different representations, and analyzing some of the models that were estimated.<br/>
knn.java: K Nearest Neighbor<br/>
regression.java: Ridge Regression<br/>
nn_regression.java: special case of the Ridge Regression approach in which you restrict your model to learn a non-negative regression. Plotted using PlotImage.py

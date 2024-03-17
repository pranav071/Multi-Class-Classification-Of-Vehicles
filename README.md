# Multi-Class-Classification-Of-Vehicles
This is a Multi-Class Classification Of Vehicles using Machine Learning techniques and used different models for best accuracy.The 2-layer neural network works best, followed by logistic regression and SVM with a linear kernel. Random forest and K-NN comes next followed by 1-layer neural network and SVM with the rbf kernel.

Even after improving our decision tree by finding a suitable PCA using grid search, it does not perform as well as the models mentioned above. Probably using a cross validated grid search with varying PCA and max_depth values might provide better results.

As expected, our convolutional neural network built from scratch using the raw images as input performs significantly worst. Compared to the other models which has access to pre-existing high level features from a complex CNN trained with a large dataset, our CNN uses a simple network with a small training set.

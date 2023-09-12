# Minimum Distance Classifier

The Minimum Distance Classifier is a type of supervised machine learning algorithm. At its core, it classifies a data point based on its proximity to the mean or centroid of predefined classes. During the training phase, the algorithm computes the centroid for each class using the feature vectors of the training samples. When classifying a new sample, the algorithm calculates the distance from the sample to each centroid and assigns the sample to the class with the nearest centroid.

The most common distance measure used is the Euclidean distance, although other metrics can be used as well. Due to its simplicity and speed, the Minimum Distance Classifier is particularly useful when computational resources are limited or a rapid decision is required.


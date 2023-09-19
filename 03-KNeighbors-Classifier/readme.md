# K-Nearest Neighbors (KNN)

## What is k-NN?
k-NN is a simple, supervised machine learning algorithm that classifies data points based on their 'k' closest neighbors in a dataset.

## How Does it Work?
Given a new data point, k-NN:

1. Calculates the distance (e.g., Euclidean) between the new point and every other point in the dataset.
2. Selects the 'k' closest data points (neighbors).
3. Assigns the class of the new point based on the majority class among its 'k' neighbors.
   
## Difference between k-NN and k-Means?
* **k-NN**: Supervised learning algorithm used for classification (and sometimes regression). It relies on labeled input data.
* **k-Means**: Unsupervised learning algorithm used for clustering data points into 'k' number of clusters. It doesn't use labeled data.

## What is a Decision Boundary?
It's a surface that separates data points of different classes. In the context of k-NN, the decision boundary can be complex and is determined by the data distribution and the value of 'k'.

## Where to Use k-NN?
k-NN is useful when:

* Data has a clear spatial separation.
* There's a need for simple interpretability.
* A complex model isn't necessary.
  
## Applications in Real Life:

* Image or handwriting recognition.
* Recommendation systems (e.g., suggesting similar products or movies).
* Medical diagnosis (identifying diseases based on symptoms).

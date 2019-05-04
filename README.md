# Credit-Card-Fraud-Detection
We have implemented the two major algorithms namely, 

1. A local outlier factor to calculate anomaly scores.

  The local outlier factor is based on a concept of a local density,where locality is given by k nearest neighbors, whose distance is used   to estimate the density.By comparing the local density of an object to the local densities of its neighbors, one canidentify regions of     similar density and points that have a substantially lower density than theirneighbors. These are considered to be outliers.
2. Isolation forest algorithm.

  The algorithm is based on the fact that anomalies are data points that are few and different. As
  a result of these properties, anomalies are susceptible to a mechanism called isolation.
  This algorithm is a method with a low linear time complexity and a small memory requirement. It
  builds a good performing model with a small number of trees using small sub-samples of fixed
  size, regardless of the size of a data set


Link for the dataset:- https://www.kaggle.com/mlg-ulb/creditcardfraud

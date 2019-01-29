#Objective:
So, we have given the IRIS dataset and The iris data set consists of 50 samples from each of three species of Iris flower (Iris setosa, Iris virginica and Iris versicolor).

Four features were measured from each sample: the length and the width of the sepals and petals, in centimetres (iris.data).

## Task:
Reduce dimension from 4-d to 2-d and perform clustering to distinguish the 3 species.

# What is Principal Component Analysis?

The main idea of principal component analysis (PCA) is to reduce the dimensionality of a data set consisting of many variables co-related with each other, either heavily or lightly, while retaining the variation and useful information present in the dataset, up to the maximum extent.

It's the one of the most powerful technique for dimension reduction.

## Methods of dimension reduction:
Well, there are two main methods of dimension reduciton>>

1. Feature Selection:
Reducing the dimension by determining a subset of the feature space.

2. Feature Extraction:
Selecting a smaller new set of features from the original set. This includes PCA, kernel PCA, Latent Semantic Analysis.

```

Goal of use PCA:

Reducing the dimenslity of data but retaining as much of it's varience.

```

## Why reduce the dimensions of the data:

As the dimensions of data increases, the difficulty to visualize it and perform computations on it also increases. 




## How does PCA work -

PCA finds a new set of dimensions (or a set of basis of views) such that all the dimensions are orthogonal (and hence linearly independent) and ranked according to the variance of data along them. It means more important principle
axis occurs first. (more important = more variance/more spread out data)

## So, how to reduce the dimensions of a data-

```
* Remove the redundant dimensions
* Only keep the most important dimensions
```

## Required Tool:

Sklearn, matplotlib

```
Pip install sklearn
pip install matplotlib

```

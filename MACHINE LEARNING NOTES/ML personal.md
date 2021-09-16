# MACHINE LEARNING

turing test

A computer program is said to learn from experience E with respect to some class of tasks T and performance measure P if its performace at tasks in T, as measured by P, improves with experience E.

data mining



examples:

image recognition

recognise handwriting by segmenting single letter into smaller images



spam filter detection based on what kind of words they contain

Libraries

numpy and pandas are mathematical libs. matplotlib





There are 3 main ML approaches :

> supervised learning
>
> unsupervised learning
>
> reinforcement learning





commonly used learning algo

> logic regression
>
> linear regression
>
> decision trees
>
> random forests
>
> knn



the gradient vector (∇) is always in the direction of greatest increase of slope



adding gaussian noise : take a normal distribution curve, and add some random noise

```python
x = 2 * np.random.rand(100,1)
y = 4 +3 * x +np.random.randn(100,1)
```



clustering

Segregate Datasets into various groups, on basis of having similarities





K means clustering (pseudo code)

```
1) specify number k of clusters to assign

2) randomly initialise k centroids

3) repeat

4) expectation

```

residual sum of squares (RSS)



how to determine number of clusters?

- elbow method (rough estimation only)
- run k-means clustering
- increment number of clusters
- record RSS



silhouette coefficient


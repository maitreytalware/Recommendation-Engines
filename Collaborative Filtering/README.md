# Collaborative Filtering
Collaborative filtering is a method of making recommendations based only on the interactions between users and items.

Example:

We know that Pradeep and Mike both have similar tastes in books. If we recommend a book Mike has read to Pradeep, this is an example of **Collaborative filtering based recommendation**


<img src='../Images/cbr.png'></img>

<a href ='https://towardsdatascience.com/brief-on-recommender-systems-b86a1068a4dd'>Image reference</a>


## 1. Types Collaborative Filtering
There are two main ways to implement collaborative filtering:

1. **Model Based Collaborative Filtering**
2. **Neighborhood Based Collaborative Filtering**

Here we will cover Neighborhood Based Collaborative Filtering, which is used to identify items or users that are "neighbors" with one another.

## 2. Common metrics used to find closest neighbors

There are a number of ways we might go about finding an individual's closest neighbors
1. **Similarity Based Measures**
    1. Pearson's correlation coefficient
    2. Spearman's correlation coefficient
    3. Kendall's Tau
2. **Distance Based Measures**
    1. Euclidean Distance
    2. Manhattan Distance
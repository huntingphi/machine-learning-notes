# CSC3022H: Machine Learning

## Introduction

### Sylalabus

**Introduction: Basic concepts**
**Unsupervised Learning**
  - Clustering, Hierarchial clustering, K-means, EC, NE.
  - PCA, ICA, SOM, ART

**Supervised Learning**
  - ANNs. Back propagation
  - Generative Learning algorithms. Naive Bayes.
  - Concept Learning

**Reinforcement Learning**
  - Q-learning. Policy and Value function approximation

### Machine Learning Types

1. Supervised Learning:
  1. Classification
  2. Regression
2. Unsupervised Learning
  1. Clustering
  2. Dimensionality reduction
3. Reinforcement Learning
  1. Value and policy iteration
  2. Q Learning
  
## Unsupervised Learning
In supervised learning, data is in the form <x,y>, where the y=f(x). The goal is to approximate f well.
In unsupervised learning, the data just contains <x> and the goal is to *summarize* or find *patterns* or *structure* in the data.
Examples of this are clustering (eg partitioning, hierarchial clustering), density estimation, dimensionality reduction (eg visualization, compression, pre-processing)
  
 Pre-processing for supervised learning is often used in data analysis
 
 ### Clustering
 
 Clustering is grouping similar objects together.
 This can be to:
 - Classify data, or to detect outliers
 - Simplify data for further analysis or learning
 - Visualize data, in the case of dimensionality reduction
 
 Clustering algorithms:
 - Use some notion of distance between objects
 - Use explicit or implicit criterion defining what a good cluster is
 - Heuristically optimise criterion to get good clusters
 
 #### K-means Clustering
 
 K-means clustering is one of the most commonly-used clustering algorithms. Its easy to implement and quick to run. It assumes objects (instances) to be clustered are n-dimensional vectors, x<sub>i</sub> (real valued data). It uses a similarity distance metric such as Euclidian distance. The goal is to partition the data into K disjoint subsets.
 
 **Inputs**
 1. A set of n-dimensional real vectors {x<sub>1</sub>,x<sub>2</sub>,x<sub>3</sub>,...,x<sub>m</sub>}
 2. K, the disired number of clusters.
 
 **Output**
 1. A mapping of the vectors into K clusters (disjoint subsets), C: {1,...,m} → {1,...,K}
 
 **Algorithm**
 1. Initialize C randomly.
 2. do
  1. Compute the *centroid* of each



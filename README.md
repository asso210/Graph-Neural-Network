# Graph-Neural-Network
In this repository we present an implementation of Graph Neural Networks - GNNs for astroparticle application. In particular we will show how is possible using this new paradigm of Neural Networks to process informations which don't present an euclidean structure, so for that data in which convolution or other conventional techniques are not suitable. 
To implent GNN we use [Spektral](https://github.com/danielegrattarola/spektral#readme) which is a Python library for graph deep learning, based on the Keras API and TensorFlow 2. 

## What is a graph?

A graph is defined as G = (V,E,A) where V is a set of nodes (or vertex), E is a set of edges (or links) and A is the adjacency matrix. An example of graph is shown in the figure below

![Example of graph](./images/graph.png)

A graph can be directed if the edges have a specific direction or undirected if edges don't have any direction. 
A graph can be weighted if in the edges is given a numerical weight or unweighted if each weight in the link is 1 and equal for all the links. 

## How does a GNN work?

GNN is a class of artificial neural network for processing data that can be represented as graphs.


## Why GNNs?



## Installation 

To run code it's essential that you've already installed [Keras](https://github.com/keras-team/keras) and [TensorFlow](https://github.com/tensorflow/tensorflow). To install Spektral the best way is from PyPi

```python
pip install spektral
```
Other libraries present in the code are 

```python
pip install pandas, statistics, numpy, sklearn, seaborn, matplotlib
```

To visualize graph we use the library [Netowrkx](https://github.com/networkx/networkx)

```python
pip install networkx
```

## Dataset

## Getting started 



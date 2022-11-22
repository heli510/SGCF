# SGCF

A implementation of paper “Simplifying Graph-based Collaborative Filtering for Recommendation” Our code is about to be presented, Stay tuned :)

## Abstract
Graph Convolutional Networks (GCNs) are a popular type of machine learning models that use multiple layers of convolutional aggregation operations and non-linear activations to represent data. Recent studies apply GCNs to Collaborative Filtering (CF)-based recommender systems (RSs) by modeling user-item interactions as a bipartite graph and achieve superior performance. However, these models face difficulty in training with non-linear activations on large graphs. Besides, most GCN-based models could not model deeper layers due to the over-smoothing effect with the graph convolution operation. In this paper, we improve the GCN-based CF models from two aspects. First, we remove non-linearities to enhance recommendation performance, which is consistent with the theories in simple graph convolutional networks. Second, we obtain the initialization of the embedding for each node in the graph by computing the network embedding on the condensed graph, which alleviates the over smoothing problem in graph convolution aggregation operation with sparse interaction data. The proposed model is a linear model that is easy to train, scalable to large datasets, and shown to yield better efficiency and effectiveness on four real datasets.

## Cite


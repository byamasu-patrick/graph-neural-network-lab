# Graph Neural Network Lab

A hands-on exploration of Graph Neural Networks through implementations from first principles. This repository documents my journey into graph-based deep learning by building and experimenting with foundational and advanced GNN architectures.

The goal is to understand how graph neural networks learn representations, aggregate information from graph structures, and solve problems involving relational data.

## Implemented Architectures

### Graph Neural Network Foundations

* Graph representation and processing
* Adjacency matrices
* Degree matrices
* Graph normalization
* Message passing mechanisms
* Node representation learning

### Graph Convolutional Network (GCN)

Implementation of the Graph Convolutional Network introduced by Thomas Kipf and Max Welling.

Key concepts:

* Spectral graph convolution
* Neighborhood aggregation
* Graph normalization
* Semi-supervised node classification

### Graph Attention Network (GAT)

Implementation of Graph Attention Networks introduced by Petar Veličković and collaborators.

Key concepts:

* Attention-based message passing
* Learning adaptive neighbor importance
* Multi-head attention mechanisms

### GraphSAGE

Implementation of GraphSAGE introduced by William Hamilton, Rex Ying, and Jure Leskovec.

Key concepts:

* Neighborhood sampling
* Aggregation functions
* Scalable graph representation learning

### Additional Architectures

Future implementations will include:

* Graph Isomorphism Networks (GIN)
* Temporal Graph Neural Networks (TGNNs)
* Heterogeneous Graph Neural Networks
* Graph Transformers
* Advanced graph representation learning methods

## Motivation

Graph Neural Networks provide a powerful framework for learning from structured data where relationships between entities are important. This repository serves as both a learning resource and an experimental environment for understanding the foundations behind modern graph-based AI systems.

The long-term goal is to explore efficient graph representation learning techniques for applications in areas such as multi-agent systems, reinforcement learning, and scalable artificial intelligence.

## Technologies

* Python
* PyTorch
* NumPy
* NetworkX
* Matplotlib

## Repository Structure

```
graph-neural-lab/
│
├── notebooks/
│   ├── gnn_from_scratch.ipynb
│   ├── gcn.ipynb
│   ├── gat.ipynb
│   └── graphsage.ipynb
│
├── src/
│   ├── layers/
│   ├── models/
│   └── utils/
│
├── experiments/
│
├── datasets/
│
├── README.md
└── requirements.txt
```

## References

* Kipf, T. N., & Welling, M. (2017). Semi-Supervised Classification with Graph Convolutional Networks.
* Veličković, P., et al. (2018). Graph Attention Networks.
* Hamilton, W., Ying, R., & Leskovec, J. (2017). Inductive Representation Learning on Large Graphs.

## Future Directions

* Benchmarking different GNN architectures
* Exploring graph representation compression
* Applying GNNs to multi-agent reinforcement learning environments
* Investigating efficient communication and decentralized learning with graph neural networks

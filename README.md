# Sparse_Topology_Distance
This repo contains code accompaning the paper, Topological Insights into Sparse Neural Networks (Liu et al., ECMLPKDD 2020). It includes code and topology example for measuring the sparse topology distance between two sparse neural networks. The sparse topology used in this paper refers to the topology of a subset of the neural graph (a fraction of parameters) that can reparameterize the whole network. And the sparse topology distance measured in this paper refers to the distance between two subsets of the neural graph. 

## Requirements

This code requires the following:

Python 3.*

Sscipy 1.4.1

matplotlib 3.1.3

## Code Structure and Usage

The repo provide an example implementation of NNSTD, a method to measure the distance between the graphs spanned over the network weights.

The main script is sparse_topology_distance.py which contains the code to compare different sparse topologies. 

We upload the topologies used to reproduce the results of Figure 4 in the original paper in the folder topo/. 




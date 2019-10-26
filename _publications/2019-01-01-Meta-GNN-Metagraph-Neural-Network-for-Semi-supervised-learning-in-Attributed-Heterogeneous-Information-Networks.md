---
title: "Meta-GNN: Metagraph Neural Network for Semi-supervised learning in Attributed Heterogeneous Information Networks"
collection: publications
permalink: /publication/2019-01-01-Meta-GNN-Metagraph-Neural-Network-for-Semi-supervised-learning-in-Attributed-Heterogeneous-Information-Networks
type: conference
date: 2019-01-01
venue: 'IEEE/ACM 2019 International Conference on Advances in Social Networks Analysis and Mining, ASONAM 2019, Vancouver, Canada, August 27-30, 2019'
paperurl: '../files/Meta-GNN-ASONAM2019.pdf'
authors: '<strong>Aravind Sankar</strong>, Xinyang Zhang, Kevin Chang'
url: 'https://dx.doi.org/10.1145/3341161.3342859'
abstract: 'Heterogeneous Information Networks (HINs) comprise nodes of different types inter-connected through diverse semantic relationships. In many real-world applications, nodes in information networks are often associated with additional attributes, resulting in Attributed HINs (or AHINs). In this paper, we study semi-supervised learning (SSL) on AHINs to classify nodes based on their structure, node types and attributes, given limited supervision. Recently, Graph Convolutional Networks (GCNs) have achieved impressive results in several graph-based SSL tasks. However, they operate on homogeneous networks, while being completely agnostic to the semantics of typed nodes and relationships in real-world HINs. In this paper, we seek to bridge the gap between semanticrich HINs and the neighborhood aggregation paradigm of graph neural networks, to generalize GCNs through metagraph semantics. We propose a novel metagraph convolution operation to extract features from local metagraph-structured neighborhoods, thus capturing semantic higher-order relationships in AHINs. Our proposed neural architecture Meta-GNN extracts features of diverse semantics by utilizing multiple metagraphs, and employs a novel metagraph-attention module to learn personalized metagraph preferences for each node. Our semi-supervised node classification experiments on multiple real-world AHIN datasets indicate significant performance gains of 6% Micro-F1 on average over state-of-the-art AHIN baselines. Visualizations on metagraph attention weights yield interpretable insights into their relative task-specific importance.'
code: https://github.com/aravindsankar28/Meta-GNN
---

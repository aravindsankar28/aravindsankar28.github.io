---
title: "Beyond Localized Graph Neural Networks: An Attributed Motif Regularization Framework"
collection: publications
permalink: /publication/2020-01-01-Beyond-Localized-Graph-Neural-Networks-An-Attributed-Motif-Regularization-Framework
type: conference
date: 2020-11-01
venue: '2020 IEEE International Conference on Data Mining (ICDM)'
paperurl: '../files/InfoMotif-ICDM2020.pdf'
authors: 'Aravind Sankar, Junting Wang, Adit Krishnan, Hari Sundaram'
url: 'https://arxiv.org/pdf/2009.05197.pdf'
abstract: 'We present InfoMotif, a new semi-supervised, motif-regularized, learning framework over graphs. We overcome two key limitations of message passing in popular graph neural networks (GNNs): localization (a k-layer GNN cannot utilize features outside the k-hop neighborhood of the labeled training nodes) and over-smoothed (structurally indistinguishable) representations. We propose the concept of attributed structural roles of nodes based on their occurrence in different network motifs, independent of network proximity. Two nodes share attributed structural roles if they participate in topologically similar motif instances over co-varying sets of attributes. Further, InfoMotif achieves architecture independence by regularizing the node representations of arbitrary GNNs via mutual information maximization. Our training curriculum dynamically prioritizes multiple motifs in the learning process without relying on distributional assumptions in the underlying graph or the learning task. We integrate three state-of-the-art GNNs in our framework, to show significant gains (3-10% accuracy) across six diverse, real-world datasets. We see stronger gains for nodes with sparse training labels and diverse attributes in local neighborhood structures.'
code: https://github.com/CrowdDynamicsLab/InfoMotif
---

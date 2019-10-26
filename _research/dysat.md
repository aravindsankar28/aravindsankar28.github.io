---
title: "Dynamic Graph Representation Learning"
collection: research
#permalink:
#venue: "Indian Institute of Technology, Madras, Computer Science and Engineering"
date: 2019-08-08
img_link: dysat_arch.png
authors: Aravind Sankar, Yanhong Wu, Wei Zhang and Hao Yang.
venue: ICLR Representation Learning on Graphs and Manifolds Workshop
#semester: Fall 2015
#location: "Chennai, India"
---
We examine representation learning on dynamic graphs described by a sequence of graph snapshots from
different time steps.
As dynamic graphs usually have periodical patterns such as
recurrent links or communities, we propose to leverage attention mechanisms to capture the most relevant historical information for representation learning.
We present a neural architecture named Dynamic Self-Attention Network (DySAT), that employs self-attention along two dimensions: structural neighborhoods and temporal dynamics, to compute dynamic node representations.
In comparison to state-of-the-art recurrent neural methods for modeling temporal
graph evolution, dynamic self-attention is efficient, while achieving
consistently superior performance.
Our extensive experiments on two graph classes: communication networks and
bipartite rating networks, demonstrate significant
performance gains for DySAT over several state-of-the-art graph embedding
baselines, in both single and multi-step link prediction tasks.

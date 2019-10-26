---
title: "RASE: Relationship Aware Social Embedding"
collection: publications
permalink: /publication/2019-01-01-RASE-Relationship-Aware-Social-Embedding
type: conference
date: 2019-01-01
venue: 'International Joint Conference on Neural Networks, IJCNN 2019 Budapest, Hungary, July 14-19, 2019'
paperurl: '../files/RASE-IJCNN2019.pdf'
authors: '<strong>Aravind Sankar</strong>, Adit Krishnan, Zongjian He, Carl Yang'
url: 'https://doi.org/10.1109/IJCNN.2019.8852147'
abstract: 'This paper studies the problem of learning latent representations or embeddings for users in social networks, by leveraging relationship semantics associated with each link. User embeddings are low-dimensional vector-space representations designed to preserve structural proximity indicated by the pairwise relationships. In social networks, the closeness (or proximity) between pairs of users is very different w.r.t. multiple social relationships and thus cannot be represented accurately using a single embedding space. Furthermore, social networks pose a unique challenge of relationship label sparsity that precludes the application of knowledge-graph embedding techniques.In this paper, we associate each observed link with multiple relationship types through relationship weights and learn projection matrices for each relationship type to model the social distance (or proximity) between users specific to each relationship. We propose a novel two-step mutual enhancement framework to iteratively (a) learn user embeddings preserving relationship-specific proximity, and (b) link-relationship weights capturing the role of each link in multiple relationship types. The first step learns user embeddings optimizing relationship-specific proximity, while fixing the relationship weights (or roles) for each link. In the second step, the user embeddings and corresponding projection matrices are assumed to be fixed, while the link-relationship weights are learned. We demonstrate that the relationship-aware user embeddings learned through this mutual enhancement framework, are more effective in representing the users and outperform representative baseline techniques in multi-label classification and relationship prediction tasks.'
---

---
title: "GroupIM: A Mutual Information Maximization Framework for Neural Group Recommendation"
collection: publications
permalink: /publication/2020-01-01-GroupIM-A-Mutual-Information-Maximization-Framework-for-Neural-Group-Recommendation
type: conference
date: 2020-07-01
venue: 'International ACM SIGIR Conference on Research and Development in Information Retrieval, SIGIR 2020, July 25-30, 2020'
paperurl: '../files/GroupIM-SIGIR2020.pdf'
authors: '<strong>Aravind Sankar</strong>, Yanhong Wu, Yuhang Wu, Wei Zhang, Hao Yang, Hari Sundaram'
url: 'https://arxiv.org/abs/2006.03736'
abstract: 'We study the problem of making item recommendations to ephemeral groups, which comprise users with limited or no historical activities together. Existing studies target persistent groups with substantial activity history, while ephemeral groups lack historical interactions. To overcome group interaction sparsity, we propose data-driven regularization strategies to exploit both the preference covariance amongst users who are in the same group, as well as the contextual relevance of users&apos; individual preferences to each group. We make two contributions. First, we present a recommender architecture-agnostic framework GroupIM that can integrate arbitrary neural preference encoders and aggregators for ephemeral group recommendation. Second, we regularize the user-group latent space to overcome group interaction sparsity by: maximizing mutual information between representations of groups and group members; and dynamically prioritizing the preferences of highly informative members through contextual preference weighting. Our experimental results on several real-world datasets indicate significant performance improvements (31-62% relative NDCG@20) over state-of-the-art group recommendation techniques.'
code: https://github.com/CrowdDynamicsLab/GroupIM
---

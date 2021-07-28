---
title: "ProtoCF: Prototypical Collaborative Filtering for Few-shot Recommendation"
collection: publications
permalink: /publication/2021-01-01-ProtoCF-Prototypical-Collaborative-Filtering-for-Few-shot-Recommendation
date: 2021-07-01
type: conference
venue: 'RecSys 2021: Fifteenth ACM Conference on Recommender Systems, Virtual Event, Brazil, September 22-26, 2020'
paperurl: '../files/ProtoCF-RecSys2021.pdf'
authors: '<strong>Aravind Sankar</strong>, Junting Wang, Adit Krishnan, Hari Sundaram'
url: 'https://doi.org/10.1145/3472456.3473511'
abstract: 'In recent times, deep learning methods have supplanted conventional collaborative filtering approaches as the backbone of modern recommender systems. However, their gains are skewed towards popular items with a drastic performance drop for the vast collection of long-tail items with sparse interactions. Moreover, we empirically show that prior neural recommenders lack the resolution power to accurately rank relevant items within the long-tail. In this paper, we formulate long-tail item recommendations as a few-shot learning problem of learning-to-recommend few-shot items with very few interactions.We propose a novel meta-learning framework ProtoCF that learns-to-compose robust prototype representations for few-shot items. ProtoCF utilizes episodic few-shot learning to extract meta-knowledge across a collection of diverse meta-training tasks designed to mimic item ranking within the tail. To further enhance discriminative power, we propose a novel architecture-agnostic technique based on knowledge distillation to extract, relate, and transfer knowledge from neural base recommenders. Our experimental results demonstrate that ProtoCF consistently outperforms state-of-art approaches on overall recommendation (by 5% Recall@50) while achieving significant gains (of 60-80% Recall@50) for tail items with less than 20 interactions.'
code: https://github.com/aravindsankar28/ProtoCF
---

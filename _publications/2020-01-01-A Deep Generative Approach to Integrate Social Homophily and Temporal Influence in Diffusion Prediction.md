---
title: "A Deep Generative Approach to Integrate Social Homophily and Temporal Influence in Diffusion Prediction"
collection: publications
permalink: /publication/2020-01-01-A-Deep-Generative-Approach-to-Integrate-Social-Homophily-and-Temporal-Influence-in-Diffusion-Prediction
date: 2020-01-01
venue: 'International Conference on Web Search and Data Mining, WSDM 2020, Houston, TX, February 3-7, 2020'
authors: '<strong>Aravind Sankar</strong>, Xinyang Zhang, Adit Krishnan, Jiawei Han'
abstract: 'Recent years have witnessed tremendous interest in understanding and predicting the spread or diffusion of information on social media platforms such as Twitter, Facebook, etc. While early methods assume pre-defined propagation hypotheses, contemporary techniques adopt a data-driven view to learn diffusion models from collections of observed cascades. Recent diffusion prediction methods primarily exploit the sequential order of influenced users by projecting diffusion cascades onto their local social neighborhoods. However, this fails to capture global social structures that do not explicitly manifest in any of the cascades, resulting in poor characterization of inactive users with limited historical interactions.

In this paper, we present a novel Coattentive Variational Graph autoEncoder (CoVaGE) to jointly embed social homophily and temporal influence through proximity-preserving social and position-encoded temporal latent variables. Given a sequence of seed user activations, CoVaGE uses a novel co-attentive fusion network that jointly attends over their social and temporal variables to retrieve the set of all influenced users. Our framework readily admits a multitude of graph neural networks modeling social network proximity. We conduct extensive experiments on multiple real-world social network datasets, including Digg, Weibo and Stack-Exchanges. Experimental results demonstrate significant gains (22% MAP@10) of CoVaGE over state-of-the-art diffusion prediction models. Our ablation study further emphasizes the synergistic impact of jointly modeling social homophily and temporal influence.'
---

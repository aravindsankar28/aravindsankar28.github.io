---
title: "An Adversarial Approach to Improve Long-Tail Performance in Neural Collaborative Filtering"
collection: publications
permalink: /publication/2018-01-01-An-Adversarial-Approach-to-Improve-Long-Tail-Performance-in-Neural-Collaborative-Filtering
type: conference
date: 2018-01-01
venue: 'Proceedings of the 27th ACM International Conference on Information and Knowledge Management, CIKM 2018, Torino, Italy, October 22-26, 2018'
paperurl: '../files/Long-Tail-GAN-CIKM2018.pdf'
authors: 'Adit Krishnan, Ashish Sharma, <strong>Aravind Sankar</strong>, Hari Sundaram'
url: 'https://doi.org/10.1145/3269206.3269264'
abstract: 'In recent times, deep neural networks have found success in Collaborative Filtering (CF) based recommendation tasks. By parametrizing latent factor interactions of users and items with neural architectures, they achieve significant gains in scalability and performance over matrix factorization. However, the long-tail phenomenon in recommender performance persists on the massive inventories of online media or retail platforms. Given the diversity of neural architectures and applications, there is a need to develop a generalizable and principled strategy to enhance long-tail item coverage. In this paper, we propose a novel adversarial training strategy to enhance long-tail recommendations for users with Neural CF (NCF) models. The adversary network learns the implicit association structure of entities in the feedback data while the NCF model is simultaneously trained to reproduce these associations and avoid the adversarial penalty, resulting in enhanced long-tail performance. Experimental results show that even without auxiliary data, adversarial training can boost long-tail recall of state-of-the-art NCF models by up to 25%, without trading-off overall performance. We evaluate our approach on two diverse platforms, content tag recommendation in Q&amp;A forums and movie recommendation.'
code: https://github.com/CrowdDynamicsLab/NCF-GAN
---

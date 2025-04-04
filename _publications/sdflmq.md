---
title: "SDFLMQ: A Semi-Decentralized Federated Learning Framework over MQTT"
collection: publications
category: conferences
permalink: /publication/sdflmq
excerpt: 'This paper is about core features of the framework.'
date: 2025.06.02
venue: 'IPDPS 2025, PAISE workshop'
slidesurl: ''
paperurl: 'https://arxiv.org/pdf/2503.13624'
citation: 'Ali-Pour, A. and Gascon-Samson, J., 2025. SDFLMQ: A Semi-Decentralized Federated Learning Framework over MQTT. arXiv preprint arXiv:2503.13624.'
---

Federated Learning is widely discussed as a distributed machine learning concept with stress on preserving data privacy. Various structures of Federated Learning were proposed. Centralized Federated learning for instance has been the primary structure that suits cloud computing. Decentralized Federated learning also has been proposed for ecosystems where communication is dominantly peer-to-peer. Semi-Decentralized Federated Learning (SDFL) has emerged recently as a new concept where the interconnected nodes are clustered, and each cluster is managed independently. The potential of SDFL lies in its clustering feature, which distributes the load of the global model update down onto multiple nodes. Since the concept is fairly new, much can be done to render this FL model a reliable, efficient, and real-time service at the edge. In this paper, we propose SDFLMQ, a semi-decentralized Federated learning framework at the Edge that uses MQTT as the communication protocol. We demonstrate how the publish/subscribe communication model is used to facilitate the clustering and load balancing in SDFL. We also demonstrate how SDFLMQ can use some of the core MQTT features to expand its capacity with no significant costs. Based on some primary evaluations, we demonstrate how SDFLMQ can efficiently distribute the load of aggregation, and potentially save unnecessary memory allocation, all with no requirement for a powerful central unit for aggregation and global model update. We also disclose some of the key future expansions of SDFLMQ with a focus on the operation of large deep neural network models at the edge. 
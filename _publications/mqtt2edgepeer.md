---
title: "MQTT2EdgePeer: A robust and scalable brokerless peer-to-peer edge middleware for topic-based publish/subscribe"
collection: publications
category: conferences
permalink: /publication/mqtt2edgepeer
excerpt: 'This paper is about a robust and scalable brokerless peer-to-peer edge middleware for topic-based publish/subscribe commnication model'
date: 2024.5.6
venue: 'CCGRID 2024'
slidesurl: ''
paperurl: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10701428&casa_token=x_inOeT1YWUAAAAA:NJre046vepm4Kdjpopumh6V4onKXgNlmj3NCgB1OWv_BXn3vp4zX9XKLwdyE_17cUCORidkPBTs'
citation: 'Rahmani, S., Ali-Pour, A., Coti, C. and Gascon-Samson, J., 2024, May. MQTT2EdgePeer: A robust and scalable brokerless peer-to-peer edge middleware for topic-based publish/subscribe. In 2024 IEEE 24th International Symposium on Cluster, Cloud and Internet Computing (CCGrid) (pp. 419-424). IEEE.'
---

The topic-based publish-subscribe paradigm plays an important role among many applications, as it enables a seamless interconnection of heterogeneous client applications and devices, through easy-to-use high-level abstractions. While publish-subscribe systems are usually provided in a centralized (i.e., broker-based) model, a peer-to-peer (P2P) topology can bring several benefits, such as increased resiliency and scalability, better load distribution, and a better handling of hot topics that comprise a large amount of publishers and subscribers. The presence of hot topics can result in high outgoing bandwidth usage, which is an important consideration in edge-based deployments.This paper presents MQTT2EdgePeer, a robust and scalable P2P brokerless topic-based publish-subscribe middleware that provides compatibility with MQTT-based applications. MQTT2EdgePeer, which is built on top of a structured edge P2P overlay, provides two message delivery approaches that enable a trade-off between efficient bandwidth distribution among the nodes, and latency minimization. Our findings reveal that MQTT2EdgePeer provides improved scalability, better load distribution, and reduced latencies, in comparison with a state-of-the-art Distributed Single Root per Topic (DSRT) approach.
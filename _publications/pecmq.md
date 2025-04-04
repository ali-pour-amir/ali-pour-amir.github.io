---
title: "PECMQ: Private and Encrypted Communications in IoT Systems Using PUFs and MQTT"
collection: publications
category: conferences
permalink: /publication/pecmq
excerpt: 'This paper is about how PUF can be used in composition with MQTT protocol to create private and encrypted communcation channels.'
date: 2024.07.23
venue: 'ICDCS 2024, EDCCS workshop'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10660755'
citation: 'Ali-Pour, A. and Gascon-Samson, J., 2024, July. PECMQ: Private and Encrypted Communications in IoT Systems Using PUFs and MQTT. In 2024 IEEE 44th International Conference on Distributed Computing Systems Workshops (ICDCSW) (pp. 64-74). IEEE.'
---

IoT systems are actively improving their core system qualities, including but not limited to network and device performance, system security, and reliability. Simplicity in implementation is also a quality that has gained importance over the years, especially in terms of communication protocols. In this regard, protocols that are based on a publish-subscribe (pub/sub) communication paradigm (e.g., MQTT) have gained a lot of attention, as they offer support for dynamically establishing and joining communications channels (i.e., topics), that can be used to quickly disseminate contents to groups of users. Nonetheless, sensitive applications might require the creation of private and secure communications channels that can be used only by certain users. In this paper, we propose a preliminary design of PECMQ, a private session generation method that uses a built-in Physically Unclonable Function in the client machines to mutually generate a random topic and a random key that can be used for private and secure message exchanges over an unsecured, unmodified MQTT broker. We demonstrate that our proposed PECMQ method can uphold the secrecy of the topic and the messages, with minimal computation overhead on the client machines, while guarding against various attack scenarios.
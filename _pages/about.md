---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am a postdoctoral researcher at ETS. I work at the [Cloud-2-Edge (C2E)](https://www.juliengs.ca/) lab which is under supervision and management of [Dr. Julien Gascon-Samson](https://www.etsmtl.ca/en/study-at-ets/professors/jgsamson). I work on various projects related to distributed systems, distributed machine learning, and edge computing. Before joining C2E at ETS, I worked at SGS-Brightsight in Delft, the Netherlands, as a hardware security evaluator. I received my PhD in Computer Engineering from Grenoble Alpes University, Grenoble, France, in 2022, and my masters in Embedded Systems Security and Trust from Grenoble INP in 2019. I also have a B.Sc in Computer Software Engineering which I received from Azad University of Tehran (South Branch), Tehran, Iran, in 2016.


Early career as a researcher
======
I started my research in Machine Learning and Deep Learning when I joined the LCIS lab in Valence, France as an M.intern. Before that, I briefly studied Nueromorphic computing chips as Master student research assistant in IUST, during which time I developed interest in the utilization of machine learning for embedded systems. At LCIS, I studied and implemented various side channel analysis techniques based on Deep Learning for hardware security evaluation. My work then was submitted and presented at DATE 2020 conference. After graduating from my master program in Grenoble INP, I continued as a PhD student in Computer Engineering at LCIS, with more focus on applied ML/DL techinques to improve big cryptographic data processing for constrained cyber-phyiscal objects. I developed and led various projects, including a methodology on ML-based authentication and enrollment of Phyiscally Unclonable Functions (PUF) with ML, number of works on improving PUF modeling using Transfer Learning and Sub-space modeling, and a light-weight authentication and key-exchange protocol based on ML for PUF-enabled embedded systems. I then briefly joined SGS-Brightsight as a hardware security evaluator, worked on side-channel analysis and hardware verification at industrial level percision, before I joined ETS as a postdoctoral researcher in 2023.     


Career as a software developer
======
I was a software developer before beginning my career as a researcher. I majorly worked on video game projects as a part-time software engineer and gameplay programmer during my B.Sc studies in Tehran between 2011 to 2016. I was part of development teams working on small-sized video games mostly targetted mobile platforms at Karina mobile solutions in Tehran, Iran, and before that at Medrick game studio in Tehran Iran. I was a pineering member of an indie game development team during the years between 2012 to 2016, and worked on various indie titles for personal computers, and [a game development tool](https://www.youtube.com/watch?v=hLBACBFNxTE) to improve 2D game design in Unity3D game engine.

Current Projects
======

Semi-Decentralized Federated Learning over MQTT
------

SDFLMQ is a framework I designed and co-developed that is aimed to enable constrained user-end and edge-level devices to perform federated learning. The framework follows a semi-decentralized hierarchical FL model. This model does not require a central server to perform aggregation. Instead, client machines that contribute to the FL process are elected to perform aggregation exclusively, or mututally with locally training the model. We employed MQTT protocol and exclusively used the Publish/Subscribe communication method to model the role association, arrangement, and re-arrangement in the framework. SDFLMQ is implemented in python, and the source code of the framework is available [here](https://github.com/ali-pour-amir/SDFLMQ) on github. It currently supports Pytorch only. The immidiate next versions of the framework however will be ML platform agnostic. Further information on the architecture of the framework and other related information can be found [here](https://arxiv.org/abs/2503.13624), an openly accessible paper about the framework. This paper is also accepted and to be presented in the renown [IPDPS 2025](https://www.ipdps.org/) conference, [PAISE](https://paise.org/) workshop. 


Flag Swap: FL aggregation placement optimization using Swarm Intelligence
------

Flag Swap is a project developed to optimize the aggregation placement in a hierarchical model of SDFL. The project exclusively employs Particle Swarm Intteligence (PSO) as a black-box meta-heuristic optimization algorithm to progressively optimize the placement as the FL rounds progress. Flag Swap's simulation has been developed by Mr. Sadra Bekrani, and is available [here](https://github.com/10xComrade/PSO_FL_Sim) on github. Flag Swap is also integrated into [SDFLMQ source code](https://github.com/ali-pour-amir/SDFLMQ), and can be found in the [optimizers](https://github.com/ali-pour-amir/SDFLMQ/tree/main/Client/Core/Modules/Coordinator_Modules/optimizers) directory. A paper is written that explains the structure of the optimizer, and some early findings on the superior performance of the optimizer compared to conventional determinstic placement strategies. It will soon be publicized [here]().


Towards resource-efficient distributed aggregation using adaptive clustering in Semi-Decentralized Federated Learning
------
This is an on-going project, with the aim to be employed in SDFLMQ to enable the framework with adaptability towards the changing population in FL. The adaptability is primarily aimed to be in the topology of the connections inter-cluster-wise and intra-cluster-wise. Information on the progress in this project, and the new findings will be published here. 
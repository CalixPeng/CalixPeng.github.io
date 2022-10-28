---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /research
---

{% include base_path %}

---

## Cognitive Scheduling for Multihop Underwater Acoustic Networks
The major goal of this project is to investigate optimal scheduling for a cognitive multihop underwater acoustic network with a primary user interference constraint. The network consists of primary and secondary users, with multihop transmission adopted for both user types to provide reliable communications. Key characteristics of underwater acoustic channels, including large propagation delay, distance-and-frequency dependent attenuation, half-duplex modem and inter-hop interference are taken into account in the design and analysis. In particular, time-slot allocation is found to be more effective than frequency slot allocation due to the underwater channel model. The goal of the network scheduling problem is to maximize the end-to-end throughput of the overall system, while limiting the throughput loss of primary users. Both centralized and decentralized approaches are considered. e framework of Partially Observable Markov Decision Processes (POMDP) is applied to formulate the optimization problem and an optimal dynamic programming algorithm is derived. However, the optimal dynamic programming solution is computationally intractable. Key properties are shown for the objective function, enabling the design of approximate schemes with significant complexity reduction. Numerical results show the proposed schemes significantly increase system throughput and while maintaining the primary throughput loss constraint. Under certain traffic conditions, the throughput gain over frequency-slot allocation schemes can be as high as 55%.

## Multiuser Spatial Division Scheduling in Underwater Acoustic Networks with Fairness (on-going)
In this project, we consider a multiple-input single-output underwater acoustic OFDM communication system. The POMDP framework is combined with spatial division multiple access and beamforming ideas to explore scheduling opportunities in the spatial domain. We explore the multi-user scenario where user mobility is taken into consideration. As the scheduling problem faces the issue of high computation complexity due to the exponentially large state space, we will explore simplification ideas to reduce dimensionality reasonably. Moreover, we also introduce a fairness measure into the scheduling problem to ensure that users with different traffic statistics are served fairly.

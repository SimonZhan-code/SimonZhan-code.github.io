---
title: "Belief-Based Offline Reinforcement Learning for Delay-Robust Policy Optimization"
collection: publications
category: conference
permalink: /publication/2026-iclr-dt-corl.md
excerpt: 'This paper introduces Shop-R1, a novel reinforcement learning framework aimed at enhancing the reasoning ability of LLMs for simulation of real human behavior in online shopping environments through a two-stage approach with distinct reward signals.'
date: 2026-01-23
venue: 'ICLR 2026'
authors: 'Simon Sinong Zhan, Qingyuan Wu, Philip Wang, Frank Yang, Xiangyu Shi, Chao Huang, Qi Zhu'
paperurl: 'https://arxiv.org/pdf/2506.00131'
citation: '@article{zhan2025adapting,
  title={Adapting Offline Reinforcement Learning with Online Delays},
  author={Zhan, Simon Sinong and Wu, Qingyuan and Yang, Frank and Shi, Xiangyu and Huang, Chao and Zhu, Qi},
  journal={arXiv preprint arXiv:2506.00131},
  year={2025}
}'
---

Offline–to–online deployment of reinforcement learning (RL) agents often stumbles over two fundamental gaps: (1) the sim-to-real gap, where real-world systems exhibit latency and other physical imperfections not captured in simulation; and (2) the interaction gap, where policies trained purely offline face out-of-distribution (OOD) issues during online execution, as collecting new interaction data is costly or risky. As a result, agents must generalize from static, delay-free datasets to dynamic, delay-prone environments. In this work, we propose DT-CORL(Delay-Transformer belief policy Constrained Offline RL), a novel framework for learning delay-resilient policies solely from static, delay-free offline data. DT-CORL introduces a transformer-based belief model to infer latent states from delayed observations and jointly trains this belief with a constrained policy objective, ensuring that value estimation and belief representation remain aligned throughout learning. Crucially, our method does not require access to delayed transitions during training and outperforms naive history-augmented baselines, SOTA delayed RL methods, and existing belief-based approaches. Empirically, we demonstrate that DT-CORL achieves strong delay-robust generalization across both locomotion and goal-conditioned tasks in the D4RL benchmark under varying delay regimes. Our results highlight that joint belief-policy optimization is essential for bridging the sim-to-real latency gap and achieving stable performance in delayed environments.


**Authors:** Simon Sinong Zhan, Qingyuan Wu, Philip Wang, Frank Yang, Xiangyu Shi, Chao Huang, Qi Zhu
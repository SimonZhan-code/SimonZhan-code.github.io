---
title: "Variational Delayed Policy Optimization"
collection: publications
category: conferences
permalink: /publication/2024-neurips-vdpo
excerpt: 'Variational Delayed Policy Optimization (VDPO) reformulates delayed RL as a variational inference problem, which is further modelled as a two-step iterative optimization problem, where the first step is TD learning in the delay-free environment with a small state space, and the second step is behaviour cloning which can be addressed much more efficiently than TD learning.'
date: 2024-10-01
venue: 'Conference on Neural Information Processing Systems (NeurIPS)'
authors: 'Qingyuan Wu*, Simon Sinong Zhan*, Yixuan Wang, Yuhui Wang, Chung-Wei Lin, Chen Lv, Qi Zhu, Chao Huang (*equal contribution)'
paperurl: 'https://arxiv.org/pdf/2405.14226'
codeurl: 'https://github.com/QingyuanWuNothing/VDPO'
citation: '@article{wu2024variational,
  title={Variational delayed policy optimization},
  author={Wu, Qingyuan and Zhan, Simon S and Wang, Yixuan and Wang, Yuhui and Lin, Chung-Wei and Lv, Chen and Zhu, Qi and Huang, Chao},
  journal={Advances in neural information processing systems},
  volume={37},
  pages={54330--54356},
  year={2024}
}'
---

This paper introduces Variational Delayed Policy Optimization (VDPO), a novel approach to reinforcement learning with delayed observations. The method reformulates the delayed RL problem as a variational inference problem and solves it through a two-step iterative optimization process. The first step involves TD learning in a delay-free environment with a reduced state space, while the second step uses behavior cloning, which is computationally more efficient than traditional TD learning approaches.



**Authors:** Qingyuan Wu*, Simon Sinong Zhan*, Yixuan Wang, Yuhui Wang, Chung-Wei Lin, Chen Lv, Qi Zhu, Chao Huang (*equal contribution)
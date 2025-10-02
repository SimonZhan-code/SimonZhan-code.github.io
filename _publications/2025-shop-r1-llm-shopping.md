---
title: "Shop-R1: Rewarding LLMs to Simulate Human Behavior in Online Shopping via Reinforcement Learning"
collection: publications
category: workshops
permalink: /publication/2025-shop-r1-llm-shopping
excerpt: 'This paper introduces Shop-R1, a novel reinforcement learning framework aimed at enhancing the reasoning ability of LLMs for simulation of real human behavior in online shopping environments through a two-stage approach with distinct reward signals.'
date: 2025-07-01
venue: 'Scaling Environments for Agents (SEA) NeurIPS 2025'
paperurl: 'https://arxiv.org/pdf/2507.17842'
citation: '@article{zhang2025shop,
  title={Shop-R1: Rewarding LLMs to Simulate Human Behavior in Online Shopping via Reinforcement Learning},
  author={Zhang, Yimeng and Wang, Tian and Gesi, Jiri and Wang, Ziyi and Lu, Yuxuan and Lin, Jiacheng and Zhan, Sinong and Gao, Vianne and Jiao, Ruochen and Liu, Junze and Qian, Kun and Tang, Yuxin and Xue, Ran and Zhang, Houyu and Cui, Qingjun and Guo, Yufan and Wang, Dakuo},
  journal={arXiv preprint arXiv:2507.17842},
  year={2025},
  url={https://arxiv.org/abs/2507.17842}
}'
---

This paper addresses the challenge of generating believable human-like behavior in web environments using Large Language Models (LLMs). While prior work has explored augmenting training data with LLM-synthesized rationales and supervised fine-tuning, performance remains bounded by the reasoning capabilities of the rationale-generating model. Shop-R1 introduces a novel reinforcement learning framework that decomposes human behavior simulation into two stages: rationale generation and action prediction, each guided by distinct reward signals. For rationale generation, the framework leverages internal model signals to guide reasoning in a self-supervised manner. For action prediction, it proposes a hierarchical reward structure with difficulty-aware scaling to prevent reward hacking and enable fine-grained reward assignment.

[Download paper here](https://arxiv.org/pdf/2507.17842)

**Authors:** Yimeng Zhang, Tian Wang, Jiri Gesi, Ziyi Wang, Yuxuan Lu, Jiacheng Lin, Sinong Zhan, Vianne Gao, Ruochen Jiao, Junze Liu, Kun Qian, Yuxin Tang, Ran Xue, Houyu Zhang, Qingjun Cui, Yufan Guo, Dakuo Wang
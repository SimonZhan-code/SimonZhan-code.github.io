---
title: "STEP-LLM: Generating CAD STEP Models from Natural Language with Large Language Models"
collection: publications
category: conferences
permalink: /publication/2026-date-step-llm
excerpt: 'STEP-LLM is the first unified framework for direct STEP (ISO 10303) CAD file generation from natural language, combining a 40K STEP-caption dataset, graph-aware reserialization, retrieval-augmented fine-tuning, and Chamfer-distance-based RL refinement.'
date: 2026-04-20
venue: 'Design, Automation and Test in Europe Conference (DATE)'
badge: 'DATE 2026'
authors: 'Xiangyu Shi, Junyang Ding, Xu Zhao, Sinong Zhan, Payal Mohapatra, Daniel Quispe, Kojo Welbeck, Jian Cao, Wei Chen, Ping Guo, Qi Zhu'
paperurl: 'https://arxiv.org/abs/2601.12641'
codeurl: 'https://github.com/JasonShiii/STEP-LLM'
citation: '@inproceedings{shi2026stepllm,
  title={STEP-LLM: Generating CAD STEP Models from Natural Language with Large Language Models},
  author={Shi, Xiangyu and Ding, Junyang and Zhao, Xu and Zhan, Sinong and Mohapatra, Payal and Quispe, Daniel and Welbeck, Kojo and Cao, Jian and Chen, Wei and Guo, Ping and Zhu, Qi},
  booktitle={Design, Automation and Test in Europe Conference (DATE)},
  year={2026},
  url={https://arxiv.org/abs/2601.12641}
}'
---

STEP-LLM bridges large language models with the STEP (ISO 10303) boundary-representation CAD standard, enabling direct generation of manufacturable CAD models from natural language. The framework curates ~40K STEP-caption pairs, introduces a depth-first-search-based reserialization that linearizes cross-references while preserving locality, grounds generation with retrieval-augmented fine-tuning, and refines quality via reinforcement learning with a Chamfer-distance geometric reward.


**Authors:** Xiangyu Shi, Junyang Ding, Xu Zhao, Sinong Zhan, Payal Mohapatra, Daniel Quispe, Kojo Welbeck, Jian Cao, Wei Chen, Ping Guo, Qi Zhu

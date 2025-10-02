---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a 3rd year PhD student in the ECE department at Northwestern University, advised by [Qi Zhu](http://users.eecs.northwestern.edu/~qzhu/). Before Northwestern, I did my undergrad in Applied Math and Computer Science at UC Berkeley, where I was advised by [Sanjit A. Seshia](http://people.eecs.berkeley.edu/~sseshia/). I have also spent great time as research intern at [Amazon SFAI](https://www.aboutamazon.com/news/retail/amazon-rufus). 

## Research Statement

My research lies at the intersection of Reinforcement Learning and Formal Methods, developing principled approaches to ensure safety, robustness, and verifiability in embodied cyber-physical systems. I focus on integrating formal verification techniques with learning-based control to provide guarantees while maintaining adaptability and performance. My work spans safe reinforcement learning with constraint satisfaction, delay-aware optimization under uncertainty, model-based approaches for certified learning, and neurosymbolic methods that combine symbolic reasoning with neural computation to achieve interpretable and verifiable intelligent systems. And my research has resulted in publications in some top tier conference such as ICML, NeurIPS, ICCPS, L4DC, FM, RV, IROS, etc. 

## News

<div class="news-container">
  <div class="news-scroll">
  <div class="news-item">
      <span class="news-date">[10/2025]</span> 2 paper have been accepted to <a href="https://sea-workshop.github.io/">SEA@NeurIPS 2025</a>.
    </div>
    <div class="news-item">
      <span class="news-date">[05/2025]</span> I will start my summer internship at Amazon as Applied Scientist in Palo Alto office. Happy to connect!
    </div>
    <div class="news-item">
      <span class="news-date">[05/2025]</span> Our paper <a href="https://arxiv.org/pdf/2505.00546">"Directly Forecasting Belief for Reinforcement Learning with Delays"</a> is accepted to <a href="https://icml.cc/">ICML 2025</a>
    </div>
    <div class="news-item">
      <span class="news-date">[10/2024]</span> Our paper <a href="https://arxiv.org/pdf/2405.14226">"Variational Policy Delayed Optimization"</a> is accepted to <a href="https://neurips.cc/">NeurIPS 2024</a> (Spotlight!)
    </div>
    <div class="news-item">
      <span class="news-date">[06/2024]</span> Our paper <a href="https://arxiv.org/abs/2309.09317">"Kinematics-aware Trajectory Generation and Prediction with Latent SDE"</a> is accepted to <a href="https://iros2024-abudhabi.org">IROS 2024</a>
    </div>
    <div class="news-item">
      <span class="news-date">[06/2024]</span> Our paper <a href="https://link.springer.com/chapter/10.1007/978-3-031-74234-7_13">"Case Study: Runtime Safety Verification of Neural Network Controlled System"</a> is accepted to <a href="https://yeni.cmpe.bogazici.edu.tr/rv24/">RV 2024</a>
    </div>
    <div class="news-item">
      <span class="news-date">[06/2024]</span> Our paper <a href="https://link.springer.com/chapter/10.1007/978-3-031-71177-0_15">"Switching Controller Synthesis for Hybrid Systems Against STL Formulas"</a> is accepted to <a href="https://www.fm24.polimi.it/">FM 2024</a>
    </div>
    <div class="news-item">
      <span class="news-date">[05/2024]</span> Our paper <a href="https://arxiv.org/abs/2402.03141">"Boosting long delayed RL with auxiliary short delay"</a> is accepted to <a href="https://icml.cc/">ICML 2024</a>
    </div>
    <div class="news-item">
      <span class="news-date">[05/2024]</span> I will attend <a href="https://fm.csl.sri.com/SSFT24/">SSFT 2024</a>. Please feel free to reach out if you are interested in my research
    </div>
    <div class="news-item">
      <span class="news-date">[04/2024]</span> Our paper <a href="https://arxiv.org/abs/2311.02227">"State-wise Safe RL With Pixel Observations"</a> is accepted to <a href="https://l4dc.web.ox.ac.uk/home">L4DC 2024</a>
    </div>
    <div class="news-item">
      <span class="news-date">[03/2024]</span> <a href="https://arxiv.org/pdf/2312.00812">One paper</a> accepted to <a href="https://llmagents.github.io/">LLMAgent@ICLR 2024</a>
    </div>
    <div class="news-item">
      <span class="news-date">[09/2023]</span> I will start my PhD journey at ECE department, Northwestern University
    </div>
  </div>
</div>

## Selected Publications

<div class="selected-publications">
  <div class="publication-item">
    <div class="publication-header">
      <h3 class="publication-title">
        <a href="/publication/2024-neurips-vdpo">Variational Delayed Policy Optimization</a>
      </h3>
      <div class="publication-venue">NeurIPS 2024 <span class="spotlight-badge">Spotlight</span></div>
    </div>
    <div class="publication-authors">
      Qingyuan Wu*, <strong>Simon Zhan*</strong>, Yixuan Wang, Yuhui Wang, Chung-Wei Lin, Chen Lv, Qi Zhu, Chao Huang
    </div>
    <div class="publication-description">
      Variational Delayed Policy Optimization (VDPO) reformulates delayed RL as a variational inference problem, solved through a two-step iterative optimization process with TD learning and behavior cloning.
    </div>
    <div class="publication-links">
      <a href="https://arxiv.org/pdf/2405.14226" class="pub-link">
        <i class="fas fa-file-pdf"></i> Paper
      </a>
      <a href="https://github.com/QingyuanWuNothing/VDPO" class="pub-link">
        <i class="fas fa-code"></i> Code
      </a>
    </div>
  </div>

  <div class="publication-item">
    <div class="publication-header">
      <h3 class="publication-title">
        <a href="/publication/2023-icml-safe-rl">Enforcing Hard Constraints with Soft Barriers: Safe Reinforcement Learning in Unknown Stochastic Environments</a>
      </h3>
      <div class="publication-venue">ICML 2023</div>
    </div>
    <div class="publication-authors">
      Yixuan Wang, <strong>Simon Zhan</strong>, Ruochen Jiao, Zhilu Wang, Wanxin Jin, Zhuoran Yang, Zhaoran Wang, Chao Huang, Qi Zhu
    </div>
    <div class="publication-description">
      A safe RL approach that can jointly learn the environment and optimize the control policy, while effectively avoiding unsafe regions with safety probability optimization using soft barriers to enforce hard safety constraints.
    </div>
    <div class="publication-links">
      <a href="https://arxiv.org/abs/2209.15090" class="pub-link">
        <i class="fas fa-file-pdf"></i> Paper
      </a>
      <a href="https://github.com/wangyixu14/safe_unknown_control" class="pub-link">
        <i class="fas fa-code"></i> Code
      </a>
    </div>
  </div>

  <div class="publication-item">
    <div class="publication-header">
      <h3 class="publication-title">
        <a href="/publication/2023-iccps-certified-rl">Joint Differentiable Optimization and Verification for Certified Reinforcement Learning</a>
      </h3>
      <div class="publication-venue">ICCPS 2023</div>
    </div>
    <div class="publication-authors">
      Yixuan Wang*, <strong>Simon Zhan*</strong>, Zhilu Wang, Chao Huang, Zhaoran Wang, Zhuoran Yang, Qi Zhu
    </div>
    <div class="publication-description">
      A framework that jointly conducts reinforcement learning and formal verification by formulating and solving a novel bilevel optimization problem, which is end-to-end differentiable through gradients from the value function and certificates formulated by linear programs and semi-definite programs.
    </div>
    <div class="publication-links">
      <a href="https://arxiv.org/abs/2201.12243" class="pub-link">
        <i class="fas fa-file-pdf"></i> Paper
      </a>
      <a href="https://github.com/SimonZhan-code/Certified-RL-LP" class="pub-link">
        <i class="fas fa-code"></i> Code
      </a>
    </div>
  </div>
</div>

<style>
.news-container {
  background: var(--global-background-color);
  border: 1px solid var(--global-border-color);
  border-radius: 8px;
  padding: 0;
  margin: 1em 0;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  position: relative;
}

.news-scroll {
  max-height: 300px;
  overflow-y: auto;
  padding: 0;
  scrollbar-width: thin;
  scrollbar-color: var(--global-border-color) transparent;
}

.news-scroll::-webkit-scrollbar {
  width: 8px;
}

.news-scroll::-webkit-scrollbar-track {
  background: transparent;
}

.news-scroll::-webkit-scrollbar-thumb {
  background: var(--global-border-color);
  border-radius: 4px;
}

.news-scroll::-webkit-scrollbar-thumb:hover {
  background: var(--global-text-color-light);
}

.news-item {
  padding: 12px 16px;
  border-bottom: 1px solid var(--global-border-color);
  font-size: 0.95em;
  line-height: 1.4;
  transition: background-color 0.2s ease;
}

.news-item:last-child {
  border-bottom: none;
}

.news-item:hover {
  background-color: var(--global-code-background-color);
}

.news-date {
  font-weight: bold;
  color: var(--global-primary-color);
  margin-right: 8px;
  font-family: monospace;
  font-size: 0.9em;
}

.news-item a {
  color: var(--global-link-color);
  text-decoration: none;
}

.news-item a:hover {
  color: var(--global-link-color-hover);
  text-decoration: underline;
}

/* Add a subtle gradient at the bottom to indicate more content */
.news-container::after {
  content: "";
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  height: 20px;
  background: linear-gradient(transparent, var(--global-background-color));
  pointer-events: none;
  border-radius: 0 0 8px 8px;
}

/* Responsive design for mobile */
@media (max-width: 768px) {
  .news-scroll {
    max-height: 250px;
  }
  
  .news-item {
    padding: 10px 12px;
    font-size: 0.9em;
  }
  
  .news-date {
    display: block;
    margin-bottom: 4px;
    margin-right: 0;
  }
}

.selected-publications {
  margin: 2em 0;
}

.publication-item {
  background: var(--global-background-color);
  border: 1px solid var(--global-border-color);
  border-radius: 8px;
  padding: 20px;
  margin-bottom: 20px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  transition: box-shadow 0.3s ease, transform 0.2s ease;
}

.publication-item:hover {
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
  transform: translateY(-2px);
}

.publication-header {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  margin-bottom: 8px;
  flex-wrap: wrap;
  gap: 10px;
}

.publication-title {
  margin: 0;
  font-size: 1.1em;
  font-weight: 600;
  line-height: 1.3;
  flex: 1;
  min-width: 300px;
}

.publication-title a {
  color: var(--global-text-color);
  text-decoration: none;
}

.publication-title a:hover {
  color: var(--global-link-color);
  text-decoration: underline;
}

.publication-venue {
  font-weight: 600;
  color: var(--global-primary-color);
  font-size: 0.95em;
  white-space: nowrap;
}

.spotlight-badge {
  background: #ff6b6b;
  color: white;
  padding: 2px 8px;
  border-radius: 12px;
  font-size: 0.8em;
  font-weight: 500;
  margin-left: 8px;
}

.publication-authors {
  color: var(--global-text-color-light);
  font-size: 0.9em;
  margin-bottom: 10px;
  line-height: 1.4;
}

.publication-authors strong {
  color: var(--global-text-color);
  font-weight: 600;
}

.publication-description {
  color: var(--global-text-color);
  font-size: 0.95em;
  line-height: 1.5;
  margin-bottom: 15px;
}

.publication-links {
  display: flex;
  gap: 10px;
  flex-wrap: wrap;
}

.pub-link {
  display: inline-flex;
  align-items: center;
  padding: 8px 14px;
  background: var(--global-primary-color);
  color: white;
  text-decoration: none;
  border-radius: 6px;
  font-size: 0.85em;
  font-weight: 500;
  transition: all 0.2s ease;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.pub-link:hover {
  background: var(--global-primary-color-hover);
  color: white;
  text-decoration: none;
  transform: translateY(-1px);
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.15);
}

.pub-link i {
  margin-right: 6px;
  font-size: 0.9em;
}

/* Different colors for different link types */
.pub-link:has(i.fa-file-pdf) {
  background: #e74c3c;
}

.pub-link:has(i.fa-file-pdf):hover {
  background: #c0392b;
}

.pub-link:has(i.fa-code) {
  background: #2ecc71;
}

.pub-link:has(i.fa-code):hover {
  background: #27ae60;
}

.pub-link:has(i.fa-presentation, i.fa-file-powerpoint) {
  background: #f39c12;
}

.pub-link:has(i.fa-presentation, i.fa-file-powerpoint):hover {
  background: #e67e22;
}

.pub-link:has(i.fa-globe, i.fa-external-link-alt) {
  background: #3498db;
}

.pub-link:has(i.fa-globe, i.fa-external-link-alt):hover {
  background: #2980b9;
}

.pub-link:has(i.fa-video) {
  background: #9b59b6;
}

.pub-link:has(i.fa-video):hover {
  background: #8e44ad;
}

/* Additional icon types can be added here with custom colors */
.pub-link:has(i.fa-database) {
  background: #34495e; /* Dark gray for datasets */
}

.pub-link:has(i.fa-database):hover {
  background: #2c3e50;
}

.pub-link:has(i.fa-image) {
  background: #e67e22; /* Orange for posters/images */
}

.pub-link:has(i.fa-image):hover {
  background: #d35400;
}

.pub-link:has(i.fa-quote-right) {
  background: #95a5a6; /* Light gray for BibTeX */
}

.pub-link:has(i.fa-quote-right):hover {
  background: #7f8c8d;
}

/* Responsive design for publications */
@media (max-width: 768px) {
  .publication-item {
    padding: 15px;
  }
  
  .publication-header {
    flex-direction: column;
    align-items: flex-start;
  }
  
  .publication-title {
    min-width: auto;
    margin-bottom: 5px;
  }
  
  .publication-venue {
    align-self: flex-start;
  }
  
  .publication-links {
    justify-content: flex-start;
  }
  
  .pub-link {
    flex: 0 0 auto;
    padding: 6px 12px;
    font-size: 0.8em;
  }
  
  .pub-link i {
    margin-right: 4px;
  }
}
</style>

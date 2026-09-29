---
layout: home
permalink: /
redirect_from:
  - /about/
  - /about.html
---

{% include base_path %}

<div class="intro">
  <div class="intro__text">
    <h1>Sinong (Simon) Zhan</h1>
    <p>I am a 4th year PhD student in the ECE department at Northwestern University, advised by <a href="http://users.eecs.northwestern.edu/~qzhu/">Qi Zhu</a>. Before Northwestern, I did my undergrad in Applied Math and Computer Science at UC Berkeley, where I was advised by <a href="http://people.eecs.berkeley.edu/~sseshia/">Sanjit A. Seshia</a>. I am currently a Research Intern at <a href="https://research.google/">Google Research</a>. Previously, I spent a great time as a research intern at <a href="https://www.aboutamazon.com/news/retail/amazon-rufus">Amazon SFAI</a>.</p>
    <div class="intro__icons">
      <a href="mailto:{{ site.author.email }}"><i class="fas fa-envelope"></i>Email</a>
      <a href="{{ site.author.googlescholar }}"><i class="fas fa-graduation-cap"></i>Google Scholar</a>
      <a href="https://github.com/{{ site.author.github }}"><i class="fab fa-github"></i>GitHub</a>
      <a href="https://twitter.com/{{ site.author.twitter }}"><i class="fab fa-x-twitter"></i>Twitter</a>
      <a href="{{ base_path }}/cv/"><i class="fas fa-file-pdf"></i>CV</a>
    </div>
  </div>
  <div class="intro__photo">
    <img src="{{ base_path }}/images/simonzhan.jpg" alt="Photo of Sinong (Simon) Zhan">
  </div>
</div>

## Research

My research lies at the intersection of reinforcement learning, formal methods, and AI safety. I design safe and delay-robust RL algorithms that integrate formal verification — barrier certificates, constraint satisfaction — with learning-based control to provide provable guarantees for autonomous systems. More recently, I have been developing specification-guided frameworks that leverage formal specifications (temporal logics, program contracts) to systematically evaluate, steer, and explain foundation-model-based agents, addressing the challenge of bridging informal human safety intent and provably correct agent behavior. This agenda has led to publications in venues such as ICML, NeurIPS, ICLR, CVPR, CCS, ICCPS, L4DC, FM, RV, and IROS.

## News

{% include news-list.html %}

## Education

{% include experience.html data=site.data.education %}

## Experience

{% include experience.html data=site.data.experience %}

## Selected Publications

<div class="pub-list">
{% assign selected = site.publications | where_exp: "p", "p.selected == true" | sort: "date" | reverse %}
{% for pub in selected %}{% include publication-card.html pub=pub %}{% endfor %}
</div>

<p class="pub-see-all"><a href="{{ base_path }}/publications/">See all publications →</a></p>

## Academic Service

- **Conference reviewer:** NeurIPS, ICML, ICLR, AAAI, CVPR, ECCV, ICRA, L4DC, ASP-DAC, ECC
- **Journal reviewer:** Machine Learning (Springer), IEEE Internet of Things Journal
- **Program committee:** ICCPS Artifact Evaluation Committee

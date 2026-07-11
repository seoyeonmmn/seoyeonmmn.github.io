---
permalink: /
title: 
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Most of what I've worked on comes down to the same instinct: treat whatever you're looking at — an image, a walking sequence, the acoustics of a room — as a signal, and go looking for the structure underneath it. I did my M.S. in AI at Ewha Womans University ([PAI Lab](https://pai.ewha.ac.kr/), advised by [Prof. Junhyug Noh](https://junhyug.github.io/)), and I stay on at the lab as a researcher, working across computer vision, multimodal AI, and generative models.

## Experience

<div class="experience-item">
  <div class="experience-item__header">
    <strong>AI Research Intern</strong>
    <span class="experience-item__date">Jul. 2024 – May. 2025</span>
  </div>

  <div class="experience-item__company">
    DXR Co., Ltd.
  </div>

  <p class="experience-item__description">
    Conducted research on diffusion-based defect image generation for industrial visual inspection. Designed an end-to-end pipeline encompassing data preprocessing, model training, synthetic defect generation, and performance evaluation.
  </p>
</div>

<h2 id="publications">Publications</h2>

{% assign publications = site.publications | sort: "order" %}

<div class="publication-list">
{% for post in publications %}
  {% include publication-item.html %}
{% endfor %}
</div>

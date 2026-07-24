---
permalink: /
title: 
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Most of my work is driven by the same instinct: to treat data—whether an image, a gait sequence, or a spatial audio scene—as a signal, and to look for the structure beneath it. I earned my M.S. in Artificial Intelligence at Ewha Womans University, where I conducted research in the ([PAI Lab](https://pai.ewha.ac.kr/) under the supervision of [Prof. Junhyug Noh](https://junhyug.github.io/)). I now work in the same lab as a researcher, spanning computer vision, multimodal AI, and generative modeling.

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

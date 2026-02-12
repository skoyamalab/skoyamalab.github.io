---
layout: page
permalink: /research/
title: Research
description:
lang: en 
nav: true
nav_order: 1
---

### Research topics

---

We explore fundamental theories and applications of next-generation audio signal processing and machine learning to enable advanced analysis and control of sound fields. In our fundamental research, we primarily focus on an approach known as physics-informed learning, which directly integrates the physical properties of wave fields into machine learning frameworks, such as deep learning. By fusing the universality of physical laws with the flexibility of data-driven techniques, we aim to transcend conventional limitations in sound field analysis and control. Our goal is to implement these research findings in society as foundational technologies for future audiovisual interfaces - ranging from spatial audio for VR/AR to the creation of smart and comfortable acoustic environments - striving to create novel acoustic experiences that enrich people's daily lives. 

<div style="width: 90%; margin: 1rem;">
<script defer class="speakerdeck-embed" data-id="86139ad3a3764083a970cfecec71f171" data-ratio="1.7777777777777777" src="//speakerdeck.com/assets/embed.js"></script>
</div>

<br />

### Projects

---

<div class="projects" style="margin-top: 1rem;">
<!-- Display projects without categories -->
{%- assign sorted_projects = site.projects | sort: "importance" -%}
<!-- Generate cards for each project -->
{% if page.horizontal -%}
<div class="container">
<div class="row row-cols-2">
{%- for project in sorted_projects -%}
    {% include projects_horizontal.html %}
{%- endfor %}
</div>
</div>
{%- else -%}
<div class="grid">
{%- for project in sorted_projects -%}
    {% include projects.html %}
{%- endfor %}
</div>
{%- endif -%}
</div>

<br />

### Videos introducing our resarch

---

<div class="video-container" style="display: flex; flex-wrap: wrap; justify-content: left; gap: 10px;">
<iframe style="width: 100%; max-width: 300px; aspect-ratio: 16/ 9;" src="https://www.youtube.com/embed/RlbMzSLcLOQ?si=fjWvLIlRxLwrJ3ZZ" allowfullscreen></iframe>
<iframe style="width: 100%; max-width: 300px; aspect-ratio: 16/ 9;" src="https://www.youtube.com/embed/C5mmF5BE2iU?si=hSCdtVj-Tia5O9Yx" allowfullscreen></iframe>
<iframe style="width: 100%; max-width: 300px; aspect-ratio: 16/ 9;" src="https://www.youtube.com/embed/2Ru7-XwRTak?si=ixCJinTg3PyToj8r" allowfullscreen></iframe>
</div>
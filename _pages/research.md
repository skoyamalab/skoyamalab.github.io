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

Our main research topic is the analysis and control of acoustic fields and their applications. In particular, we explore new signal processing/machine learning methodologies that incorporate the physical properties of wave fields. Based on these methodologies, we aim to develop systems for virtual/augmented reality audio, noise control, acoustic imaging, and others.

<script defer class="speakerdeck-embed" data-id="fa8341a7d3e446b8bcd1eec7b10fe781" data-ratio="1.77777777777778" src="//speakerdeck.com/assets/embed.js"></script>

<br />

### Projects

<div class="projects">
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
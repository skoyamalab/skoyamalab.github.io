---
layout: page
permalink: /ja/research/
title: Research
description:
lang: ja 
nav_ja: true
nav_ja_order: 3
---

### 研究テーマ概要

---

音空間の計測と制御に関わる基礎技術、およびその応用技術について研究しています。特に、波動場の物理的な特性を取り入れた新しい信号処理／機械学習の方法論を探究し、これらに基づく音のバーチャルリアリティ、領域的な騒音制御などをシステムとして実現することを目指します。

<div style="width: 90%; margin: 1rem;">
<script defer class="speakerdeck-embed" data-id="0c16bb1b61784f8da13b20ea2281e8d1" data-ratio="1.7777777777777777" src="//speakerdeck.com/assets/embed.js"></script>
</div>

<br />

### プロジェクト

---

<div class="projects" style="margin-top: 1rem;">
<!-- Display projects without categories -->
{%- assign sorted_projects = site.projects_ja | sort: "importance" -%}
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
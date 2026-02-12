---
layout: page
permalink: /ja/research/
title: Research
description:
lang: ja 
nav_ja: true
nav_ja_order: 1
---

### 研究テーマ概要

---

私たちは，音空間の高度な解析と制御を可能にする，次世代の音響信号処理・機械学習の基礎理論とその応用を探求しています。基礎理論においては，波動場の物理的な特性を深層学習のような機械学習の枠組みに直接統合する「物理情報に基づく学習（Physics-informed learning）」と呼ばれるアプローチに主に取り組んでいます。物理法則の普遍性とデータ駆動型技術の柔軟性を融合させることで，従来の限界を超えた音場解析／制御の実現を目指します。これらの研究成果を，音のバーチャルリアリティ（VR/AR）やスマートかつ快適な音響空間の創出など，未来の視聴覚インタフェースを支える基盤技術として社会へ実装し，人々の生活をより豊かにする新しい音響体験の創出に挑んでいます。

より詳しい研究内容については以下のスライドをご参照ください。

<div style="width: 90%; margin: 1rem;">
<script defer class="speakerdeck-embed" data-id="86139ad3a3764083a970cfecec71f171" data-ratio="1.7777777777777777" src="//speakerdeck.com/assets/embed.js"></script>
</div>

<br />

### プロジェクト

---

個別の研究プロジェクトに関する詳細については以下をご参照ください。

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

<br />

### 研究紹介動画

---

研究内容を紹介する動画を以下でご覧いただけます。

<div class="video-container" style="display: flex; flex-wrap: wrap; justify-content: left; gap: 10px;">
<iframe style="width: 100%; max-width: 300px; aspect-ratio: 16/ 9;" src="https://www.youtube.com/embed/RlbMzSLcLOQ?si=fjWvLIlRxLwrJ3ZZ" allowfullscreen></iframe>
<iframe style="width: 100%; max-width: 300px; aspect-ratio: 16/ 9;" src="https://www.youtube.com/embed/C5mmF5BE2iU?si=hSCdtVj-Tia5O9Yx" allowfullscreen></iframe>
<iframe style="width: 100%; max-width: 300px; aspect-ratio: 16/ 9;" src="https://www.youtube.com/embed/2Ru7-XwRTak?si=ixCJinTg3PyToj8r" allowfullscreen></iframe>
</div>
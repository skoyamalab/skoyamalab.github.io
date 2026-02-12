---
layout: page
title: 物理的性質に基づく機械学習による音響処理
description: 
img: assets/img/piml_sfest.png
lang: ja
importance: 1
---

### 物理的性質に基づく機械学習による音響処理

<div style="margin: 1rem;">
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
    {% include figure.html path="assets/img/piml_sfest.png" title="Physics-informed machine learning for audio processing" class="img-fluid" %}
    </div>
</div>
</div>

多くの機械学習技術では、大量のデータを用いて目的のタスクを達成するためのモデル学習を行います。しかしながら、音響メディア処理ではそのような学習に用いるデータを大量に収集することが難しい場合も少なくありません。一方で、音響現象は物理法則に従うはずであり、そのような物理的性質に基づく制約が機械学習モデルの有用な事前情報となりえます。波動方程式のような音伝搬の支配方程式はその最たる例です。それ以外にも、扱う対象やタスクによって様々な物理的性質に基づく制約が考えられますが、これらを効率よく機械学習モデルに取り入れることによる、新たな音響処理技術の構築を目指します。これにより、従来の機械学習技術よりも少量のデータで、かつ古典的な物理モデルのみに基づく技術よりも高い柔軟性を持つ技術が実現できると期待できます。

##### 参考文献

<div class="sel-publications">
    {% bibliography --file skoyamalab_ja -q @*[key=Koyama:IEEE_M_SP2025]* %}
    {% bibliography --file skoyamalab_ja -q @*[key=Ribeiro:IEEE_ACM_J_ASLP2024]* %}
    {% bibliography --file skoyamalab_ja -q @*[key=Ueno:FnT_SP2025]* %}
</div>


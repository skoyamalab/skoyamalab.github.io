---
layout: page
title: 空間アクティブ騒音制御
description: 
img: assets/img/spatial_anc.png
lang: ja
importance: 1
---

### 空間アクティブ騒音制御

<div style="margin: 2rem;">
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
    {% include figure.html path="assets/img//spatial_anc.png" title="Spatial active noise control" class="img-fluid" %}
    </div>
</div>
</div>

騒音をマイクでモニタリングしながらスピーカ信号によってそれを打ち消す、アクティブ騒音制御技術は、主にダクト内のような一次元空間や、三次元空間だとしても局所的な領域のみを対象として応用されてきました。空間アクティブ騒音制御は、三次元空間のある対象領域内全体にわたって騒音を抑圧することを目的とする技術です。しかしながら、従来の技術では、騒音抑圧の効果はマイク位置付近のみに限られてしまいます。マイク信号から対象領域内の音場を推定し、それを打ち消すような音場をスピーカによって合成する、新たな空間アクティブ騒音制御の技術を研究しています。

##### デモ

<div class="ifrm_wrap">
<iframe width="560" height="315" src="https://www.youtube.com/embed/VhCPxi5BW34" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>


##### 参考文献

<div class="sel-publications">
    {% bibliography --file skoyamalab_ja -q @*[key=Koyama:IEEE_ACM_J_ASLP2021]* %}
    {% bibliography --file skoyamalab_ja -q @*[key=Ito:ICASSP2019]* %}
</div>



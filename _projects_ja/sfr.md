---
layout: page
title: スピーカアレイによる音場再現
description: 
img: assets/img/sfr_circ.gif
lang: ja
importance: 3
---

### スピーカアレイによる音場再現

<div style="margin: 1rem;">
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
    {% include figure.html path="assets/img/sfr_circ.gif" title="Sound field reproduction using loudspeaker array" class="img-fluid" %}
    </div>
</div>
</div>

従来のステレオ/サラウンド方式での音響再生は、summing localizationと呼ばれる聴覚特性に基づくため、スピーカアレイ中心位置（いわゆるスィートスポット）でしか適切に受聴することができず、特に残響環境を再現する場合などは人手で音をデザインするプロセスも必要です。複数のスピーカを用いて物理的な音空間そのものを合成する音場再現技術では、広い受聴領域での再現や、音の距離感・広がり感も含めた再現が可能であるほか、人手でのデザインも不要になることが期待できます。

##### 参考文献

<div class="sel-publications">
    {% bibliography --file skoyamalab_ja -q @*[key=Koyama:IEEE_J_ASLP2013]* %}
    {% bibliography --file skoyamalab_ja -q @*[key=Ueno:IEEE_ACM_J_ASLP2019]* %}
    {% bibliography --file skoyamalab_ja -q @*[key=Koyama:JAES2023]* %}
</div>


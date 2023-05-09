---
layout: page
title: マイクアレイ信号からのバイノーラル再現
description: 
img: assets/img/micarray2binaural.png
lang: ja
importance: 1
---

### マイクアレイ信号からのバイノーラル再現

<div style="margin: 1rem;">
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
    {% include figure.html path="assets/img/micarray2binaural.png" title="Binaural reproduction from microphone array recordings" class="img-fluid" %}
    </div>
</div>
</div>

頭部伝達関数を用いて両耳位置の信号を合成することを目的とするバイノーラル再現は、ヘッドフォンでの受聴を主に対象とした空間音響技術です。音源の位置や信号などの情報を与えてレンダリングをするような、VR空間におけるバイノーラル再現では、音響数値シミュレーションなどを用いることで比較的容易に実現できます。しかしながら、実環境の音を収録し、バイノーラル信号として再現することは技術的な課題が多く、発展途上の段階です。マイクアレイ信号から対象の音場を推定し、バイノーラル信号を再現する技術を実現することで、広い領域の再現が必要となる6DoFのVR技術などへも応用可能となることが期待できます。

##### デモ

<div class="ifrm_wrap">
<iframe width="560" height="315" src="https://www.youtube.com/embed/7ymP5Ey9uuM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

##### References
- N. Iijima, S. Koyama, and H. Saruwatari, "Binaural Rendering from Microphone Array Signals of Arbitrary Geometry," *J. Acoust. Soc. Amer.*, vol. 150, no. 4, pp. 2479-2491, 2021. <a href="https://doi.org/10.1121/10.0006538" target="_blank"><i class="fas fa-external-link-alt"></i></a>
- N. Ueno, S. Koyama, and H. Saruwatari, "Sound Field Recording Using Distributed Microphones Based on Harmonic Analysis of Infinite Order," *IEEE Signal Process. Lett.*, vol. 25, no. 1, pp. 135-139, 2018.  <a href="https://doi.org/10.1109/LSP.2017.2775242" target="_blank"><i class="fas fa-external-link-alt"></i></a>



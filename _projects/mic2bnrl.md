---
layout: page
title: Binaural reproduction from microphone array recordings
description: 
img: assets/img/micarray2binaural.png
importance: 1
---

### Binaural reproduction from microphone array recordings

<div style="margin: 1rem;">
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
    {% include figure.html path="assets/img/micarray2binaural.png" title="Binaural reproduction from microphone array recordings" class="img-fluid" %}
    </div>
</div>
</div>

Binaural reproduction is a spatial audio technology that reproduces sounds at two ear positions by using headphones and head-related transfer functions (HRTFs). The binaural sounds in a VR space are simply reproduced by numerical acoustic simulations using given source positions and signals. However, the binaural reproduction of a real environment is not straightforward. We develop a technology to estimate a sound field using a microphone array and reproduce it as binaural sounds, which can be applied to VR systems requiring a large listening area.

##### Demo

<div class="ifrm_wrap">
<iframe width="560" height="315" src="https://www.youtube.com/embed/7ymP5Ey9uuM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

##### References

<div class="sel-publications">
    {% bibliography --file skoyamalab_en -q @*[key=Iijima:JASA_J_2021]* %}
    {% bibliography --file skoyamalab_en -q @*[key=Ueno:IEEE_SPL2018]* %}
</div>




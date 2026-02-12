---
layout: page
title: Spatial active noise control
description: 
img: assets/img/spatial_anc.png
importance: 1
---

### Spatial active noise control

<div style="margin: 2rem;">
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
    {% include figure.html path="assets/img//spatial_anc.png" title="Spatial active noise control" class="img-fluid" %}
    </div>
</div>
</div>

Active noise control (ANC) is a technique to reduce noise by a canceling loudspeaker and monitoring microphone, which has been applied to local or one-dimensional space such as earphones and air ducts. Spatial ANC aims to reduce noise over a three-dimensional target region. However, conventional techniques can reduce noise only at microphone positions. We develop a new spatial ANC technique to reduce regional noise by estimating a noise field with microphones and synthesizing an anti-noise field with loudspeakers.

##### Demo

<div class="ifrm_wrap">
<iframe width="560" height="315" src="https://www.youtube.com/embed/VhCPxi5BW34" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

##### References

<div class="sel-publications">
    {% bibliography --file skoyamalab_en -q @*[key=Koyama:IEEE_ACM_J_ASLP2021]* %}
    {% bibliography --file skoyamalab_en -q @*[key=Ito:ICASSP2019]* %}
</div>

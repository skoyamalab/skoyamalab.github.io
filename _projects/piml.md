---
layout: page
title: Physics-informed machine learning for audio processing
description: 
img: assets/img/piml_sfest.png
importance: 1
---

### Physics-informed machine learning for audio processing

<div style="margin: 1rem;">
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
    {% include figure.html path="assets/img/piml_sfest.png" title="Physics-informed machine learning for audio processing" class="img-fluid" %}
    </div>
</div>
</div>

In many machine learning techniques, a model is trained on a large amount of data to accomplish a specific task. However, in audio processing, it is often difficult to collect a large amount of data for such training. On the other hand, acoustic phenomena are supposed to obey physical laws, and such physical constraints can provide useful prior information for machine learning models. The governing equations of sound propagation, such as the wave equation, are the best example. In addition, there are various other constraints based on physical properties that can be considered depending on the target or task, and we aim to build new audio processing technology by efficiently incorporating them into machine learning models. This is expected to enable technology that requires less data than conventional machine learning technology and is more flexible than technology based solely on physical models.

##### References

<div class="sel-publications">
    {% bibliography --file skoyamalab_en -q @*[key=Koyama:IEEE_M_SP2025]* %}
    {% bibliography --file skoyamalab_en -q @*[key=Ribeiro:IEEE_ACM_J_ASLP2024]* %}
    {% bibliography --file skoyamalab_en -q @*[key=Ueno:FnT_SP2025]* %}
</div>

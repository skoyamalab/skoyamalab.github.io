---
layout: page
title: Head-Related Transfer Function Personalization
description: 
img: assets/img/hrtf_indv.png
importance: 2
---

### Head-Related Transfer Function Personalization

<div style="margin: 1rem;">
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
    {% include figure.html path="assets/img/hrtf_indv.png" title="Head-Related Transfer Function Personalization" class="img-fluid" %}
    </div>
</div>
</div>

The head-related transfer function (HRTF) describes how sound propagates from a source to both ears. It contains important information for human sound localization and is essential for achieving binaural reproduction, a spatial audio technology for headphones. However, HRTFs vary significantly among listeners, and using another person's HRTF for binaural signals often results in localization errors. Therefore, to achieve high-quality binaural reproduction, it is crucial to obtain an individual's HRTF using a simple setup. We are investigating techniques such as upsampling HRTFs from a small set of measurements and estimating an individual's HRTF from ear shape parameters using machine learning.

##### References

<div class="sel-publications">
    {% bibliography --file skoyamalab_en -q @*[key=Ito:IEEE_OJSP2025]* %}
    {% bibliography --file skoyamalab_en -q @*[key=Niu:WASPAA2025]* %}
</div>





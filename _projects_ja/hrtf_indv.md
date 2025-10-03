---
layout: page
title: 頭部伝達関数の個人化
description: 
img: assets/img/hrtf_indv.png
lang: ja
importance: 2
---

### 頭部伝達関数の個人化

<div style="margin: 1rem;">
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
    {% include figure.html path="assets/img/hrtf_indv.png" title="Head-Related Transfer Function Personalization" class="img-fluid" %}
    </div>
</div>
</div>

音源位置から両耳位置までの音の伝達特性である頭部伝達関数（Head-Related Transfer Function: HRTF）は、人間の音像定位にとって重要な手がかりを含んでおり、ヘッドフォン受聴による空間音響技術であるバイノーラル再現を実現するには必要不可欠です。しかしながら、HRTFは受聴者ごとに大きく異なる上、他人のHRTFを用いたバイノーラル信号では定位感にずれが生じることが多く報告されています。したがって、高品質なバイノーラル再現には、受聴者個人のHRTFを簡易的な方法で取得できることが求められます。我々は、機械学習を用いて、少数の測定信号からHRTFをアップサンプリングする技術や、耳の形状パラメータから個人のHRTFを推定する技術などを研究しています。

##### References
- Y. Ito, T. Nakamura, S. Koyama, and H. Saruwatari, "Head-Related Transfer Function Interpolation from Spatially Sparse Measurements Using Autoencoder with Source Position Conditioning," in *Proc. IWAENC*, 2022. <a href="https://arxiv.org/abs/2207.10967" target="_blank"><i class="fas fa-external-link-alt"></i></a>
- R. Niu, S. Koyama, and T. Nakamura, "Head-Related Transfer Function Individualization Using Anthropometric Features and Spatially Independent Latent Representation," in *Proc. IEEE WASPAA*, 2025. <a href="https://arxiv.org/abs/2508.16176" target="_blank"><i class="fas fa-external-link-alt"></i></a>




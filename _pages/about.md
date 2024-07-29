---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently pursuing a master's Degree in computer science at the College of Computer Science and Technology, Civil Aviation University of China in Tianjin, China.

My research interests lie in Change Detection(CD), RGB-D Salient Object Detection(RGB-D SOD), and their application in diverse practical scenarios.

# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2024</div><img src='papers/ICASSP24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[A Saliency Enhanced Feature Fusion Based Multiscale RGB-D Salient Object Detection Network](https://ieeexplore.ieee.org/document/10447807)

Rui Huang, **Qingyi Zhao**, Yan Xing, Sihua Gao, Weifeng Xu, Yuxiang Zhang, Wei Fan

[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=GitHub&logoColor=FFFFFF)](https://github.com/Heprain/SEFFSal)

- We create an effective saliency enhanced feature fusion (SEFF) module, which uses the saliency maps to improve the representative ability of the fused features.
- Based on SEFF, we build a multiscale RGB-D saliency detector, which takes images with three different scales and generates high quality saliency results.
- We have conducted extensive experiments on five benchmark datasets, which demonstrates that our method outperforms ten SOTA saliency detectors. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2023</div><img src='papers/ICASSP23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ScaleMix: Intra- And Inter-Layer Multiscale Feature Combination for Change Detection](https://ieeexplore.ieee.org/document/10095962)

Rui Huang, **Qingyi Zhao**, Ruofei Wang, Caihua Liu, Sihua Gao, Yuxiang Zhang, Wei Fan

- We propose an inception difference module to conduct the intra-layer multiscale feature fusion.
- We propose a residual network refinement to capture inter-layer multiscale characteristics.
- Our method can consider both intra- and inter-layer multiscale characteristics simultaneously, which results in superior CD performance over other compared CD methods.
</div>
</div>

- [HQFS: High-Quality Feature Selection for Accurate Change Detection](https://link.springer.com/chapter/10.1007/978-3-031-46305-1_3#citeas), Xing Yan, Qi’ao Xu, **Qingyi Zhao**, Rui Huang, Yuxiang Zhang. ICIG 2023.
- [PAPnet: A Plug-and-play Virus Network for Backdoor Attack](https://ieeexplore.ieee.org/document/10580479), Rui Huang, Zongyu Guo, **Qingyi Zhao**, Wei Fan. CSCWD 2024.
- [C-NERF: Representing Scene Changes as Directional Consistency Difference-based NeRF](https://arxiv.org/abs/2312.02751), Rui Huang , Binbin Jiang, **Qingyi Zhao**, William Wang, Yuxiang Zhang, Qing Guo. Arxiv.

# 🏆 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2022.09 - Present*, Computer Science and Technology, Civil Aviation University of China. 
- *2018.09 - 2022.06*, Internet of Things Engineering, Guangxi University of Science and Technology.

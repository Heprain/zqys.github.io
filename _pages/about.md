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
<h3>A Saliency Enhanced Feature Fusion Based Multiscale RGB-D Salient Object Detection Network</h3>

Rui Huang, **Qingyi Zhao**, Yan Xing, Sihua Gao, Weifeng Xu, Yuxiang Zhang, Wei Fan

[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=GitHub&logoColor=FFFFFF)](https://github.com/Heprain/SEFFSal) [![Paper](https://img.shields.io/badge/-Paper-018EF5?style=flat-square&logo=readdotcv&logoColor=FFFFFF)](https://ieeexplore.ieee.org/document/10447807)

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
- *2024.06* 3rd prize, 2024“Challenge Cup” Tianjin University Student Entrepreneurship Plan Competition, CAUC
- *2023.12* Outstanding Graduate Student Cadre (Top 5%), CAUC
- *2023.12* Kyushu Scholarship (Top 1%), CAUC
- *2022 & 2023* 1st prize (Top 20%), Postgraduate Scholarship, CAUC
- *2021.12* 3rd Prize in the 13th National College Mathematics Competition (Non-mathematics), GXUST
- *2020.11* 2nd Prize in the 2nd Guangxi Collegiate Artificial Intelligence Design Contest, GXUST
- *2019.12* Scholarship of the Autonomous Region People's Government (Top 1%), GXUST
- *2018.12* 1st prize, School-level Outstanding Student Scholarship， GXUST


# 📖 Educations
- *2022.09 - Present*, Computer Science and Technology, Civil Aviation University of China. 
- *2018.09 - 2022.06*, Internet of Things Engineering, Guangxi University of Science and Technology.

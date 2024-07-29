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

I am currently pursuing a master's Degree in computer science at College of Computer Science and Technology, Civil Aviation University of China in Tianjin, China.

My research interests lie in Change Detection(CD), RGB-D Salient Object Detection(RGB-D SOD) and their application in diverse practical scenarios, such as biological and system large models. My focus also extends to developing efficient machine learning systems aimed at expediting the training and inference processing of LMMs (especially LLMs), leveraging expertise in high-performance computing and distributed systems.

Before transferring to the University of Minnesota, I studied at Nanchang University, majoring in Artificial Intelligence in a top-tier class with a School Academic Special Scholarship. I was honored to be advised by Professor Zichen Xu at GOOD LAB starting from March 2022, where my focus was on solving data-centric challenges and building efficient and reliable systems. I was the leader of Nanchang University Supercomputer Cluster Team (NCUSCC) Leader, with experience of ASC22 and SC23(IndySCC).

I was also fortunately recruited as a research assistant at TOP NLP Lab TsinghuaNLP in Beijing from July to September 2023, advised by Professor Zhiyuan Liu, trying to build efficient distributed large language model training framework BMTrain and Develop 10B Chinese LLM CPM-Bee.

I am passionate about open source and firmly believe in its potential to disseminate knowledge widely, leverage technology to lead innovation to the world and contribute to the advancement of human society. I am proud to have garnered over 1000 stars and acquired 155 followers on GitHub. It is gratifying to know that my open-source projects have benefitted numerous individuals, and I have personally gained valuable knowledge from the open-source community.
My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).


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

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2022.09 - Present*, Computer Science and Technology, Civil Aviation University of China. 
- *2018.09 - 2022.06*, Internet of Things Engineering, Guangxi University of Science and Technology.

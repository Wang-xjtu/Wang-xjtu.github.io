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

I am a PhD candidate at the [National Key Laboratory of Human-Machine Hybrid Augmented Intelligence](http://www.aiar.xjtu.edu.cn/), the College of Artificial Intelligence, Xi’an Jiaotong University (西安交通大学人工智能学院), China, under the supervision of [Prof. Meng Yang](https://gr.xjtu.edu.cn/en/web/mengyang). I am also a joint Ph.D student at the [College of Computing and Data Science](https://www.ntu.edu.sg/computing), Nanyang Technological University (南洋理工大学计算与数据科学学院), Singapore, supervised by [Prof. Shijian Lu](https://personal.ntu.edu.sg/shijian.lu/).

My research interest includes computer vision, 3D vision, multi-model vision, and scene depth perception.

**I am currently seeking a <font color="red">postdoctoral position</font>** (expected graduation: 06/2025). If my profile aligns with your interests, please feel free to contact me!


# 🔥 News
- *2024.11*: &nbsp;🎉🎉 I've created my academic homepage. (In preparation) 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-PAMI 2024 (major revision)</div><img src='images/SPNet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Scale Propagation Network for Generalizable Depth Completion](https://arxiv.org/abs/2410.18408)

**Haotian Wang**, Meng Yang, Xinhu Zheng, Gang Hua

<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> SPNet is the first to carefully analyze the significance of scale propagation property in generalizable depth completion. To satisfy this property, we introduce SP-Norm, a novel normalization layer that enhances generalizability and ensures efficient convergence. Coupled with our insights for ConvNeXt V2, SPNet achieves impressive generalization across a wide range of unseen scenarios. [**Project Page**](https://github.com/Wang-xjtu/SPNet)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-PAMI 2024</div><img src='images/G2-monodepth.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[G2-MonoDepth: A General Framework of Generalized Depth Map Inference from Monocular RGB-X Data](https://ieeexplore.ieee.org/abstract/document/10373158)

**Haotian Wang**, Meng Yang, Nanning Zheng

<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> G2-MonoDepth investigated a novel unified task of single-view depth inference for various robots, which may be equipped with a range of sensors, such as cameras, LiDAR, ToF, or their combinations, and operate in diverse indoor and outdoor environments. Our work introduced a general and generalized framework to robustly perform in this challenging scenario by comprehensively exploring data preparation, network architecture, and loss function. [**Project Page**](https://github.com/Wang-xjtu/G2-MonoDepth)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-IP 2023</div><img src='images/CRF.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[RGB-Guided Depth Map Recovery by Two-Stage Coarse-to-Fine Dense CRF Models](https://ieeexplore.ieee.org/abstract/document/10043681)

**Haotian Wang**, Meng Yang, Ce Zhu, Nanning Zheng

<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> This work aims to effectively eliminate large erroneous regions in depth maps captured by low-cost depth sensors without training. It is achieved by an optimization-based approach employing the fully connected conditional random field (dense CRF) model to integrate local and global contexts from RGB-D pairs in a coarse-to-fine manner, achieving superior performance even than learning-based techniques. [**Project Page**](https://github.com/Wang-xjtu/C2F-DenseCRF-Depth)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-IP 2022</div><img src='images/SSIM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Depth Map Recovery based on a Unified Depth Boundary Distortion Model](https://ieeexplore.ieee.org/abstract/document/9940165)

**Haotian Wang**, Meng Yang, Xuguang Lan, Ce Zhu, Nanning Zheng

<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> This work is the first to establish a unified model capable of identifying all kinds of distorted boundaries in depth maps, including missing, fake, and misaligned boundaries. Leveraging this unified model, the proposed pipeline iteratively optimizes low-quality depth maps, resulting in high-quality depth maps with accurate boundaries. [**Project Page**](https://github.com/Wang-xjtu/Unified_DBDM)
</div>
</div>

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2021.09 - 2025.06 (now)*, Ph.D., College of Artificial Intelligence, Xi’an Jiaotong University, China. 
- *2023.12 - 2024.12*, Joint Ph.D., College of Computing and Data Science, Nanyang Technological University, Singapore.
- *2013.09 - 2017.06*, B.S., School of Electrical and Electronic Engineering, North China Electric Power University, China.

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.

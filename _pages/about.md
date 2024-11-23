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

I am a Ph.D. candidate at the [National Key Laboratory of Human-Machine Hybrid Augmented Intelligence](http://www.aiar.xjtu.edu.cn/), the College of Artificial Intelligence, Xi’an Jiaotong University (西安交通大学人工智能学院), China, under the supervision of [Prof. Meng Yang](https://gr.xjtu.edu.cn/en/web/mengyang). I am also a joint Ph.D. student at the [College of Computing and Data Science](https://www.ntu.edu.sg/computing), Nanyang Technological University (南洋理工大学计算与数据科学学院), Singapore, supervised by [Prof. Shijian Lu](https://personal.ntu.edu.sg/shijian.lu/).

My research interests include computer vision, 3D vision, multi-modal vision, and scene depth perception. I aim to develop advanced techniques that enable autonomous agents to effectively perceive real-world environments, particularly in dynamic and open settings.

**I am currently seeking a <font color="red">postdoctoral position</font>** (expected graduation: 06/2025). If my profile aligns with your interests, please feel free to contact me!


# 🔥 News
- *2024.11*: &nbsp;🎉🎉 I've created my academic homepage.

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

<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> This work aims to effectively eliminate large erroneous regions in depth maps captured by low-cost depth sensors without training. It is achieved by an optimization-based approach employing the fully connected conditional random field (dense CRF) model to integrate local and global contexts from RGB-D pairs in a coarse-to-fine manner, achieving superior performance and even outperforming learning-based techniques. [**Project Page**](https://github.com/Wang-xjtu/C2F-DenseCRF-Depth)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-IP 2022</div><img src='images/SSIM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Depth Map Recovery based on a Unified Depth Boundary Distortion Model](https://ieeexplore.ieee.org/abstract/document/9940165)

**Haotian Wang**, Meng Yang, Xuguang Lan, Ce Zhu, Nanning Zheng

<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> This work is the first to establish a unified model capable of identifying all kinds of distorted boundaries in depth maps, including missing, fake, and misaligned boundaries. Leveraging this unified model, we developed a filter-based pipeline to iteratively optimize low-quality depth maps, resulting in high-quality depth maps with accurate boundaries. [**Project Page**](https://github.com/Wang-xjtu/Unified_DBDM)
</div>
</div>

# 📖 Educations
- *2019.09 - 2025.06*, *Ph.D.*, College of Artificial Intelligence, Xi’an Jiaotong University, China. 
- *2023.12 - 2024.12*, *Joint Ph.D.*, College of Computing and Data Science, Nanyang Technological University, Singapore.
- *2013.09 - 2017.06*, *B.S.*, School of Electrical and Electronic Engineering, North China Electric Power University, China.

# 🎖 Honors and Awards
- *2024.10*, Outstanding Graduate Student, XJTU.
- *2024.09*, Baosheng Hu Scholarship (Top 5%, 1st Place), XJTU.
- *2024.01*, Academic Star of the [IAIR](http://www.aiar.xjtu.edu.cn/) (Top 1%), XJTU.
- *2023.10*, Academic Scholarship (Top 5%, 1st Place), XJTU.
- *2023.10*, Qianheng Huang Scholarship, XJTU.
- *2023.07*, Joint Ph.D. Scholarship, China Scholarship Council (CSC).
- *2023.07*, Invited Oral Presenter, XJTU.
- *2015.11*, College Scholarship, [NCEPU](https://english.ncepu.edu.cn/).

# 📕 Patents
- *2024*, Meng Yang\*, **Haotian Wang**, and Nanning Zheng, "Zero-Shot Depth Completion Based on Scale Propagation Normalization Layer: Method and System", *China Patent*, 2023101807430.
- *2023*, Meng Yang\*, **Haotian Wang**, and Nanning Zheng, "Generalizable Depth Map Inference with Single-View: Method and System," *China Patent*, 2023101807430.
- *2021*, Meng Yang\*, **Haotian Wang**, and Nanning Zheng, "Depth Map Structure Restoration Method based on the Fully Connected Conditional Random Field Model," *China Patent*, ZL202111057715.2.
- *2020*, Meng Yang\*, **Haotian Wang**, and Nanning Zheng, "An Iterative Method of Depth Map Structure Restoration based on Structural Similarity between RGB and Depth," *China Patent*, ZL200010007508.X.

# 🔨 Projects
- *2022.12 - 2025.12*, *Core Member*, "A General Model of Single-View 3D Perception for Multi-Modal Autonomous Agents", National Natural Science Foundation of China.
- *2022.01 - 2023. 12*, *Project Leader*, "A General Depth Perception Model", Research Foundation of XJTU.

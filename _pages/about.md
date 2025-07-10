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

I am currently a postdoctoral researcher at the [Intelligent Transportation (Systems Hub)](https://www.hkust-gz.edu.cn/academics/hubs-and-thrust-areas/systems-hub/intelligent-transportation/), The Hong Kong University of Science and Technology (Guangzhou).
I received my Ph.D. from the [National Key Laboratory of Human-Machine Hybrid Augmented Intelligence](http://www.aiar.xjtu.edu.cn/), Xi’an Jiaotong University.
During my Ph.D., I was also a visiting student at the [College of Computing and Data Science](https://www.ntu.edu.sg/computing), Nanyang Technological University, under the supervision of [Prof. Shijian Lu](https://personal.ntu.edu.sg/shijian.lu/).

My research interests lie in computer vision, 3D vision, and spatial perception and understanding. I aim to develop advanced techniques that enable autonomous agents to perceive and understand real-world environments effectively, especially in dynamic and open-world settings.


# 🔥 News
- *2025.07*: &nbsp;🎉🎉 One paper is accepted in ICCV 2025!
- *2024.12*: &nbsp;🎉🎉 One paper is accepted in T-PAMI!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/PacGDC.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PacGDC: Label-Efficient Generalizable Depth Completion with Projection Ambiguity and Consistency ](https://ieeexplore.ieee.org/document/10786388)

**H. Wang**, A. Xiao, X. Zhang, M. Yang, and S. Lu

<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> PacGDC is a label-efficient technique that enhances data diversity with minimal annotation effort for generalizable depth completion. It builds on novel insights into inherent ambiguities and consistencies in object shapes and positions during 2D-to-3D projection, allowing the synthesis of numerous pseudo geometries for the same visual scene. These insights contribute to the model’s strong generalizability across diverse scene semantics/scales and depth sparsity/patterns under both zero-/few-shot settings. [**Project Page**](https://github.com/Wang-xjtu/PacGDC)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-PAMI 2025</div><img src='images/SPNet.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Scale Propagation Network for Generalizable Depth Completion](https://ieeexplore.ieee.org/document/10786388)

**H. Wang**, M. Yang, X. Zheng, and G. Hua

<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> SPNet is the first to carefully analyze the significance of scale propagation property in generalizable depth completion. To satisfy this property, we introduce SP-Norm, a novel normalization layer that enhances generalizability and ensures efficient convergence. Coupled with our insights for ConvNeXt V2, SPNet achieves impressive generalization across a wide range of unseen scenarios. [**Project Page**](https://github.com/Wang-xjtu/SPNet)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-PAMI 2024</div><img src='images/G2-monodepth.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[G2-MonoDepth: A General Framework of Generalized Depth Map Inference from Monocular RGB-X Data](https://ieeexplore.ieee.org/abstract/document/10373158)

**H. Wang**, M. Yang, N. Zheng

<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> G2-MonoDepth investigated a novel unified task of single-view depth inference for various robots, which may be equipped with a range of sensors, such as cameras, LiDAR, ToF, or their combinations, and operate in diverse indoor and outdoor environments. Our work introduced a general and generalized framework to robustly perform in this challenging scenario by comprehensively exploring data preparation, network architecture, and loss function. [**Project Page**](https://github.com/Wang-xjtu/G2-MonoDepth)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-IP 2023</div><img src='images/C2F.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[RGB-Guided Depth Map Recovery by Two-Stage Coarse-to-Fine Dense CRF Models](https://ieeexplore.ieee.org/abstract/document/10043681)

**H. Wang**, M. Yang, C. Zhu, N. Zheng

<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> This work aims to effectively eliminate large erroneous regions in depth maps captured by low-cost depth sensors without training. It is achieved by an optimization-based approach employing the fully connected conditional random field (dense CRF) model to integrate local and global contexts from RGB-D pairs in a coarse-to-fine manner, achieving superior performance and even outperforming learning-based techniques. [**Project Page**](https://github.com/Wang-xjtu/C2F-DenseCRF-Depth)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-IP 2022</div><img src='images/SSIM.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Depth Map Recovery based on a Unified Depth Boundary Distortion Model](https://ieeexplore.ieee.org/abstract/document/9940165)

**H. Wang**, M. Yang, X. Lan, C. Zhu, N. Zheng

<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> This work is the first to establish a unified model capable of identifying all kinds of distorted boundaries in depth maps, including missing, fake, and misaligned boundaries. Leveraging this unified model, we developed a filter-based pipeline to iteratively optimize low-quality depth maps, resulting in high-quality depth maps with accurate boundaries. [**Project Page**](https://github.com/Wang-xjtu/Unified_DBDM)
</div>
</div>

# 📖 Educations
- *2019.09 - 2025.06*, **Ph.D.**, College of Artificial Intelligence, Xi’an Jiaotong University, China. 
- *2023.12 - 2024.12*, **Visiting Ph.D.**, College of Computing and Data Science, Nanyang Technological University, Singapore.
- *2013.09 - 2017.06*, **B.S.**, School of Electrical and Electronic Engineering, North China Electric Power University, China.

# 🏅 Honors and Awards
- *2025.06*, Outstanding Graduate, XJTU.
- *2025.01*, Academic Star of the [IAIR](http://www.aiar.xjtu.edu.cn/) (Top 1%), XJTU.
- *2024.10*, Excellent Postgraduate Student, XJTU.
- *2024.09*, Baosheng Hu Scholarship (Top 5%, 1st Place), XJTU.
- *2024.01*, Academic Star of the [IAIR](http://www.aiar.xjtu.edu.cn/) (Top 1%), XJTU.
- *2023.10*, Academic Scholarship (Top 5%, 1st Place), XJTU.
- *2023.10*, Qianheng Huang Scholarship, XJTU.
- *2023.07*, Joint Ph.D. Scholarship (6700 people in China), China Scholarship Council (CSC).
- *2023.07*, Invited Oral Presenter, XJTU.
- *2015.11*, College Scholarship, [NCEPU](https://english.ncepu.edu.cn/).

# 📕 Patents
- *2024*, M. Yang\*, **H. Wang**, N. Zheng. Zero-Shot Depth Completion Based on Scale Propagation Normalization Layer: Method and System. *China Patent*, No. 2023101807430.
- *2023*, M. Yang\*, **H. Wang**, N. Zheng. Generalizable Depth Map Inference with Single-View: Method and System. *China Patent*, No. 2023101807430.
- *2021*, M. Yang\*, **H. Wang**, N. Zheng. Depth Map Structure Restoration Method based on the Fully Connected Conditional Random Field Model. *China Patent*, No. ZL202111057715.2.
- *2020*, M. Yang\*, **H. Wang**, N. Zheng. An Iterative Method of Depth Map Structure Restoration based on Structural Similarity between RGB and Depth. *China Patent*, No. ZL200010007508.X.

# 🔨 Projects
- *2022.12 - 2025.06*, A General Model of Single-View 3D Perception for Multi-Modal Autonomous Agents. Responsibility: *Core Member*, Source: *No. 62373298, The National Natural Science Foundation of China*.
- *2022.01 - 2023. 12*, A General Depth Perception Model. Responsibility: *Project Leader*, Source: *No. xzy022022061, The Basic Research Foundation of XJTU*.

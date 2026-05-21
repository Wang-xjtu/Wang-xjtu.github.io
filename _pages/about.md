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

I am currently a postdoctoral researcher with the [Thrust of Intelligent Transportation](https://www.hkust-gz.edu.cn/academics/hubs-and-thrust-areas/systems-hub/intelligent-transportation/) at The Hong Kong University of Science and Technology (Guangzhou), supervised by [Prof. Xinhu Zheng](https://facultyprofiles.hkust-gz.edu.cn/faculty-personal-page?id=168). I am also an Honorary Postdoctoral Fellow affiliated with the Department of Information Engineering at The Chinese University of Hong Kong, advised by [Prof. Angela Yingjun Zhang](https://staff.ie.cuhk.edu.hk/~yjzhang/index.html).

Before that, I received my Ph.D. from the [College of Artificial Intelligence](http://www.aiar.xjtu.edu.cn/), Xi’an Jiaotong University, under the supervision of [Prof. Meng Yang](http://www.lianpp.com/xjtu/mu_gr/web/mengyang). During my Ph.D., I was also a visiting student at the [College of Computing and Data Science](https://www.ntu.edu.sg/computing), Nanyang Technological University, supervised by [Prof. Shijian Lu](https://personal.ntu.edu.sg/shijian.lu/).

My research interests lie in spatial perception and understanding. I aim to develop advanced techniques that enable autonomous agents to perceive and understand real-world environments effectively, especially in dynamic and open-world settings.


# 🔥 News
- *2026.05*: &nbsp;🎉🎉 Our paper UniT is now available on arXiv!
- *2025.07*: &nbsp;🎉🎉 One paper is accepted in ICCV 2025!
- *2024.12*: &nbsp;🎉🎉 One paper is accepted in T-PAMI!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2026</div><img src='images/PacGDC.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[UniT: Unified Geometry Learning with Group Autoregressive Transformer](https://arxiv.org/abs/2605.21131)

**H. Wang**, Y. Huang, Z. Kuang, H. Lu, X. Zheng. M. Yang, and G. Hua

<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> UniT is a unified feed-forward model that reformulates a wide range of geometry perception capabilities into a single framework, covering diverse view configurations, modality combinations, metric-scale perception, and long-horizon scalability. It supports both online and offline inference over an arbitrary number of views, flexibly incorporates auxiliary modalities such as camera parameters and depth maps, recovers geometry in metric scale measured in meters, and maintains bounded complexity over long horizons in in-the-wild environments. [**Project Page**](https://sc2i-hkustgz.github.io/UniT/)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/PacGDC.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PacGDC: Label-Efficient Generalizable Depth Completion with Projection Ambiguity and Consistency](https://arxiv.org/abs/2507.07374)

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

# 📖 Academic Service
- **Conference Reviews**: CVPR, ICCV, ECCV, AAAI, ACM'MM, ICRA
- **Journal Reviews**: TPAMI, TIP


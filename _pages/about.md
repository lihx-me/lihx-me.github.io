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

I am a first-year PhD student at [The Hong Kong University of Science and Technology (HKUST)](https://hkust.edu.hk/zh-hant) (2025 Fall), supervised by [Long Chen](https://scholar.google.com/citations?user=-gtmMpIAAAAJ). Before that, I obtained my M.S. degree from [Peking University (PKU)](https://www.pku.edu.cn/), supervised by [Yuexian Zou](https://scholar.google.com/citations?user=sfyr7zMAAAAJ&hl=zh-CN).

My research interests include Visual Generation and Multi-modal Large Language Model.

If interested in collaboration or discussion, please email me (lihxxxxxx@gmail.com).

# 🔥 News
- *2025.08*: One paper is accepted to SIGGRAPH Asia 2025.
- *2025.02*: One paper is accepted to IEEE TCSVT. 
- *2025.01*: One paper is accepted to ICLR 2025. 
- *2024.12*: One paper is accepted to IEEE TMI.
- *2024.08*: Two papers are accepted to ECCV 2024.
- *2024.07*: One paper is accepted to ACM MM 2024.
- *2023.12*: Two papers are accepted to AAAI 2024.
- *2023.07*: Two papers are accepted to ICCV 2023. G2L is accepted as Oral.

# 📝 Selected Publications
See full list at [Google Scholar](https://scholar.google.com/citations?view_op=list_works&hl=zh-CN&authuser=1&hl=zh-CN&user=U4AwycUAAAAJ&authuser=1). (<sup>\*</sup>equal contribution, <sup>#</sup>corresponding author)

<!-- arXiv2025 GIR-Bench -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv2025</div><img src='images/GIR-Bench.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[GIR-Bench: Versatile Benchmark for Generating Images with Reasoning](https://arxiv.org/abs/2510.11026)

**Hongxiang Li**<sup>\*</sup>, Yaowei Li<sup>\*</sup>, Bin Lin, Yuwei Niu, Yuhang Yang, Xiaoshuang Huang, Jiayin Cai, Xiaolong Jiang, Yao Hu, Long Chen<sup>#</sup> <br>

<a href="https://hkust-longgroup.github.io/GIR-Bench">Project</a>, <a href="https://arxiv.org/abs/2510.11026">Paper</a>, <a href="https://github.com/HKUST-LongGroup/GIR-Bench">Code</a> <a href="https://huggingface.co/datasets/lihxxx/GIR-Bench">Data</a> <br>

arXiv, 2025
</div>
</div>


<!-- ICLR2025 DisPose -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR2025</div><img src='images/ICLR2025_DisPose.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[DisPose: Disentangling Pose Guidance for Controllable Human Image Animation](https://arxiv.org/abs/2412.09349)

**Hongxiang Li**, Yaowei Li, Yuhang Yang, Junjie Cao, Zhihong Zhu, Xuxin Cheng, Long Chen<sup>#</sup> <br>

<a href="https://lihxxx.github.io/DisPose/">Project</a>, <a href="https://arxiv.org/abs/2412.09349">Paper</a>, <a href="https://github.com/lihxxx/DisPose">Code</a> <br>

International Conference on Learning Representations (ICLR), 2025
</div>
</div>

<!-- ECCV2024 KDProR-->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV2024</div><img src='images/ECCV2024_KDProR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[KDProR: A Knowledge-Decoupling Probabilistic Framework for Video-Text Retrieval](https://eccv.ecva.net/virtual/2024/poster/1475)

Xianwei Zhuang<sup>\*</sup>, <b>Hongxiang Li</b><sup>\*</sup>, Xuxin Cheng, Zhihong Zhu, Yuxin Xie, Yuexian Zou<sup>#</sup> <br>

<a href="https://eccv.ecva.net/virtual/2024/poster/1475">Paper</a>, <a href="https://github.com/mengchuang123/KDProR">Code</a> <br>

European Conference on Computer Vision (ECCV), 2024
</div>
</div>

<!-- ECCV2024 UPRet-->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV2024</div><img src='images/ECCV2024_UPRet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Uncertainty-aware Sign Language Video Retrieval with Probability Distribution Modeling](https://arxiv.org/abs/2405.19689)

Xuan Wu<sup>\*</sup>, <b>Hongxiang Li</b><sup>\*</sup>, Yuanjiang Luo, Xuxin Cheng, Xianwei Zhuang, Meng Cao, Keren Fu<sup>#</sup> <br>

<a href="https://arxiv.org/abs/2405.19689">Paper</a>, <a href="https://github.com/xua222/UPRet">Code</a> <br>

European Conference on Computer Vision (ECCV), 2024
</div>
</div>

<!-- AAAI2024 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI2024</div><img src='images/aaai2024-acnet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Exploiting Auxiliary Caption for Video Grounding](https://ojs.aaai.org/index.php/AAAI/article/view/29812)

**Hongxiang Li**, Meng Cao, Xuxin Cheng, Yaowei Li, Zhihong Zhu, Yuexian Zou<sup>#</sup> <br>

<a href="https://ojs.aaai.org/index.php/AAAI/article/view/29812">Paper</a> <br>

AAAI Conference on Artificial Intelligence (AAAI), 2024
</div>
</div>

<!-- ICCV2023 G2L -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV2023 Oral</div><img src='images/iccv2023-g2l.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[G2L: Semantically Aligned and Uniform Video Grounding via Geodesic and Game Theory](https://arxiv.org/abs/2307.14277)

**Hongxiang Li**, Meng Cao, Xuxin Cheng, Yaowei Li, Zhihong Zhu, Yuexian Zou<sup>#</sup> <br>

<a href="https://arxiv.org/abs/2307.14277">Paper</a> <br>

International Conference on Computer Vision (ICCV), 2023 (Oral)
</div>
</div>

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->

# 💻 Internships
- *2023 - 2024* Baidu VIS, China.
- *2023 - 2023* Tencent YouTu Lab, China.
- *2021 - 2022* SenseTime Research, China.

# 🎖 Honors and Awards
- *2024* Merit Student, Peking University. 
- *2023* Merit Student, Peking University. 
- *2020* National Scholarship. 

<!-- # 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- # Academic Services
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=300&t=tt&d=6QsWf4KK-03cp2_GNpoY-H9i_4ZaVbHSNRup-os9Ras&co=2d78ad&cmo=3acc3a&cmn=ff5353&ct=ffffff'></script>

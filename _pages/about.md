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

I obtained my Bachelor's degree in Telecommunication Engineering from the School of Electronic Information and Communications at [Huazhong University of Science and Technology (HUST)](https://www.hust.edu.cn/). I then completed my Master’s degree in Telecommunication Engineering at [Politecnico di Milano](https://www.polimi.it/), graduating **cum laude**.

In May 2025, I joined the [**Bonsai (Broadband Optical Networks, Security and Advanced Internet) Lab**](https://www.bonsai.deib.polimi.it/) at Politecnico di Milano as a PhD student, working under the supervision of [Prof. Massimo Tornatore](https://tornatore.faculty.polimi.it/) and [Prof. Francesco Musumeci](https://musumeci.faculty.polimi.it/).

My research interests lie in **network optimization and planning**, with a particular focus on **optical networks** and **quantum networks**, including topics such as **quantum key distribution (QKD)** and **entanglement routing**. I am also currently working on **communication-efficient distributed training** for large-scale AI models, aiming to reduce the communication overhead in distributed machine learning systems.


<!--My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).-->


# 🔥 News
- *2025.12*: &nbsp;🎉 I will present my paper “SCALE-CCL: A Scalable Collective Communication Library for Wide-Area Distributed Training” at the CoNEXT INET4AI Workshop 2025. This is my first publication on cross–data center collective communication!
- *2025.06*: &nbsp;🎉 Our paper “Power Consumption Analysis of QKD Networks under Different Protocols and Detector Configurations” was accepted for oral presentation at ECOC 2025!
- *2025.04*: &nbsp;🎓🎉 Successfully completed my Master’s degree in Telecommunication Engineering at Politecnico di Milano, graduating with the maximum grade **110/110 cum laude**!
- *2024.06*: &nbsp;🎉 Our paper "Shared-Protected Backup Paths Assignment with Mode Group Division Multiplexing in Optical Networks" was accepted at ECOC 2024!



# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CoNEXT 2025</div><img src='images/Architecture across DCs.jpg' alt="SCALE-CCL" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SCALE-CCL: A Scalable Collective Communication Library for Wide-Area Distributed Training](https://dl.acm.org/doi/10.1145/3769695.3771677)

**Jiaheng Xiong**, Qiaolun Zhang, Paolo Medagliani, Michele Ferrero, Xiaomin Liu, Meng Lian, Nicola Di Cicco, Baosen Zhao, Mëmëdhe Ibrahimi, Francesco Musumeci, Massimo Tornatore

- Accepted at the CoNEXT INET4AI Workshop 2025, co-located with ACM CoNEXT 2025.
- This work introduces SCALE-CCL, a wide-area–aware collective communication library that efficiently generates communication schedules for AllGather across geo-distributed datacenters. By combining topology-aware decomposition with lightweight schedule synthesis, SCALE-CCL enables scalable and adaptable WAN-level collective communication.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECOC 2025</div><img src='images/Bypass and Nobypass.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Power Consumption Analysis of QKD Networks under Different Protocols and Detector Configurations](https://rboutaba.cs.uwaterloo.ca/Papers/Conferences/2023/xiong-qkd25.pdf)

**Jiaheng Xiong**, Qiaolun Zhang, Yoann Piétri, Raja Yehia, Raouf Boutaba, Francesco Musumeci, Massimo Tornatore

<!--[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>-->
- Accepted by European Conference on Optical Communication as Oral (ECOC 2025).
- This work proposed a power- and spectrum-aware resource allocation algorithm for QKD networks, optimizing protocol selection, detector placement, and routing to minimize energy consumption under realistic traffic and topology scenarios.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECOC 2024</div><img src='images/Example of DPP and SPP int MGDM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Shared-Protected Backup Paths Assignment with Mode Group Division Multiplexing in Optical Networks](https://ieeexplore.ieee.org/document/10926129)

**Jiaheng Xiong**, Qiaolun Zhang, Ruikun Wang, Alberto Gatto, Francesco Musumeci, Massimo Tornatore

<!--[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>-->
- Accepted by European Conference on Optical Communication (ECOC 2024).
- This work proposed a shared-protected backup path assignment algorithm leveraging Mode Group Division Multiplexing (MGDM) to enhance spectrum efficiency and reduce MIMO complexity in optical networks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CNSM 2023</div><img src='images/Fig3-globecom.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Adaptive entanglement routing for quantum networks with cutoff](https://ieeexplore.ieee.org/document/10327909)

**Jiaheng Xiong**, Qiaolun Zhang, Alberto Gatto, Francesco Musumeci, Raouf Boutaba, Massimo Tornatore
- Accepted by International Conference on Network and Service Management (CNSM 2023).
- This work proposed adaptive entanglement routing algorithms for quantum networks, which leverage multi-path redundancy and high-success-probability selection strategies to effectively reduce entanglement establishment latency.
<!--[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>-->
</div>
</div>



<!--# 🎖 Honors and Awards-->
<!--- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. -->
<!--- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. -->

## 📖 Educations

- *2025.05 – present*, Ph.D student in Information Technology, **Politecnico di Milano**, Milan, Italy.  
- *2022.09 – 2025.04*, M.Sc in Telecommunication Engineering (cum laude), **Politecnico di Milano**, Milan, Italy.  
- *2017.09 – 2021.06*, B.Eng in Telecommunication Engineering, **Huazhong University of Science and Technology**, Wuhan, China.

<!--# 💬 Invited Talks-->
<!--- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. -->
<!--- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)-->

## 💻 Work Experience
- *2021.08 - 2022.03*, Display Software Driver Engineer, OPPO, China.

<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=080808&w=200&t=tt&d=Gi8B3_EApaCi2filpg_cUbG20TcOcyLhM14xp7mb7ew&co=ffffff&cmo=3acc3a&cmn=ff5353&ct=808080'></script>
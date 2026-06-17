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

Hello! I am Yanran Liu. If you are interested in academic collaboration, please feel free to contact me at [yanranliu7-c@my.cityu.edu.hk](mailto:yanranliu7-c@my.cityu.edu.hk).

- 🎓 I will join the Department of Biomedical Sciences at [City University of Hong Kong (香港城市大学)](https://www.cityu.edu.hk/) as a PhD student in September 2026 under the supervision of [Prof. Lingxi CHEN (陈凌曦)](https://www.cityu.edu.hk/bms/profile/lingxichen.htm). I will be a member of the [CompBioClub](https://compbioclub.github.io/), where I am currently working as a Research Assistant.

- 🔬 From April 2024 to April 2026, I was a Visiting Student Researcher at the School of Information Science and Technology, Great Bay University, supervised by [Prof. Xubin ZHENG (郑旭彬)](https://kimxbzheng.github.io/).

- 📚 I received my M.Sc. in Information Systems from City University of Hong Kong in October 2025 and my B.Eng. in Financial Engineering from Dalian Maritime University in June 2023.

# 🔍 Research Interests

My research interests mainly include AI for Biomedical Science and Bioinformatics, specifically in:
- Subcellular Spatial Transcriptomics
- AI in Healthcare
- Online Biomedical Platforms


# 🔥 News
- *2026.05*: &nbsp;🚀 Huge congratulations! Our spatial transcriptomics super-resolution model, **SRast**, has been accepted to **KDD 2026 Oral** (**<6.1%**)!
- *2026.05*: &nbsp;🎓🎉 Delighted and grateful to have accepted a **PhD offer from City University of Hong Kong (CityU HK)** under **Prof. Lingxi CHEN**. Looking forward to beginning this new chapter in the CompBioClub!
- *2026.04*: &nbsp;🎉 Joining **City University of Hong Kong (CityU HK)** in the CompBioClub under **Prof. Lingxi CHEN**. Another beautiful chapter of my research journey begins here!
- *2026.04*: &nbsp;🌟 Concluding a rewarding research journey at **Great Bay University (GBU)** under **Prof. Xubin ZHENG**, with deep gratitude for the mentorship and collaborations along the way.
- *2026.02*: &nbsp;🎉 Our work on influenza prediction has been published in **BMC Public Health**!
- *2025.11*: &nbsp;🚀 Huge news! Our spatial multi-omics model, GROVER, has been accepted by **AAAI 2026**!
- *2025.10*: &nbsp;🎊 Triple win at **BIBM 2025**! Thrilled to announce that our work BioLinkGPT is headed to **BIBM 2025**!
- *2025.10*: &nbsp;✨ Our project SVP has also been accepted by **BIBM 2025**!
- *2025.10*: &nbsp;� Another win! Our gene regulatory relationship prediction model has been accepted by **BIBM 2025**.
- *2025.10*: &nbsp;🎓🥳 Celebrated my **Master's graduation at CityU HK**! A wonderful journey comes to an end!
- *2024.12*: &nbsp;🎉 Our first spatial multi-omics model, PRAGA, was accepted by **AAAI 2025**!
- *2024.12*: &nbsp;✨ Back to the research frontline at **GBU**!
- *2024.09*: &nbsp;🎓 A new chapter begins! Officially started my **Master's journey at CityU HK**.
- *2024.08*: &nbsp;👋 Temporarily bidding farewell to GBU. New adventures await!
- *2024.04*: &nbsp;⚓ Joined **Great Bay University (GBU)**. This is where my research dream officially sets sail!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">BIBM 2025</div><img src='images/bibm_framework.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Predicting Gene Regulatory Relationship in Cancer Using LLM and Graph Neural Network from Known Regulations

**Yanran Liu**, Dian Meng, Xinlei Huang, Yidi Wang, et al.

**BIBM 2025(CCF-B Conference)**

- Extracted gene regulatory relationships from 31,000+ PubMed abstracts using LLM to construct cancer-specific networks.
- Applied Magnetic Signed GNN for link prediction to discover novel regulatory relationships.
- Achieved SOTA performance with predictions validated by external cell line data.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">BMC Public Health</div><img src='images/bmc_framework.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Two-Stage Hybrid Model for Influenza Trend Forecasting and Key Driver Analysis

**Yanran Liu**, Jingxia Guo, Xubin Zheng, et al.

**BMC Public Health(JCR Q1 Journal)**

- Analyzed 2011-2023 influenza data in Xinjiang with demographic and virological drivers across pre/post-COVID periods.
- Developed LSTM-GBR hybrid model integrating key drivers via systematic feature engineering.
- Identified school-age cases and viral strain proportions as primary predictors of outbreak severity.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/praga_framework.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

PRAGA: Prototype-aware Graph Adaptive Aggregation for Spatial Multi-modal Omics Analysis

Xinlei Huang, Zhiqi Ma, Dian Meng, **Yanran Liu**, et al.

**AAAI 2025(CCF-A Conference)**

- Proposed dynamic graph construction to capture latent semantic relations that fixed KNN graphs fail to model due to sequencing perturbations.
- Designed cross-modal learning module to integrate spatial information and denoise perturbations from sequencing.
- Introduced Bayesian GMM-based prototype contrastive learning to optimize representations without known class priors, achieving SOTA over 7 baselines.
</div>
</div>

- <span class="badge-inline">AAAI 2026</span> GROVER: Graph-guided Representation of Omics and Vision with Expert Regulation for Adaptive Spatial Multi-omics Fusion, Yongjun Xiao, Dian Meng, Xinlei Huang, **Yanran Liu**, et al.
- <span class="badge-inline">BIBM 2025</span> SVP: Support Vector Gene Pair as Biomarker Selection for Breast Cancer, Yijun Zhou, Qiyi Chen, Dian Meng, **Yanran Liu**, Jinchao Feng, Xubin Zheng.
- <span class="badge-inline">BIBM 2025</span> BioLinkGPT: Predicting Missing TF-target Gene Interactions Using Graph Neural Networks with Large Language Model, Zhihua Du, Weiliang Huang, **Yanran Liu**, et al.

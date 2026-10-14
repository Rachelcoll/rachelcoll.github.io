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

Hi! I am an undergraduate student major in computer science at National University of Singapore. I am fortunate to be supervised by [Prof. Bryan Low](https://www.comp.nus.edu.sg/~lowkh/) and [Prof. Jiawei Zhang](https://jwzhang.netlify.app/#about).

My research focuses on data valuation, LLM efficiency, and reasoning. I am generally interested in mechanisms that improves model capabilities and investigating the reasons behind. I enjoy discovering diverse research directions and collaborating with researchers across different fields.

I am currently seeking research internship opportunities and PhD/RA positions for Fall 2027. Feel free to reach out if you are interested in collaboration or potential opportunities.


# 🔥 News
- *2026.4*: &nbsp;🎉🎉 My first paper "EULoInf: Efficient Hessian-Free Entropy Based Uncertainty-Aware Data Influence Approximation" is accepted to ACL 2026.

# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026 Findings</div><img src='images/data_selection_repsim.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
EULoInf: Efficient Hessian-Free Entropy Based Uncertainty-Aware Data Influence Approximation

<b>Runxin Cai</b><sup>*</sup>, Jingtan Wang<sup>*</sup>, Bryan Kian Hsiang Low

[**Paper**](https://aclanthology.org/2026.findings-acl.1839.pdf) |
[**Code**](https://github.com/Rachelcoll/EULoInf.git)

TL;DR: EULoInf is an efficient Hessian-free influence function approximation based on predictive uncertainty. EULoInf avoids iHVP computation, effectively reducing the iHVP-induced quadratic complexity in model parameters to linear time. It reaches perfect balance between effectiveness and efficiency, reducing computational time and memory usage by over 50%.
  </div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/meth.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Beyond Fixed Divergences: Overlap-Adaptive Distillation for Speculative Draft Models

<b>Runxin Cai</b>, Shutong Wu, Guang Lin, Jiawei Zhang

TL;DR: On-policy distillation generally results in draft model with better acceptance performance in speculative decoding. We examine how OPD benefits acceptance improvement and its limitations by characterizing typical rejection pattern, and analyze failure modes and weaknesses of commonly used training objectives in on-policy training of draft model. Based on the analysis, we proposed OWL, a acceptance-oriented training objective that reduced token rejection with overlap-adaptive weight.
  </div>
</div>

# 📖 Educations
- *2023.8 - 2027.5 (expected)*, Undergraduate Student, School of Computing, National University of Singapore
- *2026.1 - 2026.3*, UCEAP Exchange Student, Univeristy of California, Davis

# 🏆 Honors and Awards
- Dean's List, National University of Singapore, 2024.1
- Dean's List, National University of Singapore, 2024.6


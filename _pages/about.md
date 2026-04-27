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

My research focuses on data valuation, LLM efficiency, and reasoning. I am generally interested in mechanisms that improves model capabilities and investigate the reasons behind. I enjoy discovering diverse research directions and collaborating with researchers across different fields.

I am currently seeking research internship opportunities and PhD/RA positions for Fall 2027. Feel free to reach out if you are interested in collaboration or potential opportunities.


# 🔥 News
- *2026.4*: &nbsp;🎉🎉 My first paper "EULoInf: Efficient Hessian-Free Entropy Based Uncertainty-Aware Data Influence Approximation" is accepted to ACL 2026.

# 📝 Publications 
<div class='paper-box' style="position: relative; padding: 15px;">
  
  <div class="badge" style="position: absolute; top: 15px; left: 15px;">ACL 2026 Findings</div>

  <div class='paper-box-text' markdown="1" style="width: 100%; padding-top: 35px;">

EULoInf: Efficient Hessian-Free Entropy Based Uncertainty-Aware Data Influence Approximation

<b>Runxin Cai</b><sup>*</sup>, Jingtan Wang<sup>*</sup>, Bryan Kian Hsiang Low

[**Paper**](https://drive.google.com/file/d/1DDduHg6neQYb_aR0b8MwTzbyLrSekCFV/view?usp=drive_link) |
[**Code (will be available soon)**](https://github.com/Rachelcoll/EULoInf.git)

TL;DR: EULoInf is an efficient Hessian-free influence function approximation based on predictive uncertainty. EULoInf avoids iHVP computation, effectively reducing the iHVP-induced quadratic complexity in model parameters to linear time. It reaches perfect balance between effectiveness and efficiency, reducing computational time and memory usage by over 50%.
  </div>
</div>
# 📖 Educations
- *2023.8 - 2027.5 (expected)*, Undergraduate Student, School of Computing, National University of Singapore

# 🏆 Honors and Awards
- Dean's List, National University of Singapore, 2024.1
- Dean's List, National University of Singapore, 2024.6


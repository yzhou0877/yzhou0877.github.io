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
👩‍💻 I am a Staff Applied Scientist at [Walmart Labs](https://tech.walmart.com/content/walmart-global-tech/en_us.html), leading GenAI research for content generation in advertising and retail. Previously, I was an Applied Scientist at [Amazon](https://www.amazon.science/). My work focuses on Retrieval-Augmented Generation (RAG), supervised fine-tuning (SFT), reinforcement learning (RL) post-training, and scalable LLM agent system design.  I am passionate about translating cutting-edge research in large-scale modeling into production-ready AI systems.

🎓 I received my Ph.D. in Computer Science from the [University of Minnesota, Twin Cities](https://twin-cities.umn.edu/), where I was advised by [Prof. Arindam Banerjee](https://arindam.cs.illinois.edu/) and worked closely with [Prof. Steven Wu](https://zstevenwu.com/). My doctoral research focused on machine learning foundations, developing training algorithms that improve neural network generalization while preserving data privacy. I received my B.Sc. in Electronic Information and Communications from Huazhong University of Science and Technology.

<span id="news"></span>
# 🔥 News
- *2026.02*: Co-organizing the **Embodied AI Workshop ([WDFM-EAI](https://lnkd.in/gdipcH4V))** at CVPR 2026.
- *2025.11*: Paper on **LLM Agents for E-Commerce Ad Generation** accepted to EMNLP 2025.
- *2024.05*: Paper on **LLM-powered Recommendation Agents (RecMind)** accepted to NAACL 2024 Findings.
- *2024.01*: Paper on **Theory of Generalization and Optimization** accepted to AISTATS 2024.
- *2023.12*: Paper on **Conversational Query Rewrite with Feedback Learning** accepted to EMNLP 2023.
- *2023.07*: Paper on **Unified Contextual Query Rewriting** accepted to ACL 2023.

<span id="publications"></span>
# 📚 Selected Publications

<div class="pub-item">
  <img src="/images/coa.png" class="pub-img">

  <div class="pub-content">
    <div class="pub-title">
      Learning from LLM Agents: In-Context Generative Models for Text Casing in E-Commerce Ads
    </div>

    <div class="pub-authors">
      <strong>Yingxue Zhou</strong>, Tan Zhu, Tao Zeng, Zigeng Wang, Wei Shen
    </div>

    <div class="pub-venue">
      EMNLP 2025 Industry
    </div>

    <div class="pub-links">
      <a href="https://aclanthology.org/2025.emnlp-industry.79.pdf">PDF</a>
      <a href="#">Slides</a>
    </div>
  </div>
</div>

<div class="pub-item">
  <img src="/images/recmind.png" class="pub-img">

  <div class="pub-content">
    <div class="pub-title">
      RecMind: Large Language Model Powered Agent for Recommendation
    </div>
    <div class="pub-authors">
      Yancheng Wang, Ziyan Jiang, Zheng Chen, Fan Yang, <strong>Yingxue Zhou</strong>, et al.
    </div>
    <div class="pub-venue">
      NAACL 2024 Findings
    </div>
    <div class="pub-links">
      <a href="https://aclanthology.org/2024.findings-naacl.271.pdf">PDF</a>
    </div>
  </div>
</div>


<div class="pub-item">
  <img src="/images/udecoder.png" class="pub-img">

  <div class="pub-content">
    <div class="pub-title">
      Unified Contextual Query Rewriting
    </div>

    <div class="pub-authors">
      <strong>Yingxue Zhou</strong>, Jie Hao, Mukund Rungta, Yang Liu, Eunah Cho, et al.
    </div>

    <div class="pub-venue">
      ACL 2023 Industry
    </div>

    <div class="pub-links">
      <a href="https://aclanthology.org/2023.acl-industry.58.pdf">PDF</a>
      <a href="#">Slides</a>
    </div>
  </div>
</div>

<div class="pub-item">
  <img src="/images/dpo.png" class="pub-img">

  <div class="pub-content">
    <div class="pub-title">
      Improving Contextual Query Rewrite for Conversational AI Agents through User-preference Feedback Learning
    </div>
    <div class="pub-authors">
      Zhongkai Sun, <strong>Yingxue Zhou</strong>, Jie Hao, Xing Fan, Yanbin Lu, et al.
    </div>
    <div class="pub-venue">
      EMNLP 2023 Industry
    </div>

    <div class="pub-links">
      <a href="https://aclanthology.org/2023.emnlp-industry.41.pdf">PDF</a>
    </div>
  </div>
</div>


<div class="pub-item">
  <img src="/images/dpsgd3.png" class="pub-img">

  <div class="pub-content">
    <div class="pub-title">
      Bypassing the Ambient Dimension: Private SGD with Gradient Subspace Identification
    </div>

    <div class="pub-authors">
      <strong>Yingxue Zhou</strong>, Steven Wu, Arindam Banerjee
    </div>

    <div class="pub-venue">
      ICLR 2021
    </div>

    <div class="pub-links">
      <a href="https://openreview.net/pdf?id=7dpmlkBuJFC">PDF</a>
      <a href="https://github.com/yzhou0877/private-sgd-with-subspace-identification">Code</a>
      <a href="#">Slides</a>
    </div>
  </div>
</div>

<div class="pub-item">
  <img src="/images/sagd.png" class="pub-img">

  <div class="pub-content">
    <div class="pub-title">
      Towards Better Generalization of Adaptive Gradient Descent
    </div>

    <div class="pub-authors">
      <strong>Yingxue Zhou</strong>, Belhal Karimi, Zhiqiang Xu, Jinxing Yu, Ping Li
    </div>

    <div class="pub-venue">
      NeurIPS 2020
    </div>

    <div class="pub-links">
      <a href="https://proceedings.neurips.cc/paper_files/paper/2020/file/08fb104b0f2f838f3ce2d2b3741a12c2-Paper.pdf">PDF</a>
    </div>
  </div>
</div>

<span id="services"></span>
# 📋 Services

<ul>
  <li><strong>Reviewer</strong>
    <ul>
      <li><strong>NLP Conferences:</strong> ACL, EMNLP, NAACL, EACL</li>
      <li><strong>Machine Learning Conferences:</strong> ICML, NeurIPS, ICLR, AISTATS</li>
    </ul>
  </li>

  <li><strong>Workshop Organizer:</strong> 
    Embodied AI Workshop - 
    <a href="https://lnkd.in/gdipcH4V" target="_blank">
      WDFM-EAI
    </a> @ CVPR 2026
  </li>
</ul>

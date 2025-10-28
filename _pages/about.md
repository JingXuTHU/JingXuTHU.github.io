---
permalink: /
title: 
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a fifth-year year Ph.D. student majoring in computer science at
the [Institute for Interdisciplinary Information Sciences](https://iiis.tsinghua.edu.cn/en/)
in Tsinghua University.
I am very fortunate to be advised by Professor [Andrew Chi-Chih Yao](https://iiis.tsinghua.edu.cn/en/yao/), who is the
A.M. Turing laureate of 2000. I received my B.S. degree in artificial intelligence from Peking University in 2021, advised by
Professor [Liwei Wang](http://www.liweiwang-pku.com).

My research lies at the intersection of theoretical and applied machine learning. On the theoretical side, I am interested in establishing provable guarantees for the generalization and optimization of machine learning algorithms. On the empirical side, I have hands-on experience with large-scale LLM pre-training and am committed to designing efficient optimization algorithms that improve the scalability and performance pre-training.
I have worked on topics including:
- Parameter Efficient Fine-tuning of LLMs.
- Scalable model merging.
- Generalization guarantees of machine learning algorithms.
- Implicit bias and their empirical signals.
- Optimization algorithms for structured problems.

<h2 class="section-title">Internship Experiences</h2>

**Citadel Securities** (Jun. 2025 – Sept. 2025)  
*Quantitative Research Intern*  
- Built LLM pipelines to extract signals and build alphas from text-based alternative dataset.

**Moonshot AI** (Feb. 2025 – Jun. 2025)  
*Machine Learning Intern at Pre-training Team*  
- Developed efficient and stable optimization algorithms (e.g., Muon and its variants) for LLM pre-training. 

**Jump Trading** (Jun. 2024 – Aug. 2024)  
*Quantitative Research Intern*  
- Conducted alpha analysis for China's stock market.  


<h2 class="section-title">Publications</h2>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

[//]: # (======)

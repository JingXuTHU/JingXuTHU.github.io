---
permalink: /
title: 
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a research scientist on the pre-training team at **Qwen** (Alibaba), focusing on improved model architectures and training algorithms for large language models.

I received my Ph.D. in computer science from the [Institute for Interdisciplinary Information Sciences](https://iiis.tsinghua.edu.cn/en/) at Tsinghua University in 2026, advised by Professor [Andrew Chi-Chih Yao](https://iiis.tsinghua.edu.cn/en/yao/), who is recipient of the 2000 A.M. Turing Award.
I received my B.S. degree in artificial intelligence from Peking University in 2021, advised by Professor [Liwei Wang](http://www.liweiwang-pku.com).

My research lies at the intersection of theoretical and applied machine learning. On the theoretical side, I am interested in establishing provable guarantees for the generalization and optimization of machine learning algorithms. On the empirical side, I have hands-on experience with large-scale LLM pre-training and am committed to designing efficient optimization algorithms that improve scalability and performance in pre-training.

I also have in-depth practical experience in quantitative research, including internships at Citadel Securities and Jump Trading.

My previous work includes:
- Efficient and stable optimizers for LLM pre-training.
- Adaptation of LLMs, e.g., parameter-efficient fine-tuning and scalable model merging.
- Generalization guarantees, implicit bias, and corresponding empirical signals in machine learning.
- Upper and lower convergence bounds for optimization algorithms on structured problems.

<h2 class="section-title">Experience</h2>

 - **Qwen (Alibaba)** (Apr. 2026 – present)<br>
   <em>Researcher, Pre-training Team</em><br>
   Conducting research on LLM pre-training, exploring novel approaches in model architectures, training strategies, and scaling techniques. Selected for the Alibaba Alistar Talent Program.

 - **Citadel Securities** (Jun. 2025 – Sept. 2025)<br>
   <em>Quantitative Research Intern</em><br>
   Built LLM pipelines to extract signals and build alphas from text-based alternative datasets. Received return offer.

 - **Moonshot AI** (Feb. 2025 – Jun. 2025)<br>
   <em>Machine Learning Intern, Pre-training Team</em><br>
   Participated in developing efficient and stable optimization algorithms (e.g., MuonClip and other variants of Muon) for LLM pre-training. Contributed to Kimi K2 model.

 - **Jump Trading** (Jun. 2024 – Aug. 2024)<br>
   <em>Quantitative Research Intern</em><br>
   Conducted alpha analysis for China's stock market.


<h2 class="section-title">Publications</h2>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

[//]: # (======)

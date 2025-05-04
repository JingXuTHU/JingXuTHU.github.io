---
permalink: /
title: 
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a fourth-year year Ph.D. student majoring in computer science at
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


<h2 class="section-title">Publications</h2>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


<h2 class="section-title">Preprints</h2>

{% for post in site.preprints %}
  {% include archive-single.html %}
{% endfor %}

[//]: # (======)

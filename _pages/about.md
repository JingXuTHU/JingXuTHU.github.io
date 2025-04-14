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

My research focuses on machine learning, both on theoretical side and application side. I enjoy establishing theoretical guarantees of generalization and optimization of deep learning algorithms. My current research focuses on designing practical and theoretically-sound optimization algorithms to pretrain and finetune large language models. I have previously worked on topics including generalization, adversarial robustness, federated learning and differential privacy.

<h2 class="section-title">Publications</h2>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


<h2 class="section-title">Preprints</h2>

{% for post in site.preprints %}
  {% include archive-single.html %}
{% endfor %}

[//]: # (======)

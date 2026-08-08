---
permalink: /
title: "Junteng Liu"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Hi, I am Junteng Liu, a first-year Ph.D. candidate at the HKUST NLP Group, Hong Kong University of Science and Technology, advised by Professor Junxian He. I graduated from Shanghai Jiao Tong University (SJTU) in June 2024. My research focuses on natural language processing and machine learning, with interests in LLM reasoning and reinforcement learning, hallucination in vision-language models (VLMs), and LLM truthfulness and interpretability.

Academic Background
======
* Ph.D. in Computer Science, Hong Kong University of Science and Technology, 2024–Present
* B.Eng., Shanghai Jiao Tong University, 2020–2024

Research Experience
======
* Research Intern, MINIMAX, February 2025 – Present
* Research Intern, Tencent WXG, June 2024 – September 2024
* Research Intern, Shanghai AI Lab, June 2023 – December 2023

Skills
======
* Natural Language Processing
* Machine Learning
* LLM Reasoning and Reinforcement Learning
* Hallucination in Vision-Language Models
* LLM Truthfulness and Interpretability

Honors
======
* Zhiyuan Honor Scholarship, Shanghai Jiao Tong University

Publications
======
{% if site.author.googlescholar %}
You can also find my articles on <a href="{{ site.author.googlescholar }}">my Google Scholar profile</a>.
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Contact
======
* Email: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
* GitHub: [Vicent0205](https://github.com/Vicent0205)
* Google Scholar: [Profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
* X (Twitter): [@junteng88716710](https://twitter.com/junteng88716710)

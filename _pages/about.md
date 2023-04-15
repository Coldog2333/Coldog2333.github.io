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
This is Junfeng JIANG (江俊锋，こう　しゅんほう). Currently, I am a D2 student in the University of Tokyo, supported by [SPRING GX Program](https://spring-gx.adm.s.u-tokyo.ac.jp/en/). 

My research direction is Document-grounded Dialogue System (DGDS). Unfortunately, it was almost perfectly done by CloseAI's ChatGPT/GPT-4. As a human, it is a piece of good news but as for a PhD candidate, it sucks. Anyway, any interesting discussion is welcome and my full publications can be accessed from google scholar. <a href='https://scholar.google.com/citations?user=gvKNfGEAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).


# 🔥 News
- *2023.04*: &nbsp;🎉🎉 D1->D2.

# 📖 Educations
- *2022.04 - Now*, Ph.D. candidate in Computer Science, The University of Tokyo. 
- *2019.09 - 2022.04*, M.S. in Computer Science (2.88/3.0), The University of Tokyo.
- *2015.08 - 2019.07*, B.S. in Mathematics And Applied Mathematics (3.7/5.0), Sun Yat-Sen University.

# 📝 Publications 
## Conference Papers
- Che Liu, Rui Wang, **Junfeng Jiang**, Yongbin Li, Fei Huang. *Dial2vec: Self-Guided Contrastive Learning of Unsupervised Dialogue Embeddings.* In Proceedings of the 2022 Conference on Empirical Methods in Natural Language Processing, Online and Abu Dhabi. Association for Computational Linguistics. **(EMNLP 2022)**. [[paper]](https://aclanthology.org/2022.emnlp-main.490.pdf); [[code]](https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/dial2vec).
- **Junfeng Jiang**, An Wang*, and Akiko Aizawa. *Attention-based Relational Graph Convolutional Network for Target-Oriented Opinion Words Extraction*. The 16th Conference of the European Chapter of the Association for Computational Linguistics, pp.1986–1997. Online, April 19–23, 2021. **(EACL 2021)**. [[paper]](https://aclanthology.org/2021.eacl-main.170.pdf); [[code]](https://github.com/wcwowwwww/towe-eacl).
- Che Liu, **Junfeng Jiang**, Chao Xiong, Yi Yang, Jieping Ye. *Towards Building an Intelligent Chatbot for Customer Service: Learning to Respond at the Appropriate Time*. In Proceedings of the 26th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining (pp. 3377-3385). **(KDD 2020)**. [[paper]](https://dl.acm.org/doi/10.1145/3394486.3403390).

## Preprints
- Chao Xiong, Che Liu, Zijun Xu, **Junfeng Jiang**, Jieping Ye. *Sequential Sentence Matching Network for Multi-turn Response Selection in Retrieval-based Chatbots*. arXiv preprint arXiv:2005.07923. [[paper]](https://arxiv.org/pdf/2005.07923.pdf).
- **Junfeng Jiang**, Jiahao Li. *Constructing financial sentimental factors in Chinese market using natural language processing*. arXiv preprint arXiv:1809.08390. [[paper]](https://arxiv.org/pdf/1809.08390.pdf); [[code]](https://github.com/Coldog2333/Financial-NLP).

<!--
# 🎖 Honors and Awards
- N/A
-->
# 💰 Fundings
- *2022.04 - 2025.04*, SPRING GX, JST. (~1M JPY)

<!--
# 💬 Invited Talks
- N/A
-->

# 💻 Internships
- *2022.05 - 2022.09*, Alibaba DAMO Academy, Beijing, China.
- *2020.12 - 2021.05*, Baidu Inc., Shenzhen, China.
- *2020.08 - 2020.12*, Tencent Inc., Shenzhen, China.
- *2019.10 - 2020.08*, Didi Chuxing AI Labs, Beijing, China.
- *2018.07 - 2019.01*, Likelihood Lab, Guangzhou, China.

# 👓 Committees
- Reviewer for conferences: ACL 2023; EACL 2023; EMNLP 2022,2021.
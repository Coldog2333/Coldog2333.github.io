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
This is Junfeng JIANG (江俊锋，こう　しゅんほう). Currently, I am a D2 student in the University of Tokyo under the supervision of [Prof. Akiko Aizawa](https://www-al.nii.ac.jp/ja/), supported by [SPRING GX Program](https://spring-gx.adm.s.u-tokyo.ac.jp/en/). 

My research direction is Document-grounded Dialogue System (DGDS). Unfortunately, it was almost perfectly done by CloseAI's ChatGPT/GPT-4. As a human, it is a piece of good news but as for a PhD candidate, it sucks. Anyway, any interesting discussion is welcome and my full publications can be accessed from google scholar. <a href='https://scholar.google.com/citations?user=gvKNfGEAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).

Currently, I am working on research related to
- Large Language Model (no so large but large enough that cannot be fitted in a single A100 80GB GPU)
- Chain-of-thought Finetuning
- Evaluation for DGDS
- Dialogue Segmentation

Any collaboration or discussion is welcome!

# 🔥 News
- *2023.05*: 🎉 A paper was accepted by \*SEM 2023.
- *2023.05*: [SuperDialseg](https://github.com/Coldog2333/SuperDialseg) is publicly available. You can segment your dialogues in two lines.
- *2023.05*:  <img src="https://pic1.zhimg.com/80/v2-1ee42194de58b62f929d5abccfbde184_1440w.webp" width = "20" height = "20" alt="图片名称" align=center /> A paper was rejected by ACL 2023.
- *2023.04*: 🎉 D1->D2.

# 📖 Educations
- *2022.04 - Now*, Ph.D. candidate in Computer Science, The University of Tokyo. 
- *2019.09 - 2022.04*, M.S. in Computer Science (2.88/3.0), The University of Tokyo.
- *2015.08 - 2019.07*, B.S. in Mathematics And Applied Mathematics (3.7/5.0), Sun Yat-Sen University.

# 📝 Publications 
## Conference Papers
- An Wang, **Junfeng Jiang**, Youmi Ma, Ao Liu and Naoaki Okazaki. *Generative Data Augmentation for Aspect Sentiment Quad Prediction*. In The 12th Joint Conference on Lexical and Computational Semantics. **(\*SEM 2023)**. (to appear)
- Che Liu, Rui Wang, **Junfeng Jiang**, Yongbin Li, Fei Huang. *Dial2vec: Self-Guided Contrastive Learning of Unsupervised Dialogue Embeddings.* In Proceedings of the 2022 Conference on Empirical Methods in Natural Language Processing, Online and Abu Dhabi. Association for Computational Linguistics. **(EMNLP 2022)**. [[paper]](https://aclanthology.org/2022.emnlp-main.490.pdf); [[code]](https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/dial2vec). [![](https://img.shields.io/github/stars/AlibabaResearch/DAMO-ConvAI?style=social&label=Stars)](https://github.com/AlibabaResearch/DAMO-ConvAI)
- **Junfeng Jiang**\*, An Wang\*, and Akiko Aizawa. *Attention-based Relational Graph Convolutional Network for Target-Oriented Opinion Words Extraction*. The 16th Conference of the European Chapter of the Association for Computational Linguistics, pp.1986–1997. Online, April 19–23, 2021. **(EACL 2021)**. [[paper]](https://aclanthology.org/2021.eacl-main.170.pdf); [[code]](https://github.com/wcwowwwww/towe-eacl). [![](https://img.shields.io/github/stars/wcwowwwww/towe-eacl?style=social&label=Stars)](https://github.com/wcwowwwww/towe-eacl)
- Che Liu, **Junfeng Jiang**, Chao Xiong, Yi Yang, Jieping Ye. *Towards Building an Intelligent Chatbot for Customer Service: Learning to Respond at the Appropriate Time*. In Proceedings of the 26th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining (pp. 3377-3385). **(KDD 2020)**. [[paper]](https://dl.acm.org/doi/10.1145/3394486.3403390).

## Preprints
- **Junfeng Jiang**, Chengzhang Dong, Akiko Aizawa, Sadao Kurohashi. *SuperDialseg: A Large-scale Dataset for Supervised Dialogue Segmentation*. arXiv preprint arXiv:2305.08371. [[paper]](https://arxiv.org/pdf/2305.08371.pdf). 
- Chao Xiong, Che Liu, Zijun Xu, **Junfeng Jiang**, Jieping Ye. *Sequential Sentence Matching Network for Multi-turn Response Selection in Retrieval-based Chatbots*. arXiv preprint arXiv:2005.07923. [[paper]](https://arxiv.org/pdf/2005.07923.pdf).
- **Junfeng Jiang**, Jiahao Li. *Constructing financial sentimental factors in Chinese market using natural language processing*. arXiv preprint arXiv:1809.08390. [[paper]](https://arxiv.org/pdf/1809.08390.pdf); [[code]](https://github.com/Coldog2333/Financial-NLP). [![](https://img.shields.io/github/stars/Coldog2333/Financial-NLP?style=social&label=Stars)](https://github.com/Coldog2333/Financial-NLP)

# 💻 Projects
- SuperDialseg [![](https://img.shields.io/github/stars/Coldog2333/SuperDialseg?style=social&label=Stars)](https://github.com/Coldog2333/SuperDialseg) is an easy to use python library for dialogue segmentation.
- pytoflow [![](https://img.shields.io/github/stars/Coldog2333/pytoflow?style=social&label=Stars)](https://github.com/Coldog2333/pytoflow) is an unofficial PyTorch version implementation of [TOFlow: Video Enhancement with Task-Oriented Flow](http://toflow.csail.mit.edu/toflow_ijcv.pdf). [[demo]](https://www.bilibili.com/video/av39553558/).

<!--
# 🎖 Honors and Awards
- N/A
-->
# 💰 Fundings
- *2022.12 - 2023.03*, Self-directed and integrated project research, SPRING GX, JST. (~500K JPY)
- *2022.04 - 2025.04*, SPRING GX, JST. (~1M JPY)

<!--
# 💬 Invited Talks
- N/A
-->

# 👨‍💻 Internships
- *2022.12 - Now*, Research Assistant, National Institute of Informatics, Tokyo, Japan.
- *2022.05 - 2022.09*, NLP Research Intern, Alibaba DAMO Academy, Beijing, China.
- *2020.12 - 2021.05*, NLP Research Intern, Baidu Inc., Shenzhen, China.
- *2020.08 - 2020.12*, NLP R&D Intern, Tencent Inc., Shenzhen, China.
- *2019.10 - 2020.08*, NLP Research Intern, Didi Chuxing AI Labs, Beijing, China.
- *2018.07 - 2019.01*, AI Research Intern, Likelihood Lab, Guangzhou, China.

# 👓 Committees
- Invited Reviewer for conferences: ACL 2023; EACL 2023; EMNLP 2022,2021.
- Secondary Reviewer for conferences: AACL 2023.


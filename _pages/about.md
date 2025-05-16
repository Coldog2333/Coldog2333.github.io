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
This is Junfeng JIANG (江俊锋，こう　しゅんほう). Currently, I am a project researcher at [the Research and Development Center for Large Language Models (LLMC)](https://llmc.nii.ac.jp/en/) of the National Institute of Informatics (NII). Previously, I was a PhD student at the University of Tokyo under the supervision of [Prof. Akiko Aizawa](https://www-al.nii.ac.jp/ja/), supported by [SPRING GX Program](https://spring-gx.adm.s.u-tokyo.ac.jp/en/). 

My research direction is focusing on developing biomedical large language models. My previous research direction is Document-grounded Dialogue System (DGDS). Any interesting discussion is welcome and my full publications can be accessed from Google Scholar.<a href='https://scholar.google.com/citations?user=gvKNfGEAAAAJ'></a>).

Currently, I am working on research related to
- Large Language Model (not so large but large enough that cannot be fitted in a single A100 80GB GPU)
- Biomedical Language Model
- Chain-of-thought Finetuning

Any collaboration or discussion is welcome! And I am also recruiting Research Assistant (RA) at NII LLMC. Please feel free to contact me with your CV/Resume via jiang (at) nii.ac.jp, if you are interested in this position. :)

# 🔥 News
- *2025.05*: 🎉 A paper was accepted as the ACL 2025 findings.
- *2025.04*: 🎉 Our paper achieved the Best Presentation Award (最優秀賞) at 13th AAMT Seminar.
- *2025.04*: 🎉 A journal paper was published in IEEE Access.
- *2024.11*: 🎉 A paper was accepted by COLING 2025.
  
# 📖 Educations
- *2022.04 - Now*, Ph.D. candidate in Computer Science, The University of Tokyo. 
- *2019.09 - 2022.04*, M.S. in Computer Science (2.88/3.0), The University of Tokyo.
- *2015.08 - 2019.07*, B.S. in Mathematics And Applied Mathematics (3.7/5.0), Sun Yat-Sen University.

# 🐂 Work Experience
- *2025.04 - Now*, Project Researcher, National Institute of Informatics, Tokyo, Japan.

# 👨‍💻 Internships
- *2022.12 - 2025.04*, Research Assistant, National Institute of Informatics, Tokyo, Japan.
- *2022.05 - 2022.09*, NLP Research Intern, Alibaba DAMO Academy, Beijing, China.
- *2020.12 - 2021.05*, NLP Research Intern, Baidu Inc., Shenzhen, China.
- *2020.08 - 2020.12*, NLP R&D Intern, Tencent Inc., Shenzhen, China.
- *2019.10 - 2020.08*, NLP Research Intern, Didi Chuxing AI Labs, Beijing, China.
- *2018.07 - 2019.01*, AI Research Intern, Likelihood Lab, Guangzhou, China.

# 📝 Publications 
## Journals
- An Wang, Huidong Jiang, Youmi Ma, **Junfeng Jiang**, Ao Liu, & Okazaki, Naoaki. (2025). *Improving Implicit Sentiments Analysis via Explanations of Multiple Perspectives*, in IEEE Access, doi: 10.1109/ACCESS.2025.3556762.
- Detai Xin\*, **Junfeng Jiang**\*, Shinnosuke Takamichi, Yuki Saito, Akiko Aizawa, & Hiroshi Saruwatari. (2024). *JVNV: A Corpus of Japanese Emotional Speech with Verbal Content and Nonverbal Expressions*, in IEEE Access, vol. 12, pp. 19752-19764, 2024, doi: 10.1109/ACCESS.2024.3360885.

## Conference Papers
- Chengzhi Zhong, Qianying Liu, Fei Cheng, **Junfeng Jiang**, Zhen Wan, Chenhui Chu, Yugo Murawaki, Sadao Kurohashi. 2025. *What Language Do Non-English-Centric Large Language Models Think in?*. In Findings of the Association for Computational Linguistics: ACL 2025, to appear, Vienna, Austria. Association for Computational Linguistics. **(ACL 2025, findings)**.
- **Junfeng Jiang**, Jiahao Huang, Akiko Aizawa. *JMedBench: A Benchmark for Evaluating Japanese Biomedical Large Language Models.* The 31st International Conference on Computational Linguistics. January, to appear. 2025. **(COLING 2025)** [[paper]](https://arxiv.org/pdf/2409.13317); [[data]](https://huggingface.co/datasets/Coldog2333/JMedBench); [[code]](https://github.com/nii-nlp/med-eval) ![](https://img.shields.io/github/stars/nii-nlp/med-eval?style=social&label=Stars).
- **Junfeng Jiang**, Fei Cheng, and Akiko Aizawa. 2024. *Improving Referring Ability for Biomedical Language Models*. In Findings of the Association for Computational Linguistics: EMNLP 2024, pages 6444–6457, Miami, Florida, USA. Association for Computational Linguistics. **(EMNLP 2024, findings)**. [[paper]](https://aclanthology.org/2024.findings-emnlp.375.pdf); [[code]](https://github.com/Coldog2333/SuperDialseg) ![](https://img.shields.io/github/stars/Coldog2333/SuperDialseg?style=social&label=Stars).
- Davide Baldelli, **Junfeng Jiang**, Akiko Aizawa and Paolo Torroni. *TWOLAR: a TWO-step LLM-Augmented distillation method for passage Reranking*. In European Conference on Information Retrieval, vol 14608, pages 470-485, 2024, Springer. doi: 10.1007/978-3-031-56027-9_29. **(ECIR 2024)**. [[paper]](https://link.springer.com/chapter/10.1007/978-3-031-56027-9_29); [[code]](https://github.com/Dundalia/TWOLAR). ![](https://img.shields.io/github/stars/Dundalia/TWOLAR?style=social&label=Stars)
- **Junfeng Jiang**, Chengzhang Dong, Sadao Kurohashi, Akiko Aizawa. *SuperDialseg: A Large-scale Dataset for Supervised Dialogue Segmentation*. In Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing, pages 4086–4101, Singapore. Association for Computational Linguistics. **(EMNLP 2023)**. [[paper]](https://aclanthology.org/2023.emnlp-main.249.pdf); [[code]](https://github.com/Coldog2333/SuperDialseg). ![](https://img.shields.io/github/stars/Coldog2333/SuperDialseg?style=social&label=Stars)
- An Wang, **Junfeng Jiang**, Youmi Ma, Ao Liu, and Naoaki Okazaki. 2023. *Generative Data Augmentation for Aspect Sentiment Quad Prediction*. In Proceedings of the 12th Joint Conference on Lexical and Computational Semantics (*SEM 2023), pages 128–140, Toronto, Canada. Association for Computational Linguistics. **(\*SEM 2023)**. [[paper]](https://aclanthology.org/2023.starsem-1.12.pdf); [[code]](https://github.com/AnWang-AI/AugABSA). [![](https://img.shields.io/github/stars/AnWang-AI/AugABSA?style=social&label=Stars)](https://github.com/AnWang-AI/AugABSA)
- Che Liu, Rui Wang, **Junfeng Jiang**, Yongbin Li, Fei Huang. *Dial2vec: Self-Guided Contrastive Learning of Unsupervised Dialogue Embeddings.* In Proceedings of the 2022 Conference on Empirical Methods in Natural Language Processing, pages 7272–7282, Abu Dhabi, United Arab Emirates. Association for Computational Linguistics. **(EMNLP 2022)**. [[paper]](https://aclanthology.org/2022.emnlp-main.490.pdf); [[code]](https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/dial2vec). [![](https://img.shields.io/github/stars/AlibabaResearch/DAMO-ConvAI?style=social&label=Stars)](https://github.com/AlibabaResearch/DAMO-ConvAI)
- **Junfeng Jiang**\*, An Wang\*, and Akiko Aizawa. *Attention-based Relational Graph Convolutional Network for Target-Oriented Opinion Words Extraction*. The 16th Conference of the European Chapter of the Association for Computational Linguistics, pp.1986–1997. Online, April 19–23, 2021. **(EACL 2021)**. [[paper]](https://aclanthology.org/2021.eacl-main.170.pdf); [[code]](https://github.com/wcwowwwww/towe-eacl). [![](https://img.shields.io/github/stars/wcwowwwww/towe-eacl?style=social&label=Stars)](https://github.com/wcwowwwww/towe-eacl)
- Che Liu, **Junfeng Jiang**, Chao Xiong, Yi Yang, Jieping Ye. *Towards Building an Intelligent Chatbot for Customer Service: Learning to Respond at the Appropriate Time*. In Proceedings of the 26th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining (pp. 3377-3385). **(KDD 2020)**. [[paper]](https://dl.acm.org/doi/10.1145/3394486.3403390).

## Preprints
<!-- - Detai Xin\*, **Junfeng Jiang**\*, Shinnosuke Takamichi, Yuki Saito, Akiko Aizawa, & Hiroshi Saruwatari (2023). *JVNV: A Corpus of Japanese Emotional Speech with Verbal Content and Nonverbal Expressions*. arXiv preprint arXiv:2310.06072. [[paper]](https://arxiv.org/pdf/2310.06072.pdf).-->
<!-- - **Junfeng Jiang**, Jiahao Huang, Akiko Aizawa. *JMedBench: A Benchmark for Evaluating Japanese Biomedical Large Language Models*. arXiv preprint arXiv:2409.13317. [[paper]](https://arxiv.org/pdf/2409.13317); [[data]](https://huggingface.co/datasets/Coldog2333/JMedBench).-->
<!-- - Chengzhi Zhong, Fei Cheng, Qianying Liu, **Junfeng Jiang**, Zhen Wan, Chenhui Chu, Yugo Murawaki, & Sadao Kurohashi. *Beyond English-Centric LLMs: What Language Do Multilingual Language Models Think in?*. arXiv preprint arXiv:2408.10811. [[paper]](https://arxiv.org/pdf/2408.10811).-->
- Xanh Ho\*, Anh Khoa Duong Nguyen\*, An Tuan Dao\*, **Junfeng Jiang**\*, Yuki Chida\*, Kaito Sugimoto\*, Huy Quoc To, Florian Boudin, Akiko Aizawa. *A Survey of Pre-trained Language Models for Processing Scientific Text*. arXiv preprint arXiv:2401.17824. [[paper]](https://arxiv.org/pdf/2401.17824).
- Chao Xiong, Che Liu, Zijun Xu, **Junfeng Jiang**, Jieping Ye. *Sequential Sentence Matching Network for Multi-turn Response Selection in Retrieval-based Chatbots*. arXiv preprint arXiv:2005.07923. [[paper]](https://arxiv.org/pdf/2005.07923).
- **Junfeng Jiang**, Jiahao Li. *Constructing financial sentimental factors in Chinese market using natural language processing*. arXiv preprint arXiv:1809.08390. [[paper]](https://arxiv.org/pdf/1809.08390); [[code]](https://github.com/Coldog2333/Financial-NLP). [![](https://img.shields.io/github/stars/Coldog2333/Financial-NLP?style=social&label=Stars)](https://github.com/Coldog2333/Financial-NLP)
  

# 💻 Projects
- med-eval ![](https://img.shields.io/github/stars/nii-nlp/med-eval?style=social&label=Stars) is an evaluation library for medical tasks.
- BioMed-LLaMA [![](https://img.shields.io/github/stars/Coldog2333/BioMed-LLaMA?style=social&label=Stars)](https://github.com/Coldog2333/BioMed-LLaMA) is a project of continuous pre-training for biomedical LLM.
- pytoflow [![](https://img.shields.io/github/stars/Coldog2333/pytoflow?style=social&label=Stars)](https://github.com/Coldog2333/pytoflow) is an unofficial PyTorch version implementation of [TOFlow: Video Enhancement with Task-Oriented Flow](http://toflow.csail.mit.edu/toflow_ijcv.pdf). [[demo]](https://www.bilibili.com/video/av39553558/).

# 🎖 Honors and Awards
- Best Presentation Award (最優秀賞) at [the 13th AAMT for Young Translation Research Group](https://aamt.info/event/seminar/20250321): What language do Japanese-specialized large language models think in?


# 💰 Fundings
- *2022.12 - 2023.03*, Self-directed and integrated project research, SPRING GX, JST. (~500K JPY)
- *2022.04 - 2025.04*, SPRING GX, JST. (~1M JPY)

<!--
# 💬 Invited Talks
- N/A
-->

# 👓 Committees
- Invited Reviewer for conferences: COLING 2025; CIKM 2024; LREC-COLING 2024; ACL 2023, 2025; EACL 2023; EMNLP 2023,2022,2021.
- Secondary Reviewer for conferences: ICML 2025; IJCNLP-AACL 2023.

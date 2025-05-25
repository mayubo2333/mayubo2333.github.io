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

I am a researcher in the Qwen Team and a fourth-year Ph.D. candidate in College of Computing and Data Science at Nanyang Technological University (NTU). I am co-advised by Prof. [Aixin Sun](https://personal.ntu.edu.sg/axsun/) and Prof. [Yixin Cao](https://sites.google.com/view/yixin-homepage). Before that, I received my B.Eng. degree in Electronic Engineering from Tsinghua University in 2020. 

* My current work focuses on evaluations on Qwen models.
* I am also interested on multi-modality document understanding and retrieval.
* Previously, I was dedicated to (1) tool-augmented LLMs and (2) effective and efficient information extraction algorithms.

# 🔥 News
- *2025.05*: Four papers accepted to ACL 2025 (two main, two findings)!
- *2025.02*: One papers accepted to NAACL 2025 (findings)!
- *2024.09*: One papers accepted to NeurIPS 2024 as spotlight!
- *2024.09*: Two papers accepted to EMNLP 2024 (one main, one findings)!
- *2024.05*: Two papers accepted to ACL 2024 (one main, one findings)!
- *2023.10*: One paper accepted to EMNLP 2023 (Findings)!
- *2023.06*: Join Microsoft Research as a research intern!
- *2023.05*: Pass my Ph.D. Qualification Examination and become a Ph.D. candidate now!
- *2023.05*: One paper accepted to ACL 2023 (main conference)!  
- *2022.02*: Two papers accepted to ACL 2022 (one main, one demonstration system)!


# 📒 Preprint
- [Toward Generalizable Evaluation in the LLM Era: A Survey Beyond Benchmarks](https://arxiv.org/abs/2504.18838), Yixin Cao, Shibo Hong, Xinze Li, Jiahao Ying, **Yubo Ma**, Haiyuan Liang, Yantao Liu, Zijun Yao, Xiaozhi Wang, Dan Huang, Wenxuan Zhang, Lifu Huang, Muhao Chen, Lei Hou, Qianru Sun, Xingjun Ma, Zuxuan Wu, Min-Yen Kan, David Lo, Qi Zhang, Heng Ji, Jing Jiang, Juanzi Li, Aixin Sun, Xuanjing Huang, Tat-Seng Chua, Yu-Gang Jiang. 2025.
- [Long Context vs. RAG for LLMs: An Evaluation and Revisits] (https://arxiv.org/abs/2501.01880), Xinze Li, Yixin Cao, **Yubo Ma**, Aixin Sun. 2024.


# 📝 Publications
^ indicates equal contribution.
- [Towards Storage-Efficient Visual Document Retrieval: An Empirical Study on Reducing Patch-Level Embeddings](), **Yubo Ma**, Jinsong Li, Yuhang Zang, Xiaobao Wu, Xiaoyi Dong, Pan Zhang, Yuhang Cao, Haodong Duan, Jiaqi Wang, Yixin Cao, Aixin Sun. **ACL 2025 (Findings)**
- [MMLongBench-Doc: Benchmarking Long-context Document Understanding with Visualizations](https://arxiv.org/abs/2407.01523), **Yubo Ma**, Yuhang Zang, Liangyu Chen, Meiqi Chen, Yizhu Jiao, Xinze Li, Xinyuan Lu, Ziyu Liu, Yan Ma, Xiaoyi Dong, Pan Zhang, Liangming Pan, Yu-Gang Jiang, Jiaqi Wang, Yixin Cao, Aixin Sun. **NeurIPS 2024 spotlight (dataset track)**
- [SciAgent: Tool-augmented Language Models for Scientific Reasoning](https://arxiv.org/abs/2402.11451), **Yubo Ma**, Zhibin Gou, Junheng Hao, Ruochen Xu, Shuohang Wang, Liangming Pan, Yujiu Yang, Yixin Cao, Aixin Sun, Hany Awadalla, Weizhu Chen. **EMNLP 2024**
- [Large Language Model Is Not a Good Few-shot Information Extractor, but a Good Reranker for Hard Samples!](https://arxiv.org/abs/2303.08559), **Yubo Ma**, Yixin Cao, Yong Ching Hong, Aixin Sun. **EMNLP 2023 (Findings)**
- [Few-shot Event Detection: An Empirical Study and a Unified View](https://aclanthology.org/2023.acl-long.628/), **Yubo Ma**, Zehao Wang, Yixin Cao, Aixin Sun. **ACL 2023**
- [Prompt for Extraction? PAIE: Prompting Argument Interaction for Event Argument Extraction](https://aclanthology.org/2022.acl-long.466/), **Yubo Ma**^, Zehao Wang^, Yixin Cao, Mukai Li, Meiqi Chen, Kun Wang, Jing Shao. **ACL 2022**
- [MMEKG: Multi-modal Event Knowledge Graph towards Universal Representation across Modalities](https://aclanthology.org/2022.acl-demo.23/), **Yubo Ma**^, Zehao Wang^, Mukai Li^, Yixin Cao^, Meiqi Chen^, Xinze Li, Wenqi Sun, Kunquan Deng, Kun Wang, Aixin Sun, Jing Shao. **ACL 2022 (Demo Track)**
- [Synergistic Weak-Strong Collaboration by Aligning Preferences](https://arxiv.org/abs/2504.15188), Yizhu Jiao, Xuchao Zhang, Zhaoyang Wang, Yubo Ma, Zhun Deng, Rujia Wang, Chetan Bansal, Saravan Rajmohan, Jiawei Han, Huaxiu Yao. **ACL 2025**
- [Antileak-bench: Preventing data contamination by automatically constructing benchmarks with updated real-world knowledge](https://arxiv.org/abs/2412.13670), Xiaobao Wu, Liangming Pan, Yuxi Xie, Ruiwen Zhou, Shuai Zhao, **Yubo Ma**, Mingzhe Du, Rui Mao, Anh Tuan Luu, William Yang Wang. **ACL 2025**
- [InternLM-XComposer2. 5-Reward: A Simple Yet Effective Multi-Modal Reward Model](https://arxiv.org/abs/2501.12368), Yuhang Zang, Xiaoyi Dong, Pan Zhang, Yuhang Cao, Ziyu Liu, Shengyuan Ding, Shenxi Wu, **Yubo Ma**, Haodong Duan, Wenwei Zhang, Kai Chen, Dahua Lin, Jiaqi Wang. **ACL 2025 (Findings)**
- [TART: An Open-Source Tool-Augmented Framework for Explainable Table-based Reasoning](https://arxiv.org/abs/2409.11724), Xinyuan Lu, Liangming Pan, **Yubo Ma**, Preslav Nakov, Min-Yen Kan. **NAACL 2025 (Findings)**
- [Navigating the Nuances: A Fine-grained Evaluation of Vision-Language Navigation](https://aclanthology.org/2024.findings-emnlp.269), Zehao Wang, Minye Wu, Yixin Cao, **Yubo Ma**, Meiqi Chen, Tinne Tuytelaars. **EMNLP 2024 (Findings)**
- [Learning To Teach Large Language Models Logical Reasoning](https://arxiv.org/abs/2310.09158), Meiqi Chen, **Yubo Ma**, Kaitao Song, Yixin Cao, Yan Zhang, Dongsheng Li.  **ACL 2024**
- [Towards Verifiable Generation: A Benchmark for Knowledge-aware Language Model Attribution](https://arxiv.org/abs/2310.05634), Xinze Li, Yixin Cao, Liangming Pan, **Yubo Ma**, Aixin Sun. **ACL 2024 (Findings)**
- [Information Extraction in Low-Resource Scenarios: Survey and Perspective](https://arxiv.org/abs/2202.08063), Shumin Deng, **Yubo Ma**, Ningyu Zhang, Yixin Cao, Bryan Hooi. **ICKG 2024**


# 📖 Educations
- *2021.08 - Present*, PhD. student/candidate, School of Computer Science and Engineering, Nanyang Technological University. 
- *2017.06 - 2020.06*, B.Eng., Department of Electronic Engineering, Tsinghua University.
- *2015.08 - 2017.06*, Undergraduate, School of Life Sciences, Tsinghua University.


# 💻 Internships
- *2024.04 - 2025.02*, Research Intern, Shanghai AI Labratory, China (remote).
- *2023.06 - 2024.03*, Research Intern, Microsoft Research (MSR) & Azure AI, USA (remote).
- *2021.01 - 2021.07*, Research Intern, Sensetime Research, China.


# 📚 Academic Services
- *Area Chair*: ACL ARR (ACL 2025)
- *Conference Reviewer*: NeurIPS 2025, NeurIPS 2024, ACL ARR (EMNLP 2024, ACL 2024, NAACL 2024), ACL 2023, EMNLP 2023, CCL 2023
- *Journal Reviewer*: TOIS
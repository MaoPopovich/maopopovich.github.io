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
# About Me
I am currently a second-year PhD candidate at Shanghai Jiao Tong Univeristy, supervised by [Dr. Xi Lin](https://www.cs.sjtu.edu.cn/jiaoshiml/linxi.html).
I received my bachelor's degree of information security from School of Electronic Information and Electrical Engineering at Shanghai Jiao Tong University in 2022, supervised by [Dr. Kui Meng](https://infosec.sjtu.edu.cn/DirectoryDetail.aspx?id=144). 
My research interest includes trustworthy AI, retrieval augmented generation, large language models and graph machine learning.
If you are interested in my research or have any questions, please feel free to contact me.

# Research Interests
- Retrieval Augmented Generation
- Large Language Models
- Graph Neural Networks
- Trustworthy AI

# 🔥 News
- *2026.07*: &nbsp;🎉🎉 Our work "Towards Domain Generalized Neural Architecture Search via Language-Guided Visual Augmentation" has been ACCEPTED for publication in ACM Multimedia 2026 (Main Track).
- *2026.06*: &nbsp;🎉🎉 Our work "GraphTheft: Quantifying Privacy Risks in Graph Prompt Learning" has been ACCEPTED for publication in IEEE Transactions on Dependable and Secure Computing (TDSC).
- *2026.05*: &nbsp;🚀 We released the technical report for "AgentDoG 1.5: A Lightweight and Scalable Alignment Framework for AI Agent Safety and Security". Great Honor to work with colleagues from Shanghai AI Lab!
- *2026.04*: &nbsp;🎉🎉 Our work "Is There a Structural Privacy Risk in Graph Prompting with LLMs?" has been ACCEPTED for publication in International Conference on Database Systems for Advanced Applications (DASFAA 2026).
- *2025.11*: &nbsp;🎉🎉 Our work "Large language models driven neural architecture search for universal and lightweight disease diagnosis on histopathology slide images" has been ACCEPTED for publication in npj Digital Medicine.
- *2025.01*: &nbsp;🎉🎉 Our work "FeCoGraph: Label-aware Federated Graph Contrastive Learning for Few-shot Network Intrusion Detection" has been ACCEPTED for publication as a REGULAR paper in IEEE Transactions on Information Forensics & Security.
# 📝 Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div> -->
<!-- <div class='paper-box-text' markdown="1"> -->

## 📄 Conference & Journal Papers

- Towards Domain Generalized Neural Architecture Search via Language-Guided Visual Augmentation <br>
**Qinghua Mao**, Xi Lin, Zhongze Wu, Jun Wu, Xiangrui Cai, Xiu Su <br>
ACM Multimedia 2026 (Main Track)

- GraphTheft: Quantifying Privacy Risks in Graph Prompt Learning <br>
[paper](https://arxiv.org/pdf/2411.14718) <br>
Jiani Zhu, Xi Lin, Yuxin Qi, **Qinghua Mao**, Jun Wu <br>
IEEE Transactions on Dependable and Secure Computing (TDSC), 2026

- Is There a Structural Privacy Risk in Graph Prompting with LLMs? <br>
Jiani Zhu, Xi Lin, Yuxin Qi, **Qinghua Mao**, Jianhua Li, Jun Wu <br>
International Conference on Database Systems for Advanced Applications (DASFAA 2026)

- Large language models driven neural architecture search for universal and lightweight disease diagnosis on histopathology slide images <br>
[paper](https://www.nature.com/articles/s41746-025-02042-x) <br>
Xiu Su, **Qinghua Mao**, Zhongze Wu, Xi Lin, Shan You, Yue Liao, Chang Xu <br>
npj Digital Medicine, 2025

- FeCoGraph: Label-aware Federated Graph Contrastive Learning for Few-shot Network Intrusion Detection <br>
[paper](https://ieeexplore.ieee.org/abstract/document/10884817) [code](https://github.com/MaoPopovich/FeCoGraph) <br>
**Qinghua Mao**, Xi Lin, Wenchao Xu, Yuxin Qi, Xiu Su, Gaolei Li, Jianhua Li <br>
IEEE Transactions on Information Forensics & Security (TIFS), 2025

- Prompting Label Efficiency in Federated Graph Learning Via Personalized Semi-Supervision <br>
[paper](https://ieeexplore.ieee.org/abstract/document/10448483) [code](https://github.com/MaoPopovich/pfl_graph) <br>
**Qinghua Mao**, Xi Lin, Xiu Su, Gaolei Li, Lixing Chen, Jianhua Li <br>
ICASSP 2024 - IEEE International Conference on Acoustics, Speech and Signal Processing

- Ensuring Minority Group Rights in Social IoT with Fairness-aware Federated Graph Node Classification <br>
[paper](https://ieeexplore.ieee.org/abstract/document/10491682) <br>
**Qinghua Mao**, Xi Lin, Gaolei Li, Lixing Chen, Yuchen Liu, Yuxin Qi, Jianhua Li <br>
IEEE ISPA/BDCloud/SocialCom/SustainCom 2023

- Multi-Level ACE-based IoT Knowledge Sharing for Personalized Privacy-Preserving Federated Learning <br>
[paper](https://ieeexplore.ieee.org/abstract/document/10566968) <br>
Jing Wang, Xi Lin, Jun Wu, **Qinghua Mao**, Bei Pei, Jianhua Li, Suchang Guo, Baitao Zhang <br>
IEEE MSN 2023

## 📑 Preprints & Working Papers

- Before Agent Tells The Lie: Has Deception Already Been Represented? <br>
[paper](https://arxiv.org/pdf/2610.06576) <br>
Xinling Li, Dadi Guo, Qingyu Liu, **Qinghua Mao**, Yi R Fung, Na Zou, Xia Hu, Dongrui Liu <br>
arXiv preprint arXiv:2610.06576, 2026

- SafeEvolve: Harness-Policy Co-Evolution from Agent Experience for Safety Alignment <br>
[paper](https://arxiv.org/pdf/2609.02786) <br>
**Qinghua Mao**, Wanying Qu, Dadi Guo, Leitao Yuan, Qingyu Liu, Yu Li, Guanxu Chen, Yanwei Fu, Xi Lin, Xia Hu, Dongrui Liu <br>
arXiv preprint arXiv:2609.02786, 2026

- SHE: Trajectory-Driven Safety Harness Evolution for LLM Agents <br>
[paper](https://arxiv.org/pdf/2608.09885) <br>
Wanying Qu, **Qinghua Mao**, Yu Li, Jiyao Liu, Xin Zhang, Dadi Guo, Yanxu Zhu, Qingyu Liu, Leitao Yuan, Xi Lin, Shanfeng Zhu, Yanwei Fu, Jing Shao, Xia Hu, Dongrui Liu <br>
arXiv preprint arXiv:2608.09885, 2026

- AgentDoG 1.5: A Lightweight and Scalable Alignment Framework for AI Agent Safety and Security <br>
[paper](https://arxiv.org/pdf/2605.29801) [project](https://ai45lab.github.io/AgentDoG/) <br>
Dongrui Liu, Yu Li, Zhonghao Yang, Peng Wang, Guanxu Chen, Yuejin Xie, **Qinghua Mao**, Wanying Qu, Yanxu Zhu, Tianyi Zhou, Leitao Yuan, Zhijie Zheng, Qihao Lin, Yimin Wang, Haoyu Luo, Shuai Shao, Chen Qian, Qingyu Liu, Ling Tang, Ruiyang Qin, Qihan Ren, Junxiao Yang, Kun Wang, Zhiheng Xi, Linfeng Zhang, Ranjie Duan, Bo Zhang, Wenjie Wang, Wen Shen, Qiaosheng Zhang, Yan Teng, Chaochao Lu, Rui Mei, Man Li, Jialing Tao, Xi Lin, Tianhang Zheng, Yong Liu, Quanshi Zhang, Lei Zhu, Xingjun Ma, Junhua Liu, Hui Xue, Xiaoxiang Zuo, Xiangnan He, Chao Shen, Xianglong Liu, Minlie Huang, Jing Shao, Xia Hu <br>
Technical Report / arXiv preprint arXiv:2605.29801, 2026

- Frequency-Domain Regularized Adversarial Alignment for Transferable Attacks against Closed-Source MLLMs <br>
[paper](https://arxiv.org/pdf/2605.21541) <br>
Leitao Yuan, **Qinghua Mao**, Daizong Liu, Kun Wang, Wenjie Wang, Yan Teng, Jing Shao, Dongrui Liu <br>
arXiv preprint arXiv:2605.21541, 2026

- Towards Multi-Task Generative-AI Edge Services with an Attention-based Diffusion DRL Approach <br>
[paper](https://arxiv.org/pdf/2405.08328) <br>
Yaju Liu, Xi Lin, Siyuan Li, Gaolei Li, **Qinghua Mao**, Jianhua Li <br>
arXiv preprint arXiv:2405.08328, 2024

- Improving Chinese Named Entity Recognition by Search Engine Augmentation <br>
[paper](https://arxiv.org/pdf/2210.12662) [code](https://github.com/MaoPopovich/FiD-NER) <br>
**Qinghua Mao**, Jiatong Li, Kui Meng <br>
arXiv preprint arXiv:2210.12662, 2022

# 📖 Educations
- *2022.09 - 2028.03 (expected)*, PhD candidate (master-doctor combind program), Computer Science and Cybersecurity, School of Computer Science, Shanghai Jiao Tong University. 
- *2018.09 - 2022.06*, Bachelor, Information Security, School of Electronic Information and Electrical Engineering, Shanghai Jiao Tong University. 


# 🎖 Honors
- *2022.06* Outstanding Graduate of Shanghai Jiao Tong Univeristy
- *2022-2025* 1st-Class Academic Scholarship for Graduate Students
- *2024.09* Advanced Individuals in Social Practice of SJTU
- *2021.08* 3rd-class Prize of National College Student Information Security Competition

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Service
- **Reviewer**: ICLR 2025/2026, ICCV 2025, AAAI 2026, 

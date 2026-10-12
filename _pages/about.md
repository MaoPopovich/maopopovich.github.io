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
I am currently a third-year PhD candidate at Shanghai Jiao Tong University, supervised by [Dr. Xi Lin](https://www.cs.sjtu.edu.cn/jiaoshiml/linxi.html). Currently, I am also a research intern at Shanghai AI Laboratory, mentored by [Dr. Dongrui Liu](https://shenqildr.github.io/).
I received my bachelor's degree of information security from School of Electronic Information and Electrical Engineering at Shanghai Jiao Tong University in 2022, supervised by [Dr. Kui Meng](https://infosec.sjtu.edu.cn/DirectoryDetail.aspx?id=144). 
My research interests include graph neural networks, agent safety & security, recursive self-improvement, and trustworthy AI.
If you are interested in my research or have any questions, please feel free to contact me.


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

- <span class="pub-badge">ACM MM 2026</span> [Towards Domain Generalized Neural Architecture Search via Language-Guided Visual Augmentation](#) <br>
**Qinghua Mao**, Xi Lin, Zhongze Wu, Jun Wu, Xiangrui Cai, Xiu Su <br>
*ACM Multimedia 2026 (Main Track)*

- <span class="pub-badge">IEEE TDSC</span> [GraphTheft: Quantifying Privacy Risks in Graph Prompt Learning](https://arxiv.org/pdf/2411.14718) <br>
Jiani Zhu, Xi Lin, Yuxin Qi, **Qinghua Mao**, Jun Wu <br>
*IEEE Transactions on Dependable and Secure Computing (TDSC), 2026*

- <span class="pub-badge">DASFAA 2026</span> [Is There a Structural Privacy Risk in Graph Prompting with LLMs?](https://link.springer.com/chapter/10.1007/978-981-97-2977-7_36) <br>
Jiani Zhu, Xi Lin, Yuxin Qi, **Qinghua Mao**, Jianhua Li, Jun Wu <br>
*International Conference on Database Systems for Advanced Applications (DASFAA 2026)*

- <span class="pub-badge">npj Digit. Med.</span> [Large language models driven neural architecture search for universal and lightweight disease diagnosis on histopathology slide images](https://www.nature.com/articles/s41746-025-02042-x) <br>
Xiu Su, **Qinghua Mao**, Zhongze Wu, Xi Lin, Shan You, Yue Liao, Chang Xu <br>
*npj Digital Medicine, 2025*

- <span class="pub-badge">IEEE TIFS</span> [FeCoGraph: Label-aware Federated Graph Contrastive Learning for Few-shot Network Intrusion Detection](https://ieeexplore.ieee.org/abstract/document/10884817) <br>
**Qinghua Mao**, Xi Lin, Wenchao Xu, Yuxin Qi, Xiu Su, Gaolei Li, Jianhua Li <br>
*IEEE Transactions on Information Forensics & Security (TIFS), 2025* <a href="https://github.com/MaoPopovich/FeCoGraph" target="_blank" class="pub-icon-link" title="GitHub Code"><i class="fab fa-github"></i></a>

- <span class="pub-badge">ICASSP 2024</span> [Prompting Label Efficiency in Federated Graph Learning Via Personalized Semi-Supervision](https://ieeexplore.ieee.org/abstract/document/10448483) <br>
**Qinghua Mao**, Xi Lin, Xiu Su, Gaolei Li, Lixing Chen, Jianhua Li <br>
*IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP 2024)* <a href="https://github.com/MaoPopovich/pfl_graph" target="_blank" class="pub-icon-link" title="GitHub Code"><i class="fab fa-github"></i></a>

- <span class="pub-badge">IEEE ISPA 2023</span> [Ensuring Minority Group Rights in Social IoT with Fairness-aware Federated Graph Node Classification](https://ieeexplore.ieee.org/abstract/document/10491682) <br>
**Qinghua Mao**, Xi Lin, Gaolei Li, Lixing Chen, Yuchen Liu, Yuxin Qi, Jianhua Li <br>
*IEEE ISPA/BDCloud/SocialCom/SustainCom 2023*

- <span class="pub-badge">IEEE MSN 2023</span> [Multi-Level ACE-based IoT Knowledge Sharing for Personalized Privacy-Preserving Federated Learning](https://ieeexplore.ieee.org/abstract/document/10566968) <br>
Jing Wang, Xi Lin, Jun Wu, **Qinghua Mao**, Bei Pei, Jianhua Li, Suchang Guo, Baitao Zhang <br>
*IEEE MSN 2023*

## 📑 Preprints & Working Papers

- [Before Agent Tells The Lie: Has Deception Already Been Represented?](https://arxiv.org/pdf/2610.06576) <br>
Xinling Li, Dadi Guo, Qingyu Liu, **Qinghua Mao**, Yi R Fung, Na Zou, Xia Hu, Dongrui Liu <br>
*arXiv preprint arXiv:2610.06576, 2026*

- [SafeEvolve: Harness-Policy Co-Evolution from Agent Experience for Safety Alignment](https://arxiv.org/pdf/2609.02786) <br>
**Qinghua Mao**, Wanying Qu, Dadi Guo, Leitao Yuan, Qingyu Liu, Yu Li, Guanxu Chen, Yanwei Fu, Xi Lin, Xia Hu, Dongrui Liu <br>
*arXiv preprint arXiv:2609.02786, 2026* <a href="https://github.com/MaoPopovich/SafeEvolve" target="_blank" class="pub-icon-link" title="GitHub Code"><i class="fab fa-github"></i></a>

- [SHE: Trajectory-Driven Safety Harness Evolution for LLM Agents](https://arxiv.org/pdf/2608.09885) <br>
Wanying Qu, **Qinghua Mao**, Yu Li, Jiyao Liu, Xin Zhang, Dadi Guo, Yanxu Zhu, Qingyu Liu, Leitao Yuan, Xi Lin, Shanfeng Zhu, Yanwei Fu, Jing Shao, Xia Hu, Dongrui Liu <br>
*arXiv preprint arXiv:2608.09885, 2026* <a href="https://github.com/RainbowQTT/SHE" target="_blank" class="pub-icon-link" title="GitHub Code"><i class="fab fa-github"></i></a>

- [AgentDoG 1.5: A Lightweight and Scalable Alignment Framework for AI Agent Safety and Security](https://arxiv.org/pdf/2605.29801) <br>
Dongrui Liu, Yu Li, Zhonghao Yang, Peng Wang, Guanxu Chen, Yuejin Xie, **Qinghua Mao**, Wanying Qu, Yanxu Zhu, Tianyi Zhou, et al. <br>
*Technical Report / arXiv preprint arXiv:2605.29801, 2026* <a href="https://github.com/AI45Lab/AgentDoG" target="_blank" class="pub-icon-link" title="GitHub Code"><i class="fab fa-github"></i></a> [<a href="https://ai45lab.github.io/AgentDoG/" target="_blank">Project</a>]

- [Frequency-Domain Regularized Adversarial Alignment for Transferable Attacks against Closed-Source MLLMs](https://arxiv.org/pdf/2605.21541) <br>
Leitao Yuan, **Qinghua Mao**, Daizong Liu, Kun Wang, Wenjie Wang, Yan Teng, Jing Shao, Dongrui Liu <br>
*arXiv preprint arXiv:2605.21541, 2026*

- [Towards Multi-Task Generative-AI Edge Services with an Attention-based Diffusion DRL Approach](https://arxiv.org/pdf/2405.08328) <br>
Yaju Liu, Xi Lin, Siyuan Li, Gaolei Li, **Qinghua Mao**, Jianhua Li <br>
*arXiv preprint arXiv:2405.08328, 2024*

- [Improving Chinese Named Entity Recognition by Search Engine Augmentation](https://arxiv.org/pdf/2210.12662) <br>
**Qinghua Mao**, Jiatong Li, Kui Meng <br>
*arXiv preprint arXiv:2210.12662, 2022* <a href="https://github.com/MaoPopovich/FiD-NER" target="_blank" class="pub-icon-link" title="GitHub Code"><i class="fab fa-github"></i></a>

# 📖 Educations
- *2022.09 - 2028.03 (expected)*, Ph.D. in Computer Science and Cybersecurity, Shanghai Jiao Tong University.
- *2018.09 - 2022.06*, B.Eng. in Information Security, Shanghai Jiao Tong University.

# 💼 Internships
- *2026.02 - Present*, Research Intern, Shanghai AI Laboratory, Shanghai.

# 🎖 Honors and Awards
- *2024.09* Advanced Individual in Social Practice of SJTU
- *2022.09* 1st-Class Academic Scholarship for Graduate Students (2022 - 2025)
- *2022.06* Outstanding Graduate of Shanghai Jiao Tong University
- *2021.08* 3rd-Class Prize of National College Student Information Security Competition

# 💻 Service
- **Reviewer**: ICLR 2025/2026, ICCV 2025, AAAI 2026

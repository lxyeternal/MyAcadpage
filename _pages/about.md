---
permalink: /
title: "Homepage"
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

Wenbo Guo (郭文博) is a third-year Ph.D. candidate in the School of Computer and Data Science at Nanyang Technological University (NTU), advised by [Prof. Yang Liu](https://personal.ntu.edu.sg/yangliu/).

In 2020, he graduated with honors and earned his Bachelor's degree from Sichuan University. He was subsequently offered direct admission to graduate school at the School of Cyber Security at Sichuan University, where he continued his academic journey towards a Master's degree. During this stage, he was co-advised by Prof. Fang Yong and [Prof. Cheng Huang](https://chenghuang.org/).

His research interests include supply chain security and open-source intelligence.


# 🔥 News
- *2026.04*: &nbsp;🎉🎉 One paper was accepted by ISSTA 2026!
- *2026.01*: &nbsp;🎉🎉 One paper was accepted by USENIX Security 2026!
- *2026.01*: &nbsp;🎉🎉 One paper was accepted by WWW 2026!
- *2025.12*: &nbsp;🎉🎉 One paper was accepted by FSE 2026!
- *2025.12*: &nbsp;🎉🎉 Our team won the First Prize (Top 2) in the Prototype System Competition at CCF ChinaSoft (中国软件大会)!
- *2025.10*: &nbsp;🎉🎉 Our paper "IntelliRadar" was accepted by ICSE 2026! 
- *2025.10*: &nbsp;🎉🎉 He successfully passed the Qualifying Examination (QE) and became a Ph.D. candidate at NTU!
- *2025.09*: &nbsp;🎉🎉 Our paper "BinStruct: Binary Structure Recovery Combining Static Analysis and Semantics" was accepted by ICSE 2025! 
- *2025.01*: &nbsp;🎉🎉 He was selected for the OpenAI Researcher Access Program with $8,000 USD in API credits!
- *2024.05*: &nbsp;🎉🎉 He was appointed as a member of the Datacon Expert Committee.
- *2024.01*: &nbsp;🎉🎉 He joined the Nanyang Technological University as a Ph.D. student.
- *2023.07*: &nbsp;🎉🎉 Our paper "An Empirical Study of Malicious Code In PyPI Ecosystem" was accepted by ASE 2023! 
- *2023.06*: &nbsp;🎉🎉 He obtained the master's degree from SCU.
- *2023.03*: &nbsp;🎉🎉 He was awarded the title of Outstanding Graduate of Sichuan Province.


# 📝 Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->

- [Characterizing and Repairing Obsolete Android GUI Tests under UI Evolution]()
![](https://img.shields.io/badge/CCF-A-red?style=flat-square)![](https://img.shields.io/badge/CORE-A*-red?style=flat-square)
  - Shiwen Song, Yiheng Xiong, **Wenbo Guo**, Manqi Sun, Jiaolong Kong, Xiaofei Xie
  - ACM SIGSOFT International Symposium on Software Testing and Analysis (ISSTA), 2026
  - This paper characterizes obsolete Android GUI tests caused by UI evolution and proposes an automated approach to repair them.

- [Understanding NPM Malicious Package Detection: A Benchmark-Driven Empirical Analysis](https://arxiv.org/abs/2603.27549)
![](https://img.shields.io/badge/arXiv-preprint-b31b1b?style=flat-square)
  - **Wenbo Guo**, Zhongwen Chen, Zhengzi Xu, Chengwei Liu, Ming Kang, Shiwen Song, Chengyue Liu, Yijia Xu, Weisong Sun, Yang Liu
  - arXiv preprint, 2026
  - This paper presents a benchmark-driven empirical analysis for understanding NPM malicious package detection.

- [Cutting the Gordian Knot: Detecting Malicious PyPI Packages via a Knowledge-Mining Framework](https://arxiv.org/abs/2601.16463)
![](https://img.shields.io/badge/CCF-A-red?style=flat-square)![](https://img.shields.io/badge/CORE-A*-red?style=flat-square)
  - **Wenbo Guo**, Chengwei Liu, Ming Kang, Yiran Zhang, Jiahui Wu, Zhengzi Xu, Vinay Sachidananda, Yang Liu
  - USENIX Security Symposium (USENIX Security), 2026
  - This paper proposes a knowledge-mining framework that transforms false positives from existing tools into knowledge to drive malicious package detection, discovering over 500 new malicious packages in the PyPI ecosystem.

- [Bridging Expert Reasoning and LLM Detection: A Knowledge-Driven Framework for Malicious Packages](https://arxiv.org/abs/2601.16458)
![](https://img.shields.io/badge/CCF-A-red?style=flat-square)![](https://img.shields.io/badge/CORE-A*-red?style=flat-square)
  - **Wenbo Guo**, Shiwen Song, Jiaxun Guo, Zhengzi Xu, Chengwei Liu, Haoran Ou, Mengmeng Ge, Yang Liu
  - The Web Conference (WWW), 2026
  - This paper proposes a knowledge-driven framework that extracts and summarizes knowledge from historical expert malware analysis reports to drive LLM-based malicious package detection.

- [Casting a SPELL: Sentence Pairing Exploration for LLM Limitation-breaking](https://arxiv.org/abs/2512.21236)
![](https://img.shields.io/badge/CCF-A-red?style=flat-square)![](https://img.shields.io/badge/CORE-A*-red?style=flat-square)
  - Yifan Huang, Xiaojun Jia, **Wenbo Guo**, Yuqiang Sun, Yihao Huang, Chong Wang, Yang Liu
  - ACM International Conference on the Foundations of Software Engineering (FSE), 2026
  - This paper proposes SPELL, a testing framework that evaluates security alignment weaknesses in LLM code generation through time-division sentence pairing strategies, achieving high attack success rates across major code models.

- [IntelliRadar: A Comprehensive Platform to Pinpoint Malicious Packages from Cyber Intelligence](https://arxiv.org/abs/2409.15049)
![](https://img.shields.io/badge/CCF-A-red?style=flat-square)![](https://img.shields.io/badge/CORE-A*-red?style=flat-square)
  - **Wenbo Guo**, Chengwei Liu, Limin Wang, Yiran Zhang, Jiahui Wu, Zhengzi Xu, Yang Liu
  - 48th International Conference on Software Engineering (ICSE), 2026
  - This paper presents IntelliRadar, a comprehensive platform designed to identify and pinpoint malicious packages using cyber intelligence.

- [BinStruct: Binary Structure Recovery Combining Static Analysis and Semantics](https://ieeexplore.ieee.org/document/11334428/)
![](https://img.shields.io/badge/CCF-A-red?style=flat-square)![](https://img.shields.io/badge/CORE-A*-red?style=flat-square)
  - Yiran Zhang, Zhengzi Xu, Zhe Lang, Chengyue Liu, Yuqiang Sun, **Wenbo Guo**, Chengwei Liu, Weisong Sun, Yang Liu
  - 40th IEEE/ACM International Conference on Automated Software Engineering (ASE), 2025
  - This paper proposes BinStruct, a novel framework that combines static analysis and semantics for binary structure recovery.

- [Evolaris: A Roadmap to Self-Evolving Software Intelligence Management](https://arxiv.org/abs/2510.04689)
![](https://img.shields.io/badge/CCF-C-green?style=flat-square)![](https://img.shields.io/badge/CORE-B-blue?style=flat-square)
  - Chengwei Liu, **Wenbo Guo**, Yuxin Zhang, Limin Wang, Sen Chen, Lei Bu, Yang Liu
  - 29th International Conference on Engineering of Complex Computer Systems (ICECCS), 2025 (Position Paper)
  - This paper presents Evolaris, a roadmap to self-evolving software intelligence management.

- [SpearBot: Leveraging Large Language Models in a Generative-Critique Framework for Spear-Phishing Email Generation](https://www.sciencedirect.com/science/article/abs/pii/S1566253525002490)
![](https://img.shields.io/badge/Journal-Q1-red?style=flat-square)
  - Qinglin Qi, Yun Luo, Yijia Xu, **Wenbo Guo**, Yong Fang
  - Information Fusion, Volume 122, 2025 <strong><span class='show_paper_citations' data='qIvpXMAAAAAJ:W7OEmFMy1HYC'></span></strong>
  - This paper proposes SpearBot, a novel framework that leverages large language models in a generative-critique approach for automated spear-phishing email generation.

- [Few-shot graph classification on cross-site scripting attacks detection](https://www.sciencedirect.com/science/article/abs/pii/S0167404824000506) 
![](https://img.shields.io/badge/CCF-B-blue?style=flat-square)
  - Hongyu Pan, Yong Fang, **Wenbo Guo**, Yijia Xu, Changhui Wang
  - Computers & Security, 2024 <strong><span class='show_paper_citations' data='KAWDTzsAAAAJ:eQOLeE2rZwMC'></span></strong>
  - This paper is about detecting cross-site scripting attacks using the few-shot learning.

<details markdown="1">
<summary><b>Show more publications</b></summary>

- [An Empirical Study of Malicious Code In PyPI Ecosystem](https://arxiv.org/pdf/2309.11021) 
![](https://img.shields.io/badge/CCF-A-red?style=flat-square) ![](https://img.shields.io/badge/CORE-A*-red?style=flat-square)
  - **Wenbo Guo**, Zhengzi Xu, Chengwei Liu, Cheng Huang, Yong Fang, Yang Liu
  - 2023 38th IEEE/ACM International Conference on Automated Software Engineering (ASE) <strong><span class='show_paper_citations' data='qIvpXMAAAAAJ:UeHWp8X0CEIC'></span></strong>
  - This paper is the empirical study paper for the malicious packages in the PyPI Package Manager.
  - We constructed the largest PyPI malicious package dataset and open-sourced the dataset at [here](https://github.com/lxyeternal/pypi_malregistry)

- [HyVulDect: a hybrid semantic vulnerability mining system based on graph neural network](https://dl.acm.org/doi/10.1016/j.cose.2022.102823) 
![](https://img.shields.io/badge/CCF-B-blue?style=flat-square)
  - **Wenbo Guo**, Yong Fang, Cheng Huang, Haoran Ou, Chun Lin, Yongyan Guo
  - Computers & Security, 2022 <strong><span class='show_paper_citations' data='qIvpXMAAAAAJ:9yKSN-GCB0IC'></span></strong>
  - This paper is about vulnerability detection based on the graph neural network. 

- [Viopolicy-detector: An automated approach to detecting GDPR suspected compliance violations in websites](https://dl.acm.org/doi/abs/10.1145/3545948.3545952)
![](https://img.shields.io/badge/CCF-B-blue?style=flat-square)![](https://img.shields.io/badge/CORE-A-red?style=flat-square)
  - Haoran Ou, Yong Fang, Yongyan Guo, **Wenbo Guo**, Cheng Huang
  - Proceedings of the 25th International Symposium on Research in Attacks, Intrusions and Defenses (RAID 2022) <strong><span class='show_paper_citations' data='qIvpXMAAAAAJ:u5HHmVD_uO8C'></span></strong>
  - This paper is about detecting privacy compliance using machine learning method. 

- [Intelligent mining vulnerabilities in python code snippets](https://content.iospress.com/articles/journal-of-intelligent-and-fuzzy-systems/ifs211011) 
  - **Wenbo Guo**, Cheng Huang, Weina Niu, Yong Fang
  - Journal of Intelligent & Fuzzy Systems, 2021 <strong><span class='show_paper_citations' data='qIvpXMAAAAAJ:u-x6o8ySG0sC'></span></strong>
  - This paper is about detecting python vulnerability using the machine learning method. 

- [HackerRank: Identifying key hackers in underground forums](https://journals.sagepub.com/doi/full/10.1177/15501477211015145) 
  - Cheng Huang, Yongyan Guo, **Wenbo Guo**, Ying Li
  - International Journal of Distributed Sensor Networks, 2021 <strong><span class='show_paper_citations' data='qIvpXMAAAAAJ:d1gkVwhDpl0C'></span></strong>
  - This paper is about detecting key hackers in the underground forums.

- [No Pie in the Sky: The Digital Currency Fraud Website Detection](https://link.springer.com/chapter/10.1007/978-3-031-06365-7_11)
![](https://img.shields.io/badge/CCF-C-green?style=flat-square)
  - Haoran Ou, Yongyan Guo, Chaoyi Huang, Zhiying Zhao, **Wenbo Guo**, Yong Fang, Cheng Huang
  - 2021 IEEE 12th EAI International Conference on Digital Forensics & Cyber Crime (ICDF2C) <strong><span class='show_paper_citations' data='qIvpXMAAAAAJ:qjMakFHDy7sC'></span></strong>
  - This paper is about detecting Ponzi cryptocurrency using machine learning methods.

- [Research on QR code logistics privacy based on segmented encryption and time-limited control](https://www.infocomm-journal.com/cjnis/CN/10.11959/j.issn.2096-109x.2019039)
![](https://img.shields.io/badge/CCF-C-green?style=flat-square)
  - Liang Liu, **Wenbo Guo**, Yuwei Yang, Huaiyu Guo
  - Chinese Journal of Network and Information Security, 2019 <strong><span class='show_paper_citations' data='qIvpXMAAAAAJ:IjCSPb-OGe4C'></span></strong>
  - This paper is about a privacy protection scheme based on QR code segmentation encryption.

</details>


# 📖 Educations
- *2024.01 - Now*, Ph.D. Student at College of Computing and Data Science, Nanyang Technological University, Singapore.
- *2020.09 - 2023.06*, Postgraduate student at School of Cyber Science and Engineering, Sichuan University, Chengdu, Sichuan, P.R.C. 
- *2016.09 - 2020.06*, Undergraduate student at School of Cyber Science and Engineering, Sichuan University, Chengdu, Sichuan, P.R.C.
 

# 🎖 Honors and Awards
- *2023.06* Sichuan Province Government, Excellent Graduates.
- *2021.12* Sichuan University, Dahua Scholarship.
- *2019.10* Chinese Ministry of Education, National Inspirational Scholarship. 

<!-- # 💬 Invited Talks
- *2024.05*, Transforming Language Models into Smart Contract Audit Experts. GeekCon 2024 @ Singapore
  - [Slides](assets/pdf/geekcon2024.pdf) -->

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->

# 📫 Services

- Reviewer: IEEE Transactions on Dependable and Secure Computing (TDSC) (2025)
- Reviewer: Transactions on Information Forensics & Security (TIFS) (2025, 2026)
- Reviewer: Expert Systems with Applications (2026)
- Reviewer: ACM International Conference on AI-powered Software (AIware) (2026)
- Reviewer: Journal of Intelligent & Fuzzy Systems (2022)


# 📚 Teaching

- Part-time Student Mentor: School of Cyber Science and Engineering @ SCU, 2020-2023

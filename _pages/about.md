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

Yuqiang Sun (孙宇强 in Chinese) is now a Ph.D. student in School of Computer Science and Engineering @ Nanyang Technological University, supervised by [Prof. Yang Liu](https://personal.ntu.edu.sg/yangliu/).
Before Ph.D. study, he got his bachelor degree in Sichuan University.
His research interests include program analysis, vulnerability detection and patch generation.
He hopes to collaborate with more innovative researchers on various exciting topics in software engineering, program analysis, vulnerability detection, and program synthesis.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=KAWDTzsAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=KAWDTzsAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2023.08*: &nbsp;🎉🎉 Our preprint "When GPT Meets Program Analysis: Towards Intelligent Detection of Smart Contract Logic Vulnerabilities in GPTScan" is published on Arxiv! 
- *2023.08*: &nbsp;🎉🎉 He passed Qualifying Examination (QE) and became a Ph.D. candidate.
- *2023.07*: &nbsp;🎉🎉 Our paper "Who is the Real Hero? Measuring Developer Contribution via Multi-dimensional Data Integration" is accepted by ASE 2023! 
- *2021.08*: &nbsp;🎉🎉 He joined Nanyang Technological University as a Ph.D. student. 

# 📝 Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->

<!-- </div>
</div> -->

- [When GPT Meets Program Analysis: Towards Intelligent Detection of Smart Contract Logic Vulnerabilities in GPTScan](https://arxiv.org/abs/2308.03314) 
[![](https://img.shields.io/badge/arXiv-2308.03314-B31B1B?style=flat-square)](https://arxiv.org/abs/2308.03314)
  - **Yuqiang Sun**, Daoyuan Wu, Yue Xue, Han Liu, Haijun Wang, Zhengzi Xu, Xiaofei Xie, Yang Liu
  - Preprint
  - [**Paper**](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=KAWDTzsAAAAJ&citation_for_view=KAWDTzsAAAAJ:9yKSN-GCB0IC) <strong><span class='show_paper_citations' data='KAWDTzsAAAAJ:9yKSN-GCB0IC'></span></strong>

  - This paper is about combining LLM with static analysis method to detect vulnerabilities in smart contracts. 


- [Who is the Real Hero? Measuring Developer Contribution via Multi-dimensional Data Integration](https://ieeexplore.ieee.org/document/10298552/) 
![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/ASE-2023-blue?style=flat-square)](https://ieeexplore.ieee.org/document/10298552/)
  - **Yuqiang Sun**, Zhengzi Xu, Chengwei Liu, Yiran Zhang, Yang Liu
  - The 38th IEEE/ACM International Conference on Automated Software Engineering (ASE 2023)
  - [**Paper**](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=KAWDTzsAAAAJ&citation_for_view=KAWDTzsAAAAJ:qjMakFHDy7sC) <strong><span class='show_paper_citations' data='KAWDTzsAAAAJ:qjMakFHDy7sC'></span></strong>
  - This paper is about measuring the contribution of developers in open source projects. We proposed an approach to fuse information from different dimensions for a more comprehensive evaluation of developer contribution. 

- [WAIN: Automatic Web Application Identification and Naming Method](https://dl.acm.org/doi/abs/10.1145/3545258.3545271) 
![](https://img.shields.io/badge/CCF-C-green?style=flat-square)
  - **Yuqiang Sun**, Dunhan Li, Yixin Wu, Xuelin Wan, Cheng Huang
  - Proceedings of the 13th Asia-Pacific Symposium on Internetware, 2022
  - [**Paper**](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=KAWDTzsAAAAJ&citation_for_view=KAWDTzsAAAAJ:2osOgNQ5qMEC) <strong><span class='show_paper_citations' data='KAWDTzsAAAAJ:2osOgNQ5qMEC'></span></strong>
  - This paper is about generating fingerprints for unknown web assets for better management.

- [MineDetector: JavaScript Browser-side Cryptomining Detection using Static Methods](https://ieeexplore.ieee.org/abstract/document/9724605/)
  - Peiran Wang, **Yuqiang Sun**, Cheng Huang, Yutong Du, Genpei Liang, Gang Long
  - 2021 IEEE 24th International Conference on Computational Science and Engineering (CSE)
  - [**Paper**](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=KAWDTzsAAAAJ&citation_for_view=KAWDTzsAAAAJ:d1gkVwhDpl0C) <strong><span class='show_paper_citations' data='KAWDTzsAAAAJ:d1gkVwhDpl0C'></span></strong>
  - This paper is about detecting cryptomining in JavaScript code using machine learning methods.

- [Session-Based Webshell Detection Using Machine Learning in Web Logs](https://www.hindawi.com/journals/scn/2019/3093809/)
![](https://img.shields.io/badge/CCF-C-green?style=flat-square)
  - Yixin Wu, **Yuqiang Sun**, Cheng Huang, Peng Jia, Luping Liu
  - Security and Communication Networks, 2019
  - [**Paper**](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=KAWDTzsAAAAJ&citation_for_view=KAWDTzsAAAAJ:u5HHmVD_uO8C) <strong><span class='show_paper_citations' data='KAWDTzsAAAAJ:u5HHmVD_uO8C'></span></strong>
  - This paper is about detecting webshell activities through logs of the web server with machine learning method.

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2021.08 - Now*, Ph.D. student at school of computer science and engineering, Nanyang Technological University, Singapore.
- *2017.09 - 2021.06*, Undergraduate student at college of cyber space and engineering, Sichuan University, Chengdu, Sichuan, P.R.C. 

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->

# 📚 Services

- Member of Junior PC of MSR 2024
- Member of Artifact Evaluation Committee of Usenix Security 2024

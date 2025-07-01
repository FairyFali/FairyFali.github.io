---
layout: archive
title: " "
permalink: /kdd2025-tutorial/
author_profile: true
redirect_from: 
  - /kdd2025_tutorial
  - /kdd25_tutorial
  - /kdd25-tutorial
---

<center>
<h1>
KDD'25 A Tutorial on Small Language Models in the Era of Large Language Models: Architecture, Capabilities, and Trustworthiness	
</h1>
Fali Wang<sup>1</sup>, Minhua Lin<sup>1</sup>, Yao Ma<sup>2</sup>, Hui Liu<sup>3</sup>, Qi He, Xianfeng Tang<sup>3</sup>, Jiliang Tang<sup>4</sup>, Jian Pei<sup>5</sup>, Suhang Wang<sup>1</sup><br/>
1 The Pennsylvania State University<br/>
2 Rensselaer Polytechnic Institute<br/>
3 Amazon<br/>
4 Michigan State University<br/>
5 Duke University<br/>
Time: Aug 3, 2025 8:00 AM - 11:00 AM (EDT)<br/>
Location: The Metro Toronto Convention Centre on the 700 level, Toronto, Canada
</center>

## Abstract

Large language models (LLMs) based on the Transformer architecture are powerful but face challenges with deployment, inference latency, and costly fine-tuning. 
These limitations highlight the emerging potential of small language models (SLMs), which can either replace LLMs through innovative architectures and technologies, or assist them as efficient proxy or reward models.
Emerging architectures such as Mamba and xLSTM address the quadratic scaling of inference with window length in Transformers by enabling linear scaling.
To maximize SLM performance, test-time compute scaling strategies reduce the performance gap with LLMs by allocating extra compute budget during test time.
Beyond standalone usage, SLMs could also assist in LLMs via weak-to-strong learning, proxy tuning, and guarding, fostering secure and efficient LLM deployment. 
Lastly, the trustworthiness of SLMs remains a critical yet underexplored research area.
However, there is a lack of tutorials on cutting-edge SLM technologies, prompting us to conduct one.


This tutorial covers recent progress in Small Language Models (SLMs) in the era of Large Language Models (LLMs), focusing on architecture, capabilities, and trustworthiness.
1. LLM Foundations: Overview of recent LLM developments that support and inspire SLM design.
2. SLM Architecture: Efficient architectures tailored for small-scale models, including Transformer variants and state-space models.
3. From Weak to Strong: Techniques to boost SLM performance include distillation, test-time scaling, retrieval augmentation, and agent collaboration.
4. Trustworthiness: SLM robustness in adversarial settings, jailbreak resistance, fairness, and privacy.

## Schedule

- **Introduction**: 5 mins (8:00–8:05) — *Suhang Wang*
- **Part I: LLM Foundations**: 20 mins (8:05–8:25) — *Suhang Wang*
- **Part II: Architecture of SLMs**: 35 mins (8:25–9:00) — *Fali Wang*
- **Coffee Break**: 15 mins (9:00–9:15)
- **Part III: Weak to Strong Methods**: 45 mins (9:15–10:00) — *Fali Wang*
- **Part IV: Trustworthiness of SLMs**: 45 mins (10:00–10:40) — *Minhua Lin*
- **Conclusion + Q&A Session**: 15 mins (10:40–11:00) — *All*


## Slides
* Introduction [to-fill-the-link-later]
* Part I: SLM Architecture
* Part II: Weak to Strong Methods
* Part III: Trustworthiness 
* Conclusion 

## Authors

<img align="left" src="/images/Fali Wang.jpg" alt="Fali Wang" style="width: 200px; margin-right: 50px;" />
<b>Fali Wang</b> is a senior Ph.D. candidate in informatics at the Pennsylvania State University (PSU), under the guidance of Dr. Suhang Wang. Before joining PSU, he earned his M.S. degree in 2021 from UCAS and his B.E. in 2018 from NEFU. His research primarily focuses on LLM Knowledge and Graph Learning.
<br style="clear: both;" />

<img align="left" src="/images/tofill.png" alt="Minhua Lin" style="width: 200px; margin-right: 50px;" />
<b>Minhua Lin</b> is senior Ph.D. candidate in informatics at the Pennsylvania State University (PSU), under the supervision of Dr. Suhang Wang and Dr. Xiang Zhang. Before joining PSU, he earned his B.E. degree in Computer Science from Huazhong University of Sciences and Technology in 2021. His research primarily focuses on large language models, graph learning, trustworthy AI, and their intersections.
<br style="clear: both;" />

<img align="left" src="/images/yaoma.jpg" alt="Yao Ma" style="width: 200px; margin-right: 50px;" />
<b>Yao Ma</b> is an Assistant Professor in the Department of Computer Science at the Rensselaer Polytechnic Institute (RPI). Before joining RPI, he worked as an Assistant Professor at the New Jersey Institute of Technology (NJIT) for two years. He received his Ph.D. in Computer Science from Michigan State University (MSU) in 2021, with a focus on ML with graph-structured data. His research contributions to this area have led to numerous innovative works presented at top-tier conferences such as KDD, WWW, WSDM, ICLR, NeurIPS, and ICML. He has also organized and presented several well-received tutorials at AAAI and KDD, attracting over 1000 attendees. He is the author of the book "Deep Learning on Graphs", which has been downloaded tens of thousands of times from over 100 countries. He was awarded the Outstanding Graduate Student Award (2019-2020) from the College of Engineering at MSU.  He has also organized four workshops at ICDM, WSDM, and SDM.
<br style="clear: both;" />

<img align="left" src="/images/Wang-Suhang.jpg" alt="Suhang Wang" style="width: 200px; margin-right: 50px;" />
<b>Suhang Wang</b> is an Associate Professor of the College of IST at The Pennsylvania State University. His research interests include graph mining, trustworthy machine learning, and generative artificial intelligence. He has published 150+ papers in top-tier machine learning and data mining conferences and journals, which have garnered 22,900+ Google Scholar citations with an h-index of 61. He is a recipient of the AI 2000 Most Influential Scholar Honorable Mention from AMiner and the 2022 Global Top Chinese Young Scholars in Artificial Intelligence. He has served as an area chair and senior PC member for many conferences, such as KDD, NeurIPS, WSDM, and CIKM. He is also an associate editor for Neurocomputing, ACM TKDD, ACM TIST, and Frontiers in Big Data. 
<br style="clear: both;" />

<img align="left" src="/images/huiliu.jpg" alt="Hui Liu" style="width: 200px; margin-right: 50px;" />
<b>Hui Liu</b> is an Applied Scientist at Amazon Search. He received his PhD from Queen’s University, Canada, and a Bachelor's degree from Peking University. His research mainly focuses on natural language processing, large language models, text mining, and machine learning. He has publications in top-tier conferences such as ACL, EMNLP, ICLR, etc.
<br style="clear: both;" />

<img align="left" src="/images/qihe.jpg" alt="Qi He" style="width: 200px; margin-right: 50px;" />
<b>Qi He</b> is a technical leader in AI and its business applications, with a track record of 20 years of experience leading and executing large, complex AI projects. He serves as a Steering Committee member of ACM CIKM and an advisory board member of Neurocomputing Journal. He held many editorial and conference chair positions, including Associate Editor of IEEE TKDE and Neurocomputing Journal, General Chair of CIKM 2013, PC Chair of CIKM 2019, and Industry Chair of Web 2024, while also serving as a (senior) program committee member of SIGKDD, SIGIR, WWW, CIKM, and WSDM for over a decade. Qi has published over 70 papers and patents with over 7000 citations to date. He received the 2008 ACM SIGKDD Best Application Paper Award and the 2020 ACM WSDM 10-year Test of Time Award. Qi is an IEEE Fellow, ACM Distinguished Member, and was featured as the People of ACM in February 2021. 
<br style="clear: both;" />

<img align="left" src="/images/xianfengtang.jpg" alt="Xianfeng Tang" style="width: 200px; margin-right: 50px;" />
<b>Xianfeng Tang</b> is a senior Applied Scientist at Amazon. His research is mainly about machine learning, graph neural networks, data mining, and natural language understanding. He obtained a PhD degree from PSU and a Bachelor's degree from the University of Science and Technology of China. He has published works in top-tier conferences such as ICLR, ICML, NeurIPS, KDD, etc. 
<br style="clear: both;" />

<img align="left" src="/images/jiliang.jpg" alt="Jiliang Tang" style="width: 200px; margin-right: 50px;" />
<b>Jiliang Tang</b> is a University Foundation Professor in the computer science and engineering department at Michigan State University. His research interests include graph machine learning, trustworthy AI, and their applications in Education and Biology. He authored the first comprehensive book “deep learning on graphs” with Cambridge University Press and developed various well-received open-sourced tools, including scikit-feature for feature selection, DeepRobust for trustworthy AI, and DANCE for single-cell analysis. He was the recipient of various career awards (2022 IAPR J. K. AGGARWAL, 2022 SIAM SDM, 2021 IEEE ICDM, 2021 IEEE Big Data Security, 2020 ACM SIGKDD, 2019 NSF), numerous industrial faculty awards, and 8 best paper awards (or runner-ups), including WSDM2018 and KDD2016. He serves as conference organizers (e.g., KDD, SIGIR, WSDM, and SDM) and journal editors (e.g., TKDD, TOIS and TKDE). He has organized 20+ workshops in top AI conferences such as AI for Education in AAAI20, AAAI2021 Spring Symposium on Artificial Intelligence for K-12 Education, DLG-AAAI'21, and DLG-AAAI'23. He has published his research in highly ranked journals and top conference proceedings, which have more than 43,000 citations with an h-index of 99 and extensive media coverage.
<br style="clear: both;" />

<img align="left" src="/images/jianpei.jpg" alt="Jian Pei" style="width: 200px; margin-right: 50px;" />
<b>Jian Pei</b> is a Professor and Chair at Duke University, holding a joint position among Computer Science, Biostatistics and Bioinformatics, and Electric and Computer Engineering. He is a renowned researcher in data science, big data, data mining, and database systems. He is recognized as a Fellow of the Royal Society of Canada (i.e., the national academy of Canada), the Canadian Academy of Engineering, the ACM, and the IEEE. At the same time, he is also renowned for his active and productive professional leadership. Jian Pei is one of the most cited authors in data mining, database systems, and information retrieval. Since 2000, he has published one textbook, two monographs, and over 200 research papers in refereed journals and conferences, which have been cited over 130,000 times. He received many prestigious awards, including the 2017 ACM SIGKDD Innovation Award, the 2015 ACM SIGKDD Service Award, and the 2014 IEEE ICDM Research Contributions Award.
<br style="clear: both;" />

Website: https://FairyFali.github.io/

<br/>
<br/>
<br/>

## BibTeX
```
@article{wang2024comprehensive,
  title={A Comprehensive Survey of Small Language Models in the Era of Large Language Models: Techniques, Enhancements, Applications, Collaboration with LLMs, and Trustworthiness},
  author={Wang, Fali and Zhang, Zhiwei and Zhang, Xianren and Wu, Zongyu and Mo, Tzuhao and Lu, Qiuhao and Wang, Wanjing and Li, Rui and Xu, Junjie and Tang, Xianfeng and others},
  journal={arXiv preprint arXiv:2411.03350},
  year={2024}
}
```


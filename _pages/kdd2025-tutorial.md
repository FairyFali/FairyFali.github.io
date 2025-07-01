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

<img align="left" src="graphics/Fali Wang.jpg" alt="Fali Wang" style="width: 200px; margin-right: 50px;" />
<b>Fali Wang</b>, Ph.D. student, Informatics, Penn State University.
<br style="clear: both;" />

<img align="left" src="graphics/tofill.png" alt="Minhua Lin" style="width: 200px; margin-right: 50px;" />
<b>Minhua Lin</b>, Ph.D. student, Informatics, PSU. .
<br style="clear: both;" />

<img align="left" src="graphics/yaoma.jpg" alt="Yao Ma" style="width: 200px; margin-right: 50px;" />
<b>Yao Ma</b>, Assistant Professor, Department of Computer Science, Rensselaer Polytechnic Institute.
<br style="clear: both;" />

<img align="left" src="graphics/Wang-Suhang.jpg" alt="Suhang Wang" style="width: 200px; margin-right: 50px;" />
<b>Suhang Wang</b>, Associate Professor, College of IST, Penn State University.
<br style="clear: both;" />

<img align="left" src="graphics/huiliu.jpg" alt="Hui Liu" style="width: 200px; margin-right: 50px;" />
<b>Hui Liu</b>, Applied Scientist, Amazon.
<br style="clear: both;" />

<img align="left" src="graphics/qihe.jpg" alt="Qi He" style="width: 200px; margin-right: 50px;" />
<b>Qi He</b>
<br style="clear: both;" />

<img align="left" src="graphics/xianfengtang.jpg" alt="Xianfeng Tang" style="width: 200px; margin-right: 50px;" />
<b>Xianfeng Tang</b>, Applied Scientist, Amazon.
<br style="clear: both;" />

<img align="left" src="graphics/jiliang.jpg" alt="Jiliang Tang" style="width: 200px; margin-right: 50px;" />
<b>Jiliang Tang</b>, Professor, Michigan State University.
<br style="clear: both;" />

<img align="left" src="graphics/jianpei.jpg" alt="Jian Pei" style="width: 200px; margin-right: 50px;" />
<b>Jian Pei</b>, Professor, Duke University.
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


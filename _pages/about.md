---
permalink: /
title: "Fali Wang"
excerpt: "Fali Wang — Ph.D. candidate at Penn State working on efficient AI, test-time scaling, small language models, and graph learning."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<!-- =====================================================================
     HOME PAGE  (structure modelled on yaolinli.github.io, kept inside
     the AcademicPages theme so no other theme files need to change)

     Images this page expects (add them, or the figure column hides itself):
       /images/papers/graphskill.png      /images/papers/agentre.png
       /images/papers/graph4llm.png       /images/papers/agenttts.png
       /images/papers/slm-survey.png      /images/papers/slm-llm-collab.png
       /images/papers/graph-bench.png     /images/papers/infuserki.png
       /images/papers/hcgst.png           /images/papers/dcgst.png
       /images/logos/microsoft.png  /images/logos/amazon.png  /images/logos/nec.png
       /images/logos/psu.png        /images/logos/ucas.png    /images/logos/nefu.png
       /images/activities/kdd2025-tutorial.png   /images/activities/kdd2025-workshop.png
       /files/CV_FALIWANG.pdf
     Recommended figure size: ~600×360 px (16:9–16:10), PNG or JPG.
     ===================================================================== -->

<style>
/* ---- page-level ---- */
.page__title { display: none; }                 /* we render our own hero below */
html { scroll-behavior: smooth; }
@media (prefers-reduced-motion: reduce) { html { scroll-behavior: auto; } }
.fw h2 { margin-top: 2.4rem; padding-bottom: .3rem; border-bottom: 1px solid rgba(127,127,127,.25); scroll-margin-top: 1rem; }
.fw h3 { margin-top: 1.6rem; }
.fw .fw-muted { opacity: .72; }
.fw .fw-small { font-size: .9em; }

/* ---- anchor nav ---- */
.fw-nav { display: flex; flex-wrap: wrap; gap: .25rem 1.1rem; margin: 0 0 1.4rem; padding-bottom: .6rem; border-bottom: 1px solid rgba(127,127,127,.25); font-size: .92em; }
.fw-nav a { text-decoration: none; }

/* ---- hero ---- */
.fw-hero h1 { font-size: 1.9em; margin: 0 0 .7rem; line-height: 1.25; }
.fw-market { border-left: 3px solid #b3261e; background: rgba(179,38,30,.06); padding: .55rem .9rem; margin: 1.1rem 0; border-radius: 0 6px 6px 0; }
.fw-chips { display: flex; flex-wrap: wrap; gap: .5rem; margin: 1rem 0 .4rem; }
.fw-chips a { border: 1px solid rgba(127,127,127,.35); border-radius: 999px; padding: .15rem .75rem; font-size: .86em; text-decoration: none; }
.fw-chips a:hover { border-color: currentColor; }

/* ---- research interests ---- */
.fw-ri li { margin-bottom: .45rem; }

/* ---- news table ---- */
table.fw-news { width: 100%; border-collapse: collapse; font-size: .93em; margin: 0; }
.fw-news td { border: 0; border-bottom: 1px solid rgba(127,127,127,.18); padding: .45rem .45rem; vertical-align: top; }
.fw-news td:first-child { white-space: nowrap; font-weight: 600; opacity: .7; width: 5.6rem; }
details.fw-fold summary { cursor: pointer; font-weight: 600; margin: .8rem 0 .4rem; }

/* ---- publication cards ---- */
.fw-pub { display: flex; gap: 1.1rem; align-items: flex-start; padding: 1.1rem 0; border-bottom: 1px solid rgba(127,127,127,.18); scroll-margin-top: 1rem; }
.fw-pub-fig { flex: 0 0 190px; }
.fw-pub-fig img { width: 100%; height: auto; border-radius: 6px; border: 1px solid rgba(127,127,127,.25); display: block; }
.fw-pub-body { flex: 1; min-width: 0; }
.fw-pub-title { font-weight: 700; font-size: 1.02em; line-height: 1.35; margin: 0 0 .25rem; }
.fw-pub-title a { text-decoration: none; }
.fw-pub-authors { font-size: .9em; opacity: .85; margin: 0 0 .35rem; }
.fw-venue { display: inline-block; font-size: .78em; font-weight: 600; padding: .1rem .55rem; border-radius: 4px; background: rgba(44,74,122,.12); color: #2c4a7a; margin: 0 .3rem .35rem 0; }
.fw-venue.fw-venue-pre { background: rgba(127,127,127,.15); color: inherit; }
.fw-pub-desc { font-size: .9em; margin: .2rem 0 .55rem; }
.fw-btns a { display: inline-block; font-size: .82em; border: 1px solid rgba(127,127,127,.35); border-radius: 4px; padding: .05rem .5rem; margin: 0 .3rem .3rem 0; text-decoration: none; }
.fw-btns a:hover { border-color: currentColor; }
.fw-btns img { height: 18px; vertical-align: middle; }
@media (max-width: 640px) {
  .fw-pub { flex-direction: column; gap: .7rem; }
  .fw-pub-fig { flex-basis: auto; width: 100%; max-width: 320px; }
}
.fw-morepubs li { margin-bottom: .65rem; font-size: .9em; }
.fw-morepubs li .fw-pub-authors { margin: 0; }

/* ---- experience / education rows ---- */
.fw-row { display: flex; gap: 1rem; align-items: flex-start; padding: .9rem 0; border-bottom: 1px solid rgba(127,127,127,.18); }
.fw-row-logo { flex: 0 0 72px; }
.fw-row-logo img { width: 72px; height: 72px; object-fit: contain; border-radius: 8px; border: 1px solid rgba(127,127,127,.25); background: #fff; padding: 6px; display: block; }
.fw-row-body { flex: 1; min-width: 0; }
.fw-row-head { display: flex; justify-content: space-between; flex-wrap: wrap; gap: .2rem 1rem; }
.fw-row-head strong { font-size: 1.02em; }
.fw-row-date { white-space: nowrap; opacity: .7; font-size: .9em; }
.fw-row-body p { margin: .2rem 0; font-size: .92em; }
.fw-row-logo.fw-row-wide { flex-basis: 150px; }
.fw-row-logo.fw-row-wide img { width: 150px; height: auto; padding: 0; }

/* ---- honors ---- */
.fw-honors li { margin-bottom: .35rem; }
</style>

<div class="fw" markdown="0">

<nav class="fw-nav" aria-label="Sections">
  <a href="#news">News</a>
  <a href="#research">Research</a>
  <a href="#publications">Publications</a>
  <a href="#experience">Experience</a>
  <a href="#education">Education</a>
  <a href="#activities">Activities &amp; Service</a>
  <a href="#honors">Honors</a>
</nav>

<!-- ================================ HERO ================================ -->
<section class="fw-hero">
  <h1>👋 Hi, I am Fali Wang</h1>

  <p>I am a last-year Ph.D. candidate in the <a href="https://ist.psu.edu">College of Information Sciences and Technology</a> at <a href="https://www.psu.edu/">The Pennsylvania State University</a>, advised by Prof. <a href="https://suhangwang.ist.psu.edu/">Suhang Wang</a> in the Data Science and Machine Learning Lab. Before Penn State, I received my M.Eng. from the University of Chinese Academy of Sciences and my B.Eng. from Northeast Forestry University.</p>

  <p>I have interned at <strong>Microsoft</strong> (Redmond), <strong>Amazon</strong> (Palo Alto), and <strong>NEC Laboratories America</strong> (Princeton), working on test-time scaling, efficient AI, and knowledge-enhanced LLMs.</p>

  <div class="fw-market">
    <strong>I plan to enter the 2026–2027 academic job market and apply for faculty and postdoctoral positions.</strong>
    Please reach out to <code>fqw5095 [at] psu [dot] edu</code> for opportunities or research collaboration.
  </div>

  <div class="fw-chips">
    <a href="mailto:fqw5095@psu.edu">Email</a>
    <a href="/files/CV_FALIWANG.pdf">CV</a>
    <a href="https://scholar.google.com/citations?user=myQcu6cAAAAJ&amp;hl=en">Google Scholar</a>
    <a href="https://github.com/FairyFali">GitHub</a>
    <a href="https://twitter.com/FairyWFL">Twitter / X</a>
    <a href="https://orcid.org/0009-0000-8321-6365">ORCID</a>
  </div>
</section>

<!-- ============================ RESEARCH ============================ -->
<h2 id="research">Research Interests</h2>

<p>I build <strong>efficient AI systems that allocate models and compute according to what each task actually needs</strong>, and study how graphs and language models can enhance each other. My work spans four connected directions:</p>

<ul class="fw-ri">
  <li><strong>Efficient AI &amp; test-time scaling.</strong> Compute-optimal budget allocation at the task and query level, adaptive model routing, and agents that search scaling strategies for complex multi-stage tasks (<a href="#pub-agenttts">AgentTTS</a>, <a href="#pub-agentre">AgentRE</a>).</li>
  <li><strong>Small language models.</strong> SLMs as efficient foundations for next-generation AI: capability enhancement under limited compute, SLM–LLM collaboration, and cloud-edge deployment with privacy and trustworthiness (<a href="#pub-slm-survey">SLM Survey</a>, <a href="#pub-slm-llm">SLM–LLM Collaboration Survey</a>).</li>
  <li><strong>Agent-in-the-loop &amp; self-improving AI.</strong> Agents that iteratively optimize their own workflows — collaboration topology, model and role assignment, memory, and compute — by accumulating and reusing knowledge from prior trajectories and feedback.</li>
  <li><strong>Graph learning &amp; graphs for LLMs.</strong> Graph self-training under distribution shift, LLM graph reasoning and its benchmarking, knowledge-graph-enhanced LLMs, and graph-enhanced retrieval-augmented generation (<a href="#pub-graphskill">GraphSkill</a>, <a href="#pub-graph4llm">Graphs for LLMs</a>, <a href="#pub-infuserki">InfuserKI</a>).</li>
</ul>

<!-- ============================== NEWS ============================== -->
<h2 id="news">News</h2>

<table class="fw-news">
  <tr><td>09/2026</td><td><a href="#pub-agentre">AgentRE</a>, which generalizes test-time compute-optimal scaling as an optimizable graph, is accepted to <strong>NeurIPS 2026</strong>.</td></tr>
  <tr><td>05/2026</td><td>Started as an <strong>Applied Scientist Intern</strong> at Microsoft, Redmond.</td></tr>
  <tr><td>02/2026</td><td><a href="#pub-graph4llm">Graphs for LLMs</a>, our survey on graph-assisted large language models, is accepted to <strong>ACL 2026</strong> (Findings). [<a href="https://github.com/FairyFali/Graph4LLM-Survey">GitHub</a>]</td></tr>
  <tr><td>09/2025</td><td><a href="#pub-agenttts">AgentTTS</a>, an LLM agent for test-time compute-optimal budget allocation, is accepted to <strong>NeurIPS 2025</strong>.</td></tr>
  <tr><td>08/2025</td><td>Our <a href="#pub-slm-survey">Small Language Models survey</a> is accepted to <strong>ACM TIST</strong>.</td></tr>
  <tr><td>08/2025</td><td>Organized the <a href="https://fairyfali.github.io/kdd2025-tutorial/">KDD 2025 Tutorial on Small Language Models</a> and the <a href="https://kdd2025llm4ecommerce.github.io/">KDD 2025 Workshop on LLMs for E-Commerce</a>.</td></tr>
  <tr><td>04/2025</td><td>Invited talk on SLMs at the <a href="https://llm4ecommerce.github.io/schedule/">WWW 2025 LLM for E-Commerce Workshop</a>. [<a href="/files/SLMs_Survey_Slides__Copy_for_WWW_.pdf">Slides</a>]</td></tr>
  <tr><td>01/2025</td><td>Invited talk on SLMs at Amazon. [<a href="/files/SLMs_Survey_Slides.pdf">Slides</a>]</td></tr>
</table>

<details class="fw-fold">
  <summary>Earlier news</summary>
  <table class="fw-news">
    <tr><td>12/2024</td><td>Started as an <strong>Applied Scientist Intern</strong> at Amazon, Palo Alto.</td></tr>
    <tr><td>11/2024</td><td>Led and released the <a href="#pub-slm-survey">Small Language Models survey</a>. [<a href="https://arxiv.org/abs/2411.03350">arXiv</a>] [<a href="https://github.com/FairyFali/SLMs-Survey">GitHub</a>]</td></tr>
    <tr><td>11/2024</td><td>Passed the comprehensive exam.</td></tr>
    <tr><td>09/2023</td><td>Visiting research intern at NEC Laboratories America, Princeton.</td></tr>
    <tr><td>05/2023</td><td>Passed the qualifying exam and became a Ph.D. candidate.</td></tr>
    <tr><td>08/2022</td><td>Began my Ph.D. at Penn State University.</td></tr>
  </table>
</details>

<!-- ========================== PUBLICATIONS ========================== -->
<h2 id="publications">Selected Publications</h2>

<p class="fw-small fw-muted">First-author and co-first-author work, most recent first. <sup>*</sup> denotes equal contribution. Full list on <a href="https://scholar.google.com/citations?user=myQcu6cAAAAJ&amp;hl=en">Google Scholar</a>.</p>

<!-- NOTE: the one-line summaries below are paraphrased from titles/abstracts — please check and adjust the wording. -->

<div class="fw-pub" id="pub-agentre">
  <div class="fw-pub-fig"><a href="https://arxiv.org/abs/2511.00086"><img src="/images/papers/agentre.png" alt="AgentRE overview" onerror="this.closest('.fw-pub-fig').style.display='none'"></a></div>
  <div class="fw-pub-body">
    <p class="fw-pub-title"><a href="https://arxiv.org/abs/2511.00086">Generalizing Test-time Compute-optimal Scaling as an Optimizable Graph</a></p>
    <p class="fw-pub-authors"><strong>Fali Wang<sup>*</sup></strong>, Jihai Chen<sup>*</sup>, Shuhua Yang, Runxue Bao, Tianxiang Zhao, Zhiwei Zhang, Xianfeng Tang, Hui Liu, Qi He, Suhang Wang</p>
    <span class="fw-venue">NeurIPS 2026</span>
    <p class="fw-pub-desc">AgentRE recasts test-time compute-optimal scaling as search over an optimizable graph of models, roles, and budgets, letting an agent jointly decide <em>what</em> to run and <em>how much</em> compute to spend.</p>
    <div class="fw-btns"><a href="https://arxiv.org/abs/2511.00086">Paper</a><!-- <a href="https://github.com/FairyFali/AgentRE">Code</a> --></div>
  </div>
</div>

<div class="fw-pub" id="pub-graphskill">
  <div class="fw-pub-fig"><a href="https://arxiv.org/abs/2603.06620"><img src="/images/papers/graphskill.png" alt="GraphSkill overview" onerror="this.closest('.fw-pub-fig').style.display='none'"></a></div>
  <div class="fw-pub-body">
    <p class="fw-pub-title"><a href="https://arxiv.org/abs/2603.06620">GraphSkill: Documentation-Guided Hierarchical Retrieval-Augmented Coding for Complex Graph Reasoning</a></p>
    <p class="fw-pub-authors"><strong>Fali Wang<sup>*</sup></strong>, Chenglin Weng<sup>*</sup>, Xianren Zhang, Siyuan Hong, Hui Liu, Suhang Wang</p>
    <span class="fw-venue">KDD 2026</span>
    <p class="fw-pub-desc">Lets LLMs solve complex graph-reasoning problems by hierarchically retrieving graph-library documentation and writing executable code, instead of reasoning over graphs in text.</p>
    <div class="fw-btns"><a href="https://arxiv.org/abs/2603.06620">Paper</a><!-- <a href="#">Code</a> --></div>
  </div>
</div>

<div class="fw-pub" id="pub-graph4llm">
  <div class="fw-pub-fig"><a href="https://www.techrxiv.org/doi/full/10.36227/techrxiv.177162088.88045561"><img src="/images/papers/graph4llm.png" alt="Graphs for LLMs survey overview" onerror="this.closest('.fw-pub-fig').style.display='none'"></a></div>
  <div class="fw-pub-body">
    <p class="fw-pub-title"><a href="https://www.techrxiv.org/doi/full/10.36227/techrxiv.177162088.88045561">Graphs for LLMs: A Survey of Graph-Assisted Large Language Models</a></p>
    <p class="fw-pub-authors">Haitong Luo<sup>*</sup>, <strong>Fali Wang<sup>*</sup></strong>, Weiyao Zhang, Xianren Zhang, Zhiwei Zhang, Tianxiang Zhao, Minhua Lin, Jiahao Zhang, Hui Liu, Xianfeng Tang, Qi He, Suhang Wang, Xuying Meng, Yujun Zhang</p>
    <span class="fw-venue">ACL 2026 Findings</span>
    <p class="fw-pub-desc">A systematic survey of how graph structures assist LLMs — in retrieval, reasoning, planning, agents, and evaluation — with an open paper collection.</p>
    <div class="fw-btns">
      <a href="https://www.techrxiv.org/doi/full/10.36227/techrxiv.177162088.88045561">Paper</a>
      <a href="https://github.com/FairyFali/Graph4LLM-Survey">Paper List</a>
      <a href="https://github.com/FairyFali/Graph4LLM-Survey/stargazers"><img src="https://img.shields.io/github/stars/FairyFali/Graph4LLM-Survey?style=social&amp;logo=github&amp;label=Stars" alt="GitHub stars"></a>
    </div>
  </div>
</div>

<div class="fw-pub" id="pub-agenttts">
  <div class="fw-pub-fig"><a href="https://arxiv.org/abs/2508.00890"><img src="/images/papers/agenttts.png" alt="AgentTTS overview" onerror="this.closest('.fw-pub-fig').style.display='none'"></a></div>
  <div class="fw-pub-body">
    <p class="fw-pub-title"><a href="https://arxiv.org/abs/2508.00890">AgentTTS: Large Language Model Agent for Test-time Compute-optimal Scaling Strategy in Complex Tasks</a></p>
    <p class="fw-pub-authors"><strong>Fali Wang</strong>, Hui Liu, Zhenwei Dai, Jingying Zeng, Zhiwei Zhang, Zongyu Wu, Chen Luo, Zhen Li, Xianfeng Tang, Qi He, Suhang Wang</p>
    <span class="fw-venue">NeurIPS 2025</span>
    <p class="fw-pub-desc">An LLM agent that iteratively searches the compute-optimal test-time scaling strategy for multi-stage complex tasks — which model to use and how much compute to allocate to each subtask.</p>
    <div class="fw-btns"><a href="https://arxiv.org/abs/2508.00890">Paper</a><!-- <a href="#">Code</a> --></div>
  </div>
</div>

<div class="fw-pub" id="pub-slm-survey">
  <div class="fw-pub-fig"><a href="https://arxiv.org/abs/2411.03350"><img src="/images/papers/slm-survey.png" alt="Small Language Models survey overview" onerror="this.closest('.fw-pub-fig').style.display='none'"></a></div>
  <div class="fw-pub-body">
    <p class="fw-pub-title"><a href="https://dl.acm.org/doi/10.1145/3768165">A Comprehensive Survey of Small Language Models in the Era of Large Language Models: Techniques, Enhancements, Applications, Collaboration with LLMs, and Trustworthiness</a></p>
    <p class="fw-pub-authors"><strong>Fali Wang</strong>, Zhiwei Zhang, Xianren Zhang, Zongyu Wu, Tzuhao Mo, Qiuhao Lu, Wanjing Wang, Rui Li, Junjie Xu, Xianfeng Tang, Qi He, Yao Ma, Ming Huang, Suhang Wang</p>
    <span class="fw-venue">ACM TIST 2025</span><span class="fw-venue">KDD 2025 Tutorial</span>
    <p class="fw-pub-desc">The first comprehensive survey of SLMs: architectures, training and enhancement techniques, applications, SLM–LLM collaboration, and trustworthiness. Presented as a lecture-style tutorial at KDD 2025 and in invited talks at Amazon and WWW 2025.</p>
    <div class="fw-btns">
      <a href="https://arxiv.org/abs/2411.03350">arXiv</a>
      <a href="https://dl.acm.org/doi/10.1145/3768165">TIST</a>
      <a href="https://dl.acm.org/doi/abs/10.1145/3711896.3736563">KDD Tutorial Paper</a>
      <a href="https://fairyfali.github.io/kdd2025-tutorial/">Tutorial Site</a>
      <a href="/files/SLMs_Survey_Slides.pdf">Slides</a>
      <a href="https://github.com/FairyFali/SLMs-Survey">Paper List</a>
      <a href="https://github.com/FairyFali/SLMs-Survey/stargazers"><img src="https://img.shields.io/github/stars/FairyFali/SLMs-Survey?style=social&amp;logo=github&amp;label=Stars" alt="GitHub stars"></a>
    </div>
  </div>
</div>

<div class="fw-pub" id="pub-slm-llm">
  <div class="fw-pub-fig"><a href="https://arxiv.org/abs/2510.13890"><img src="/images/papers/slm-llm-collab.png" alt="SLM–LLM collaboration survey overview" onerror="this.closest('.fw-pub-fig').style.display='none'"></a></div>
  <div class="fw-pub-body">
    <p class="fw-pub-title"><a href="https://arxiv.org/abs/2510.13890">A Survey on Collaborating Small and Large Language Models for Performance, Cost-Effectiveness, Cloud-Edge Privacy, and Trustworthiness</a></p>
    <p class="fw-pub-authors"><strong>Fali Wang</strong>, Jihai Chen, Shuhua Yang, Ali Al-Lawati, Linli Tang, Hui Liu, Suhang Wang</p>
    <span class="fw-venue fw-venue-pre">Preprint 2025</span>
    <p class="fw-pub-desc">Organizes SLM–LLM collaboration patterns by the goals they serve — performance, cost, cloud-edge privacy, and trustworthiness — and maps open problems.</p>
    <div class="fw-btns"><a href="https://arxiv.org/abs/2510.13890">arXiv</a></div>
  </div>
</div>

<div class="fw-pub" id="pub-graph-bench">
  <div class="fw-pub-fig"><a href="https://arxiv.org/abs/2608.12391"><img src="/images/papers/graph-bench.png" alt="Graph reasoning benchmark overview" onerror="this.closest('.fw-pub-fig').style.display='none'"></a></div>
  <div class="fw-pub-body">
    <p class="fw-pub-title"><a href="https://arxiv.org/abs/2608.12391">Unified Multi-Dimensional Benchmark for Complex Graph Reasoning in Large Language Models</a></p>
    <p class="fw-pub-authors"><strong>Fali Wang</strong>, Ali Al-Lawati, Iliyas Bektas, Jinxuan Fang, Alek Melenski, Tianxiang Zhao, Yao Ma, Suhang Wang</p>
    <span class="fw-venue fw-venue-pre">Preprint 2026</span>
    <p class="fw-pub-desc">A unified benchmark that evaluates LLM graph reasoning along multiple dimensions of complexity, revealing where current models break down.</p>
    <div class="fw-btns"><a href="https://arxiv.org/abs/2608.12391">arXiv</a><!-- <a href="#">Code &amp; Data</a> --></div>
  </div>
</div>

<div class="fw-pub" id="pub-infuserki">
  <div class="fw-pub-fig"><a href="https://aclanthology.org/2024.findings-emnlp.209.pdf"><img src="/images/papers/infuserki.png" alt="InfuserKI overview" onerror="this.closest('.fw-pub-fig').style.display='none'"></a></div>
  <div class="fw-pub-body">
    <p class="fw-pub-title"><a href="https://aclanthology.org/2024.findings-emnlp.209.pdf">InfuserKI: Enhancing Large Language Models with Knowledge Graphs via Infuser-Guided Knowledge Integration</a></p>
    <p class="fw-pub-authors"><strong>Fali Wang</strong>, Runxue Bao, Suhang Wang, Wenchao Yu, Yanchi Liu, Wei Cheng, Haifeng Chen</p>
    <span class="fw-venue">EMNLP 2024 Findings</span>
    <p class="fw-pub-desc">Integrates new knowledge-graph facts into an LLM through an infuser that selectively injects only what the model does not already know, reducing hallucination without forgetting.</p>
    <div class="fw-btns"><a href="https://aclanthology.org/2024.findings-emnlp.209.pdf">Paper</a></div>
  </div>
</div>

<div class="fw-pub" id="pub-hcgst">
  <div class="fw-pub-fig"><a href="https://arxiv.org/pdf/2407.17787"><img src="/images/papers/hcgst.png" alt="HC-GST overview" onerror="this.closest('.fw-pub-fig').style.display='none'"></a></div>
  <div class="fw-pub-body">
    <p class="fw-pub-title"><a href="https://arxiv.org/pdf/2407.17787">HC-GST: Heterophily-aware Distribution Consistency-based Graph Self-training</a></p>
    <p class="fw-pub-authors"><strong>Fali Wang</strong>, Tianxiang Zhao, Junjie Xu, Suhang Wang</p>
    <span class="fw-venue">CIKM 2024</span>
    <p class="fw-pub-desc">Graph self-training that selects pseudo-labels to keep the homophily distribution of the training set consistent with the full graph, so heterophilic nodes are no longer under-represented.</p>
    <div class="fw-btns"><a href="https://arxiv.org/pdf/2407.17787">Paper</a></div>
  </div>
</div>

<div class="fw-pub" id="pub-dcgst">
  <div class="fw-pub-fig"><a href="https://arxiv.org/pdf/2401.10394"><img src="/images/papers/dcgst.png" alt="DC-GST overview" onerror="this.closest('.fw-pub-fig').style.display='none'"></a></div>
  <div class="fw-pub-body">
    <p class="fw-pub-title"><a href="https://arxiv.org/pdf/2401.10394">Distribution Consistency-based Self-Training for Graph Neural Networks with Sparse Labels</a></p>
    <p class="fw-pub-authors"><strong>Fali Wang</strong>, Tianxiang Zhao, Suhang Wang</p>
    <span class="fw-venue">WSDM 2024</span>
    <p class="fw-pub-desc">Chooses pseudo-labeled nodes that shrink the distribution gap between labeled and unlabeled nodes, making GNN self-training reliable when labels are scarce.</p>
    <div class="fw-btns"><a href="https://arxiv.org/pdf/2401.10394">Paper</a></div>
  </div>
</div>

<details class="fw-fold">
  <summary>More publications &amp; collaborations</summary>
  <ul class="fw-morepubs">
    <li><strong>Retrieved But Not Reliable: A Survey on Attacks, and Defenses in Retrieval-Augmented Generation.</strong><br>
      <span class="fw-pub-authors">Minh Tran, Cuong Dang, Tuc Nguyen, Khanh-Tung Tran, Minh Huynh Nguyen, Trinh Chau, Kien Le, Do Xuan Long, Jiahao Zhang, <strong>Fali Wang</strong>, Hoang D. Nguyen, Thanh Le, Suhang Wang.</span> <span class="fw-venue">EMNLP 2026</span></li>
    <li><strong>Adversarial Reinforcement Learning for Robust Diffusion Large Language Model Unlearning.</strong><br>
      <span class="fw-pub-authors">Zhiwei Zhang, Yudi Lin, Linlin Wu, <strong>Fali Wang</strong>, Yi Xin, Xiaomin Li, Minhua Lin, Xianfeng Tang, Qi He, Suhang Wang.</span> <span class="fw-venue">ICML 2026</span></li>
    <li><strong>Unlocking the Power of Multi-Agent LLM for Reasoning: From Lazy Agents to Deliberation.</strong><br>
      <span class="fw-pub-authors">Zhiwei Zhang, Xiaomin Li, Yudi Lin, Hui Liu, Ramraj Chandradevan, Linlin Wu, Minhua Lin, <strong>Fali Wang</strong>, Xianfeng Tang, Qi He, Suhang Wang.</span> <span class="fw-venue">ICLR 2026</span></li>
    <li><strong>Bradley-Terry and Multi-Objective Reward Modeling Are Complementary.</strong><br>
      <span class="fw-pub-authors">Zhiwei Zhang, Hui Liu, Xiaomin Li, Zhenwei Dai, Jingying Zeng, <strong>Fali Wang</strong>, Minhua Lin, Ramraj Chandradevan, Linlin Wu, Zhen Li, Chen Luo, Zongyu Wu, Xianfeng Tang, Qi He, Suhang Wang.</span> <span class="fw-venue">ICLR 2026</span></li>
    <li><strong>How Far Are LLMs from Professional Poker Players? Revisiting Game-Theoretic Reasoning with Agentic Tool Use.</strong><br>
      <span class="fw-pub-authors">Minhua Lin, Enyan Dai, Hui Liu, Xianfeng Tang, Yuliang Yan, Zhenwei Dai, Jingying Zeng, Zhiwei Zhang, <strong>Fali Wang</strong>, Hongcheng Gao, Chen Luo, Xiang Zhang, Qi He, Suhang Wang.</span> <span class="fw-venue">ICLR 2026</span></li>
    <li><strong>Image Corruption-Inspired Membership Inference Attacks against Large Vision-Language Models.</strong><br>
      <span class="fw-pub-authors">Zongyu Wu, Minhua Lin, Zhiwei Zhang, <strong>Fali Wang</strong>, Xianren Zhang, Xiang Zhang, Suhang Wang.</span> <span class="fw-venue">EACL 2026</span></li>
    <li><strong>BioMol-MQA: A Multi-Modal Question Answering Dataset for LLM Reasoning over Bio-Molecular Interactions.</strong><br>
      <span class="fw-pub-authors">Saptarshi Sengupta, Shuhua Yang, Paul Kwong Yu, <strong>Fali Wang</strong>, Suhang Wang.</span> <span class="fw-venue">ICDM 2026</span></li>
    <li><strong>Diagnosing and Addressing Pitfalls in KG-RAG Datasets: Toward More Reliable Benchmarking.</strong><br>
      <span class="fw-pub-authors">Liangliang Zhang, Zhuorui Jiang, Hongliang Chi, Haoyang Chen, Mohammed Elkoumy, <strong>Fali Wang</strong>, Qiong Wu, Zhengyi Zhou, Shirui Pan, Suhang Wang, Yao Ma.</span> <span class="fw-venue">NeurIPS 2025</span></li>
    <li><strong>SFT or RL? An Early Investigation into Training R1-Like Reasoning Large Vision-Language Models.</strong><br>
      <span class="fw-pub-authors">Hardy Chen, Haoqin Tu, <strong>Fali Wang</strong>, Hui Liu, Xianfeng Tang, Xinya Du, Yuyin Zhou, Cihang Xie.</span> <span class="fw-venue">TMLR 2025</span></li>
    <li><strong>Catastrophic Failure of LLM Unlearning via Quantization.</strong><br>
      <span class="fw-pub-authors">Zhiwei Zhang, <strong>Fali Wang</strong>, Xiaomin Li, Zongyu Wu, Xianfeng Tang, Hui Liu, Qi He, Wenpeng Yin, Suhang Wang.</span> <span class="fw-venue">ICLR 2025</span></li>
    <li><strong>Enhance Graph Alignment for Large Language Models.</strong><br>
      <span class="fw-pub-authors">Haitong Luo, Xuying Meng, Suhang Wang, Tianxiang Zhao, <strong>Fali Wang</strong>, Yujun Zhang.</span> <span class="fw-venue">Neural Networks</span></li>
    <li><strong>Maximum Entropy Loss, the Silver Bullet Targeting Backdoor Attacks in Pre-trained Language Models.</strong><br>
      <span class="fw-pub-authors">Zhengxiao Liu, Bowen Shen, Zheng Lin, <strong>Fali Wang</strong>, Weiping Wang.</span> <span class="fw-venue">ACL 2023 Findings</span></li>
    <li><strong>Dynamic Graphs and Large Language Models: A Survey of Mutual Enhancement.</strong><br>
      <span class="fw-pub-authors">Iliyas Bektas, <strong>Fali Wang</strong>, Jiahao Zhang, Suhang Wang.</span> <span class="fw-venue fw-venue-pre">Preprint 2026</span></li>
    <li><strong>Can LoRA Fusion Support Cross-Domain Tasks in Cloud-Edge Collaboration?</strong><br>
      <span class="fw-pub-authors">Yatong Wang, <strong>Fali Wang</strong>, Naibin Gu, Zheng Lin, Zhengxiao Liu, Dingyu Yao, Zhiwei Zhang, Jianxin Shi, Weiping Wang.</span> <span class="fw-venue fw-venue-pre">Preprint 2026</span></li>
    <li><strong>MacroBERT: Maximizing Certified Region of BERT to Adversarial Word Substitutions.</strong><br>
      <span class="fw-pub-authors"><strong>Fali Wang</strong>, Zheng Lin, Zhengxiao Liu, Mingyu Zheng, Lei Wang, Daren Zha.</span> <span class="fw-venue">DASFAA 2021</span></li>
    <li><strong>ConvMB: Improving Convolution-Based Knowledge Graph Embeddings by Adopting Multi-Branch 3D Convolution Filters.</strong><br>
      <span class="fw-pub-authors">Xiaobo Guo, <strong>Fali Wang</strong> (corresponding), Neng Gao, Zeyi Liu, Kai Liu.</span> <span class="fw-venue">ISPA 2021</span></li>
    <li><strong>BEFSR: A Multiple Attention-Based Model Considering Bidirectional Entity Information Flows and Few-shot Relations.</strong><br>
      <span class="fw-pub-authors">Xiaobo Guo, Neng Gao, <strong>Fali Wang</strong> (corresponding).</span> <span class="fw-venue">ICPR 2022</span></li>
    <li><strong>De-Co: A Two-Step Spelling Correction Model for Combating Adversarial Typos.</strong><br>
      <span class="fw-pub-authors">Zhengxiao Liu, <strong>Fali Wang</strong> (corresponding), Zheng Lin, Lei Wang, Zhiyi Yin.</span> <span class="fw-venue">ISPA 2020</span></li>
    <li><strong>NarGNN: Narrative Graph Neural Networks for New Script Event Prediction Problem.</strong><br>
      <span class="fw-pub-authors">Shuang Yang, <strong>Fali Wang</strong> (corresponding), Cong Xue, Daren Zha.</span> <span class="fw-venue">ISPA 2020</span></li>
    <li><strong>Research and Simulation on Processing Speed Connection of Multi-axis Woodworking Engraving Machine.</strong><br>
      <span class="fw-pub-authors"><strong>Fali Wang</strong>, Jilong Bian, Fengming Zhang, Lin Ge, Hui Ma, Guangjun Chen.</span> <span class="fw-venue">Journal of Northeast Forestry University 2018</span></li>
  </ul>
</details>

<!-- =========================== EXPERIENCE =========================== -->
<h2 id="experience">Industry Experience</h2>

<div class="fw-row">
  <div class="fw-row-logo"><img src="/images/logos/microsoft.png" alt="Microsoft" onerror="this.closest('.fw-row-logo').style.display='none'"></div>
  <div class="fw-row-body">
    <div class="fw-row-head"><strong>Microsoft</strong><span class="fw-row-date">05/2026 – 08/2026</span></div>
    <p>Applied Scientist Intern · Redmond, WA · Mentors: Dr. Zhenwei Dai, Joy Zeng, and Dr. Qi He</p>
    <p class="fw-muted">Query-level compute-optimal budget allocation for efficient LLM test-time scaling.</p>
  </div>
</div>

<div class="fw-row">
  <div class="fw-row-logo"><img src="/images/logos/amazon.png" alt="Amazon" onerror="this.closest('.fw-row-logo').style.display='none'"></div>
  <div class="fw-row-body">
    <div class="fw-row-head"><strong>Amazon</strong><span class="fw-row-date">12/2024 – 10/2025</span></div>
    <p>Applied Scientist Intern · Palo Alto, CA · Mentors: Dr. Hui Liu and Dr. Xianfeng Tang</p>
    <p class="fw-muted">Task-level compute-optimal budget allocation for test-time scaling → <a href="#pub-agenttts">AgentTTS</a> (NeurIPS 2025) and <a href="#pub-agentre">AgentRE</a> (NeurIPS 2026).</p>
  </div>
</div>

<div class="fw-row">
  <div class="fw-row-logo"><img src="/images/logos/nec.png" alt="NEC Laboratories America" onerror="this.closest('.fw-row-logo').style.display='none'"></div>
  <div class="fw-row-body">
    <div class="fw-row-head"><strong>NEC Laboratories America</strong><span class="fw-row-date">09/2023 – 12/2023</span></div>
    <p>Research Intern · Princeton, NJ · Mentors: Dr. Runxue Bao and Dr. Haifeng Chen</p>
    <p class="fw-muted">Knowledge infusion to mitigate hallucination in LLMs → <a href="#pub-infuserki">InfuserKI</a> (EMNLP 2024).</p>
  </div>
</div>

<!-- =========================== EDUCATION ============================ -->
<h2 id="education">Education</h2>

<div class="fw-row">
  <div class="fw-row-logo"><img src="/images/logos/psu.png" alt="Penn State University" onerror="this.closest('.fw-row-logo').style.display='none'"></div>
  <div class="fw-row-body">
    <div class="fw-row-head"><strong>The Pennsylvania State University</strong><span class="fw-row-date">08/2022 – present</span></div>
    <p>Ph.D. in Informatics, College of Information Sciences and Technology · Advisor: <a href="https://suhangwang.ist.psu.edu/">Prof. Suhang Wang</a></p>
  </div>
</div>

<div class="fw-row">
  <div class="fw-row-logo"><img src="/images/logos/ucas.png" alt="University of Chinese Academy of Sciences" onerror="this.closest('.fw-row-logo').style.display='none'"></div>
  <div class="fw-row-body">
    <div class="fw-row-head"><strong>University of Chinese Academy of Sciences</strong><span class="fw-row-date">09/2018 – 06/2021</span></div>
    <p>M.Eng. in Software Engineering, School of Cyber Security</p>
  </div>
</div>

<div class="fw-row">
  <div class="fw-row-logo"><img src="/images/logos/nefu.png" alt="Northeast Forestry University" onerror="this.closest('.fw-row-logo').style.display='none'"></div>
  <div class="fw-row-body">
    <div class="fw-row-head"><strong>Northeast Forestry University</strong><span class="fw-row-date">09/2014 – 07/2018</span></div>
    <p>B.Eng. in Software Engineering · Ranked 1st in the cohort</p>
  </div>
</div>

<!-- ====================== ACTIVITIES & SERVICE ====================== -->
<h2 id="activities">Academic Activities &amp; Service</h2>

<h3>Organizer</h3>

<div class="fw-row">
  <div class="fw-row-logo fw-row-wide"><img src="/images/activities/kdd2025-tutorial.png" alt="KDD 2025 SLM tutorial" onerror="this.closest('.fw-row-logo').style.display='none'"></div>
  <div class="fw-row-body">
    <div class="fw-row-head"><strong><a href="https://fairyfali.github.io/kdd2025-tutorial/">KDD 2025 Tutorial</a></strong><span class="fw-row-date">08/2025</span></div>
    <p><em>A Tutorial on Small Language Models in the Era of Large Language Models: Architecture, Capabilities, and Trustworthiness</em></p>
    <div class="fw-btns"><a href="https://fairyfali.github.io/kdd2025-tutorial/">Tutorial Site</a><a href="https://dl.acm.org/doi/abs/10.1145/3711896.3736563">Paper</a><a href="/files/SLMs_Survey_Slides.pdf">Slides</a></div>
  </div>
</div>

<div class="fw-row">
  <div class="fw-row-logo fw-row-wide"><img src="/images/activities/kdd2025-workshop.png" alt="KDD 2025 LLM4ECommerce workshop" onerror="this.closest('.fw-row-logo').style.display='none'"></div>
  <div class="fw-row-body">
    <div class="fw-row-head"><strong><a href="https://kdd2025llm4ecommerce.github.io/">KDD 2025 Workshop</a></strong><span class="fw-row-date">08/2025</span></div>
    <p><em>The 2nd Workshop on Large Language Models for E-Commerce</em></p>
    <div class="fw-btns"><a href="https://kdd2025llm4ecommerce.github.io/">Workshop Site</a></div>
  </div>
</div>

<h3>Invited Talks</h3>
<ul class="fw-small">
  <li><strong>Small Language Models in the Era of LLMs</strong> · <a href="https://llm4ecommerce.github.io/schedule/">WWW 2025 Workshop on LLMs for E-Commerce</a> · 04/2025 [<a href="/files/SLMs_Survey_Slides__Copy_for_WWW_.pdf">Slides</a>]</li>
  <li><strong>Small Language Models in the Era of LLMs</strong> · Amazon · 01/2025 [<a href="/files/SLMs_Survey_Slides.pdf">Slides</a>]</li>
</ul>

<h3>Service</h3>
<ul class="fw-small">
  <li><strong>Web Chair</strong> · KDD 2027</li>
  <li><strong>Guest Editor</strong> · ACM Transactions on Intelligent Systems and Technology (TIST)</li>
  <li><strong>Program Committee</strong> · ICMR 2026, IEEE BigData 2026, ACM MM 2026</li>
  <li><strong>Reviewer</strong> · ICLR, ICML, NeurIPS, KDD, ACL, EMNLP, WWW, CIKM, IJCAI, SDM, RecSys, ACM MM, IEEE BigData; ACM TIST, ACM Computing Surveys</li>
  <li><strong>Volunteer</strong> · NeurIPS 2025</li>
</ul>

<h3>Teaching</h3>
<ul class="fw-small">
  <li>Teaching Assistant · <strong>DS 305: Algorithmics</strong> · Penn State · Spring &amp; Fall 2026</li>
  <li>Teaching Assistant · <strong>DS 420: Network Analytics</strong> · Penn State · Fall 2024</li>
</ul>

<!-- ============================= HONORS ============================= -->
<h2 id="honors">Honors &amp; Awards</h2>
<ul class="fw-honors fw-small">
  <li>Travel Award, PSU College of IST · CIKM 2024 &amp; EMNLP 2024</li>
  <li>National Scholarship, Ministry of Education of China · 2015 &amp; 2016</li>
  <li>Honorable Mention, COMAP Interdisciplinary Contest in Modeling · 2018</li>
  <li>First Prize (Provincial) &amp; Third Prize (National), Lan Qiao International Programming Contest · 2017</li>
  <li>Top 10 Media Person, China College Students Online Campus Netcom, Ministry of Education · 2017</li>
  <li>Second Prize, CSIAM National Undergraduate Mathematical Contest in Modeling · 2016</li>
</ul>

<!-- ====================== OPTIONAL: VISITOR MAP ======================
     Register at https://mapmyvisitors.com (or https://clustrmaps.com),
     then paste the snippet it gives you here, e.g.:

<p class="fw-small fw-muted" style="margin-top:2.5rem;">Visitor map</p>
<a href="https://mapmyvisitors.com/web/YOUR_ID" title="Visit tracker">
  <img src="https://mapmyvisitors.com/map.png?d=YOUR_KEY&cl=ffffff" alt="Visitor map" style="max-width:100%;">
</a>
     =================================================================== -->

</div>

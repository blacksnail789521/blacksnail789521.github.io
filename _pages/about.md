---
permalink: /
title: "Ching (Jason) Chang | Staff ML Research Scientist @ Pravāh"
excerpt: "Personal website of Ching (Jason) Chang, Staff ML Research Scientist at Pravāh and PhD from NYCU. AI Research Scientist – Time Series • Foundation Models • Multimodal • Agentic RL • Reasoning"
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

Hello 👋, my name is Ching Chang, also known as Jason Chang. I am currently a Staff ML Research Scientist at [Pravāh](https://pravah.com/). I received my PhD in Computer Science from National Yang Ming Chiao Tung University (NYCU), Taiwan, advised by [Prof. Wen-Chih Peng](https://sites.google.com/site/wcpeng/). Previously, I was a Visiting Graduate Researcher in Computer Science at UCLA, working with [Prof. Wei Wang](http://web.cs.ucla.edu/~weiwang/).  

My research focuses on Time Series Analysis, Foundation Models, Multimodal Learning, Agentic Reinforcement Learning, and Reasoning. I have published multiple papers in top AI and data science conferences and journals, including NeurIPS, AAAI, ICDE, CIKM, and ACM TIST, with total
<a href='https://scholar.google.com/citations?user=OXCVj48AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=google citations"></a>.

**Work Authorization:** EB-1A I-140 Approved • EAD expected 2026.11 (no visa sponsorship required)

<p style="margin-top: 0.8em;">
  <a class="resume-btn" href="/resume/Ching%20Chang_Resume.pdf" target="_blank" rel="noopener">📄&nbsp; Download Resume (PDF)</a>
</p>


# 📖 Education

- *2021.09 – 2026.03*, **National Yang Ming Chiao Tung University (NYCU), Taiwan**, PhD in Computer Science  
- *2025.02 – 2026.02*, **University of California, Los Angeles (UCLA), USA**, Visiting Graduate Researcher in Computer Science  
- *2016.09 – 2018.09*, **National Chiao Tung University (NCTU), Taiwan**, MSc in Computer Science and Engineering  
- *2012.09 – 2016.06*, **National Chiao Tung University (NCTU), Taiwan**, BSc in Electrical and Computer Engineering

# 💻 Work Experience

- *2026.03 – Now*, **Staff ML Research Scientist**, Pravah, San Francisco, CA, USA  

- *2025.09 – 2026.02*, **Research Consultant**, TSMC, Hsinchu, Taiwan  

- *2022.09 – 2025.02*, **Research Scientist (Intern)**, TSMC, Hsinchu, Taiwan  

- *2021.01 – 2025.01*, **Research Scientist (Intern)**, GoEdge.ai, Hsinchu, Taiwan  

- *2019.07 – 2020.12*, **Machine Learning Engineer**, TSMC, Hsinchu, Taiwan  

- *2018.04 – 2018.09*, **Machine Learning Engineer (Intern)**, EPISTAR, Hsinchu, Taiwan

# 📝 Publications

<style>
.pub {
  border: 1px solid rgba(128, 128, 128, 0.3);
  border-radius: 8px;
  padding: 0.5em 2.2em 0.5em 0.8em; /* right gutter hosts the chevron */
  margin: 0.45em 0;
  line-height: 1.45;
  transition: border-color 0.15s ease;
}
.pub:hover {
  border-color: rgba(52, 120, 183, 0.55);
}
details.pub summary {
  cursor: pointer;
  position: relative;
  list-style: none; /* default triangle replaced by the chevron below */
}
details.pub summary::-webkit-details-marker {
  display: none;
}
details.pub summary::after { /* right-aligned chevron, rotates when open */
  content: "";
  position: absolute;
  right: -1.5em;
  top: 0.45em;
  width: 0.45em;
  height: 0.45em;
  border-right: 2px solid rgba(128, 128, 128, 0.7);
  border-bottom: 2px solid rgba(128, 128, 128, 0.7);
  transform: rotate(45deg);
  transition: transform 0.2s ease;
}
details.pub[open] summary::after {
  transform: rotate(225deg);
  top: 0.6em;
}
details.pub summary:focus-visible {
  outline: 2px solid rgba(52, 120, 183, 0.6);
  outline-offset: 2px;
  border-radius: 4px;
}
details.pub summary > a {
  font-weight: 600;
  text-decoration: none;
}
details.pub summary > a:hover {
  text-decoration: underline;
}
.pub-authors {
  display: block;
  margin-top: 0.15em;
  font-size: 0.85em;
  opacity: 0.75;
}
details.pub:not([open]) .pub-authors { /* one line until expanded */
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
}
.pub-links {
  display: block;
  margin-top: 0.3em;
}
.pub-links img {
  vertical-align: middle;
  height: 20px;
}
a.pub-link-btn {
  display: inline-block;
  padding: 0.05em 0.6em;
  border-radius: 999px;
  border: 1px solid rgba(128, 128, 128, 0.4);
  background: rgba(128, 128, 128, 0.12);
  color: inherit !important;
  font-size: 0.78em;
  font-weight: 600;
  text-decoration: none !important;
  vertical-align: middle;
  transition: background 0.15s ease, border-color 0.15s ease;
}
a.pub-link-btn:hover {
  background: rgba(52, 120, 183, 0.15);
  border-color: rgba(52, 120, 183, 0.6);
}
.pub-badge {
  display: inline-block;
  font-size: 0.72em;
  font-weight: 700;
  letter-spacing: 0.02em;
  padding: 0.12em 0.6em;
  border-radius: 999px;
  background: rgba(52, 120, 183, 0.13);
  border: 1px solid rgba(52, 120, 183, 0.3);
  color: inherit;
  margin-right: 0.3em;
  vertical-align: 0.14em;
  white-space: nowrap;
}
.pub-body {
  margin-top: 0.55em;
}
details.pub[open] .pub-body {
  animation: pubfade 0.18s ease-out;
}
@keyframes pubfade {
  from { opacity: 0; transform: translateY(-2px); }
  to   { opacity: 1; transform: none; }
}
.pub-body p {
  margin: 0 0 0.3em;
}
.pub-desc {
  font-size: 0.9em;
  opacity: 0.85;
}
.pub-fig {
  background-color: white; /* force white behind image (figures are drawn for white) */
  border: 1px solid rgba(128, 128, 128, 0.25);
  border-radius: 6px;
  overflow: hidden;
  margin: 0.55em 0;
}
.pub-fig img {
  background-color: white; /* if PNG has transparency */
  display: block;
  width: 100%;
  height: auto;
}
.pub-hint {
  font-size: 0.85em;
  opacity: 0.6;
  margin-bottom: 0.4em;
}
.pub-sort {
  margin: 0 0 0.5em;
  font-size: 0.85em;
}
.pub-sort-label {
  opacity: 0.6;
  margin-right: 0.2em;
}
.pub-sort-btn {
  display: inline-block;
  padding: 0.15em 0.75em;
  margin-right: 0.25em;
  border-radius: 999px;
  border: 1px solid rgba(128, 128, 128, 0.4);
  background: transparent;
  color: inherit;
  font: inherit;
  font-size: 1em;
  cursor: pointer;
  transition: background 0.15s ease, border-color 0.15s ease;
}
.pub-sort-btn:hover {
  border-color: rgba(52, 120, 183, 0.6);
}
.pub-sort-btn.active {
  background: rgba(52, 120, 183, 0.15);
  border-color: rgba(52, 120, 183, 0.5);
  font-weight: 600;
}
a.resume-btn {
  display: inline-block;
  padding: 0.3em 0.9em;
  border-radius: 999px;
  border: 1px solid rgba(52, 120, 183, 0.5);
  background: rgba(52, 120, 183, 0.13);
  color: inherit !important;
  font-weight: 600;
  font-size: 0.9em;
  text-decoration: none !important;
  transition: background 0.15s ease, border-color 0.15s ease;
}
a.resume-btn:hover {
  background: rgba(52, 120, 183, 0.25);
  border-color: rgba(52, 120, 183, 0.7);
}
</style>

<p class="pub-hint"><i>Click a paper to expand its figure and abstract.</i></p>

<p class="pub-sort"><span class="pub-sort-label">Sort:</span>
  <button type="button" class="pub-sort-btn active" data-sort="featured">Featured</button>
  <button type="button" class="pub-sort-btn" data-sort="year">Newest</button>
  <button type="button" class="pub-sort-btn" data-sort="citations">Most cited</button>
</p>

<div id="pub-list">

<details class="pub" data-scholar-id="qxL8FJ1GzNcC">
  <summary><span class="pub-badge">NeurIPS 2025</span> <a href="https://arxiv.org/abs/2506.10412">Time-IMM: A Dataset and Benchmark for Irregular Multimodal Multivariate Time Series</a>
    <span class="pub-authors"><b>Ching Chang</b>, Jeehyun Hwang, Yidan Shi, Haixin Wang, Wen-Chih Peng, Tien-Fu Chen, Wei Wang</span>
    <span class="pub-links">{% include scholar_citation_button.html user="OXCVj48AAAAJ" paper="qxL8FJ1GzNcC" %} <a href="https://github.com/blacksnail789521/Time-IMM"><img src="https://img.shields.io/github/stars/blacksnail789521/Time-IMM?style=social&amp;label=Code+Stars" alt="Code Stars"></a> <a href="https://github.com/blacksnail789521/IMM-TSF"><img src="https://img.shields.io/github/stars/blacksnail789521/IMM-TSF?style=social&amp;label=Dataset+Stars" alt="Dataset Stars"></a> <a class="pub-link-btn" href="https://blacksnail789521.github.io/time-imm-project-page/">Project Page</a> <a class="pub-link-btn" href="https://recorder-v3.slideslive.com/?share=103254&amp;s=e5709e82-503d-4a79-88b1-271b89b1f69f">Video</a> <a class="pub-link-btn" href="https://docs.google.com/presentation/d/199W1ktlDa3lwBfGAhLSSGoD7LDLzlgO5/edit?usp=sharing">Slides</a></span>
  </summary>
  <div class="pub-body">
    <div class="pub-fig"><img src="images/papers/timeimm.png" alt="Time-IMM" width="1593" height="794" loading="lazy"></div>
    <p class="pub-desc">Time-IMM is a comprehensive benchmark and open-source library designed for irregular, multimodal time series. It introduces nine real-world datasets across diverse domains and provides tools for fusing asynchronous text with numeric signals, showing that multimodal integration can significantly enhance forecasting in complex, real-world settings.</p>
  </div>
</details>

<details class="pub" data-scholar-id="Zph67rFs4hoC">
  <summary><span class="pub-badge">ACM TIST 2025</span> <a href="https://dl.acm.org/doi/10.1145/3719207">LLM4TS: Aligning Pre-Trained LLMs as Data-Efficient Time-Series Forecasters</a>
    <span class="pub-authors"><b>Ching Chang</b>, Wei-Yao Wang, Wen-Chih Peng, Tien-Fu Chen</span>
    <span class="pub-links">{% include scholar_citation_button.html user="OXCVj48AAAAJ" paper="Zph67rFs4hoC" %} <a href="https://github.com/blacksnail789521/LLM4TS"><img src="https://img.shields.io/github/stars/blacksnail789521/LLM4TS?style=social&amp;label=Code+Stars" alt="Code Stars"></a></span>
  </summary>
  <div class="pub-body">
    <div class="pub-fig"><img src="images/papers/llm4ts.png" alt="LLM4TS" width="1952" height="900" loading="lazy"></div>
    <p class="pub-desc">LLM4TS is a framework that adapts pre-trained Large Language Models for multivariate time series forecasting through a two-stage fine-tuning process. It captures multi-scale temporal patterns and achieves state-of-the-art performance across full-shot and few-shot settings.</p>
  </div>
</details>

<details class="pub" data-scholar-id="7PzlFSSx8tAC">
  <summary><span class="pub-badge">TechRxiv 2025</span> <a href="https://www.techrxiv.org/users/1020340/articles/1380448-training-recipes-for-agentic-reinforcement-learning-in-llms-a-survey">Training Recipes for Agentic Reinforcement Learning in LLMs: A Survey</a>
    <span class="pub-authors"><b>Ching Chang</b>, Yijia Xiao, Jade Xu, Fred Xu, Chenchen Ye, Ruoyan Li, Junkai Zhang, Yihe Deng, Kyle Zheng, Ethan Ji, Alexander K Taylor, Weikai Li, Maryam Haghifam, Anthony Cuturrufo, Renliang Sun, Jiahang Sha, Yidan Shi, Wen-Chih Peng, Yizhou Sun, Wei Wang</span>
    <span class="pub-links"><a href="https://github.com/blacksnail789521/Agentic-RL-Training-Recipes"><img src="https://img.shields.io/github/stars/blacksnail789521/Agentic-RL-Training-Recipes?style=social&amp;label=Code+Stars" alt="Code Stars"></a></span>
  </summary>
  <div class="pub-body">
    <div class="pub-fig"><img src="images/papers/agentic_rl_survey.png" alt="Agentic RL Survey" width="1589" height="703" loading="lazy"></div>
    <p class="pub-desc">This survey systematizes the training recipes, infrastructure, and environments of Agentic Reinforcement Learning to provide a unified framework for building robust, generalist autonomous agents from scratch, addressing the shortcomings of standard alignment methods like RLHF.</p>
  </div>
</details>

<details class="pub" data-scholar-id="Wp0gIr-vW9MC">
  <summary><span class="pub-badge">TMLR 2026</span> <a href="https://openreview.net/forum?id=l3QW42g6u3">A Survey of Reasoning and Agentic Systems in Time Series with Large Language Models</a>
    <span class="pub-authors"><b>Ching Chang</b>, Yidan Shi, Defu Cao, Wei Yang, Jeehyun Hwang, Haixin Wang, Jiacheng Pang, Wei Wang, Yan Liu, Wen-Chih Peng, Tien-Fu Chen</span>
    <span class="pub-links">{% include scholar_citation_button.html user="OXCVj48AAAAJ" paper="Wp0gIr-vW9MC" %} <a href="https://github.com/blacksnail789521/Time-Series-Reasoning-Survey"><img src="https://img.shields.io/github/stars/blacksnail789521/Time-Series-Reasoning-Survey?style=social&amp;label=Code+Stars" alt="Code Stars"></a></span>
  </summary>
  <div class="pub-body">
    <div class="pub-fig"><img src="images/papers/ts_reasoning_survey.png" alt="Time-Series-Reasoning-Survey" width="2153" height="956" loading="lazy"></div>
    <p class="pub-desc">Defines time-series reasoning through a two-level taxonomy (reasoning topology × primary objectives) and a compact attribute tag set (e.g., decomposition, verification, tool use, multimodality, alignment), while curating research and non-research works with guidance on evaluation and deployment.</p>
  </div>
</details>

<details class="pub" data-scholar-id="mVmsd5A6BfQC">
  <summary><span class="pub-badge">ICDM 2026</span> <a href="https://arxiv.org/abs/2510.09930">Perseus: Interactive Time Series Segmentation with Sparse Supervision via Stateful Memory</a>
    <span class="pub-authors"><b>Ching Chang</b>, Ming-Chih Lo, Chiao-Tung Chan, Wen-Chih Peng, Tien-Fu Chen</span>
    <span class="pub-links">{% include scholar_citation_button.html user="OXCVj48AAAAJ" paper="mVmsd5A6BfQC" %} <a href="https://github.com/blacksnail789521/Perseus"><img src="https://img.shields.io/github/stars/blacksnail789521/Perseus?style=social&amp;label=Code+Stars" alt="Code Stars"></a></span>
  </summary>
  <div class="pub-body">
    <div class="pub-fig"><img src="images/papers/perseus.png" alt="Perseus" width="2888" height="1150" loading="lazy"></div>
    <p class="pub-desc">Perseus is an interactive framework for multi-granularity time series segmentation under sparse supervision. Each user prompt is encoded with its local context into a persistent memory bank, so predictions condition on all prompts accumulated across iterations rather than only their local neighborhood. Across six wearable-sensing and industrial datasets, it improves segmentation accuracy by 23% (single-granularity) and 85% (multi-granularity) over strong baselines, with more than double the per-iteration refinement gains of its predecessor PromptTSS.</p>
  </div>
</details>

<details class="pub" data-scholar-id="dhFuZR0502QC">
  <summary><span class="pub-badge">ICML 2026</span> <a href="https://doi.org/10.36227/techrxiv.177092226.67693184/v1">Position: Beyond Prediction: Toward Verifiable Physiological Waveform Reasoning with Foundation Models and Agentic LLMs</a>
    <span class="pub-authors">Xiaoda Wang, <b>Ching Chang</b>, Defu Cao, Kaiqiao Han, Fang Sun, Yue Huang, Minxiao Wang, Chang Xu, Xiao Luo, Runze Yan, Xiangliang Zhang, Xiao Hu, Yan Liu, Yizhou Sun, Wei Wang, Carl Yang</span>
    <span class="pub-links">{% include scholar_citation_button.html user="OXCVj48AAAAJ" paper="dhFuZR0502QC" %}</span>
  </summary>
  <div class="pub-body">
    <div class="pub-fig"><img src="images/papers/waveform_reasoning.png" alt="Verifiable physiological waveform reasoning" width="2115" height="880" loading="lazy"></div>
    <p class="pub-desc">This position paper argues that physiological waveform analysis should move beyond black-box prediction toward verifiable reasoning, mapping how foundation models and agentic LLMs can ground, verify, and explain conclusions drawn from signals such as ECG and PPG, and laying out the field's open challenges and research agenda.</p>
  </div>
</details>

<details class="pub" data-scholar-id="4DMP91E08xMC">
  <summary><span class="pub-badge">KDD 2026</span> <a href="https://arxiv.org/abs/2505.20349">FD-Bench: A Modular and Fair Benchmark for Data-driven Fluid Simulation</a>
    <span class="pub-authors">Haixin Wang, Ruoyan Li, Fred Xu, Fang Sun, Kaiqiao Han, Zijie Huang, <b>Ching Chang</b>, Xiao Luo, Wei Wang, Yizhou Sun</span>
    <span class="pub-links">{% include scholar_citation_button.html user="OXCVj48AAAAJ" paper="4DMP91E08xMC" %} <a href="https://github.com/WillDreamer/FD-Bench"><img src="https://img.shields.io/github/stars/WillDreamer/FD-Bench?style=social&amp;label=Code+Stars" alt="Code Stars"></a></span>
  </summary>
  <div class="pub-body">
    <div class="pub-fig"><img src="images/papers/fd_bench.png" alt="FD-Bench fluid flow scenarios" width="1230" height="600" loading="lazy"></div>
    <p class="pub-desc">FD-Bench is a modular benchmark for data-driven fluid simulation that enables fair, reproducible comparisons across spatial, temporal, and loss-function design choices, evaluating 85 baseline models over diverse flow scenarios with standardized protocols and a public leaderboard.</p>
  </div>
</details>

<div class="pub">
  <span class="pub-badge">Under Review (NeurIPS 2026)</span> FraMe: Fractal Generative Framework for Molecular Dynamics
  <span class="pub-authors">Yidan Shi, Fang Sun, Yuanzhou Chen, Yanqiao Zhu, Jeehyun Hwang, <b>Ching Chang</b>, Yizhou Sun, Wei Wang</span>
</div>

<details class="pub" data-scholar-id="aqlVkmm33-oC">
  <summary><span class="pub-badge">CIKM 2025</span> <a href="https://doi.org/10.1145/3746252.3761142">PromptTSS: A Prompting-Based Approach for Interactive Multi-Granularity Time Series Segmentation</a>
    <span class="pub-authors"><b>Ching Chang</b>, Ming-Chih Lo, Wen-Chih Peng, Tien-Fu Chen</span>
    <span class="pub-links">{% include scholar_citation_button.html user="OXCVj48AAAAJ" paper="aqlVkmm33-oC" %} <a href="https://github.com/blacksnail789521/PromptTSS"><img src="https://img.shields.io/github/stars/blacksnail789521/PromptTSS?style=social&amp;label=Code+Stars" alt="Code Stars"></a> <a class="pub-link-btn" href="https://docs.google.com/presentation/d/1V0LVSP-4VTjj-B81AIC64TM9LHXgisJo/edit?usp=sharing&amp;ouid=102526612289511924674&amp;rtpof=true&amp;sd=true">Slides</a> <a class="pub-link-btn" href="https://youtu.be/u5teQmsHsHI">Video</a></span>
  </summary>
  <div class="pub-body">
    <div class="pub-fig"><img src="images/papers/prompttss.png" alt="PromptTSS" width="3491" height="1369" loading="lazy"></div>
    <p class="pub-desc">PromptTSS is a framework that unifies coarse- and fine-grained time series segmentation using prompts for dynamic adaptation. It achieves substantial accuracy gains in segmentation and transfer learning, showing strong effectiveness for hierarchical, evolving time series.</p>
  </div>
</details>

<details class="pub" data-scholar-id="WF5omc3nYNoC">
  <summary><span class="pub-badge">ICDE 2024</span> <a href="https://arxiv.org/abs/2312.04142">TimeDRL: Disentangled Representation Learning for Multivariate Time-Series</a>
    <span class="pub-authors"><b>Ching Chang</b>, Chiao-Tung Chan, Wei-Yao Wang, Wen-Chih Peng, Tien-Fu Chen</span>
    <span class="pub-links">{% include scholar_citation_button.html user="OXCVj48AAAAJ" paper="WF5omc3nYNoC" %} <a href="https://github.com/blacksnail789521/TimeDRL"><img src="https://img.shields.io/github/stars/blacksnail789521/TimeDRL?style=social&amp;label=Code+Stars" alt="Code Stars"></a> <a class="pub-link-btn" href="https://youtu.be/LyDl77cS7Ko">Video</a></span>
  </summary>
  <div class="pub-body">
    <div class="pub-fig"><img src="images/papers/timedrl.png" alt="TimeDRL" width="2048" height="894" loading="lazy"></div>
    <p class="pub-desc">TimeDRL is a self-supervised learning framework for multivariate time series data that learns disentangled timestamp- and instance-level embeddings without relying on augmentations. It introduces dual-level objectives for predictive and contrastive learning, and achieves strong performance across forecasting and classification tasks, even in low-label scenarios.</p>
  </div>
</details>

<details class="pub" data-scholar-id="UebtZRa9Y70C">
  <summary><span class="pub-badge">CIKM 2024</span> <a href="https://arxiv.org/abs/2407.12254">COKE: Causal Discovery with Chronological Order and Expert Knowledge in High Proportion of Missing Manufacturing Data</a>
    <span class="pub-authors">Ting-Yun Ou, <b>Ching Chang</b>, Wen-Chih Peng</span>
    <span class="pub-links">{% include scholar_citation_button.html user="OXCVj48AAAAJ" paper="UebtZRa9Y70C" %} <a href="https://github.com/outingyun/coke"><img src="https://img.shields.io/github/stars/outingyun/coke?style=social&amp;label=Code+Stars" alt="Code Stars"></a></span>
  </summary>
  <div class="pub-body">
    <div class="pub-fig"><img src="images/papers/coke.png" alt="COKE framework" width="1700" height="880" loading="lazy"></div>
    <p class="pub-desc">COKE discovers causal graphs in manufacturing data with extreme missingness (up to 90%) by exploiting expert knowledge and the chronological order among sensors instead of imputing missing values, improving F1-score by 39.9% on average over prior methods on semiconductor manufacturing datasets.</p>
  </div>
</details>

<details class="pub" data-scholar-id="_FxGoFyzp5QC">
  <summary><span class="pub-badge">AAAI 2024</span> <a href="https://arxiv.org/abs/2402.01140">Root Cause Analysis in Microservice Using Neural Granger Causal Discovery</a>
    <span class="pub-authors">Zheng-Ming Lin, <b>Ching Chang</b>, Wei-Yao Wang, Kuang-Da Wang, Wen-Chih Peng</span>
    <span class="pub-links">{% include scholar_citation_button.html user="OXCVj48AAAAJ" paper="_FxGoFyzp5QC" %} <a href="https://github.com/zmlin1998/RUN"><img src="https://img.shields.io/github/stars/zmlin1998/RUN?style=social&amp;label=Code+Stars" alt="Code Stars"></a></span>
  </summary>
  <div class="pub-body">
    <div class="pub-fig"><img src="images/papers/run.png" alt="RUN framework" width="2140" height="760" loading="lazy"></div>
    <p class="pub-desc">RUN performs root cause analysis in microservice systems via neural Granger causal discovery with contrastive learning, exploiting temporal precedence in time series to localize failure sources more accurately than existing techniques.</p>
  </div>
</details>

<details class="pub" data-scholar-id="hqOjcs7Dif8C">
  <summary><span class="pub-badge">NeurIPS 2024 (Workshop: Time Series in the Age of Large Models)</span> <a href="https://arxiv.org/abs/2411.00929">Text2Freq: Learning Series Patterns from Text via Frequency Domain</a>
    <span class="pub-authors">Ming-Chih Lo, <b>Ching Chang</b>, Wen-Chih Peng</span>
    <span class="pub-links">{% include scholar_citation_button.html user="OXCVj48AAAAJ" paper="hqOjcs7Dif8C" %}</span>
  </summary>
  <div class="pub-body">
    <div class="pub-fig"><img src="images/papers/text2freq.png" alt="Text2Freq overview" width="1680" height="480" loading="lazy"></div>
    <p class="pub-desc">Text2Freq integrates textual event information with time series through the frequency domain, aligning text to the low-frequency components of the series to bridge the modality gap and improve forecasting performance.</p>
  </div>
</details>

<details class="pub" data-scholar-id="5nxA0vEk-isC">
  <summary><span class="pub-badge">NeurIPS 2024 (Workshop: Time Series in the Age of Large Models)</span> <a href="https://openreview.net/forum?id=AaRCmJieG4">Align and Fine-Tune: Enhancing LLMs for Time-Series Forecasting</a>
    <span class="pub-authors"><b>Ching Chang</b>, Wei-Yao Wang, Wen-Chih Peng, Tien-Fu Chen, Sagar Samtani</span>
    <span class="pub-links">{% include scholar_citation_button.html user="OXCVj48AAAAJ" paper="5nxA0vEk-isC" %}</span>
  </summary>
  <div class="pub-body">
    <div class="pub-fig"><img src="images/papers/align_finetune.png" alt="Align and Fine-Tune framework" width="1980" height="980" loading="lazy"></div>
    <p class="pub-desc">Proposes an align-then-fine-tune recipe for adapting pre-trained LLMs to time-series forecasting — first aligning temporal representations with the language model's embedding space, then fine-tuning for the forecasting task; the workshop precursor to LLM4TS.</p>
  </div>
</details>

<details class="pub" data-scholar-id="8k81kl-MbHgC">
  <summary><span class="pub-badge">NeurIPS 2024 (Workshop: Self-Supervised Learning - Theory and Practice)</span> <a href="https://openreview.net/forum?id=GnME2Gx5H3">Self-Supervised Learning of Disentangled Representations for Multivariate Time-Series</a>
    <span class="pub-authors"><b>Ching Chang</b>, Chan Chiao-Tung, Wei-Yao Wang, Wen-Chih Peng, Tien-Fu Chen</span>
    <span class="pub-links">{% include scholar_citation_button.html user="OXCVj48AAAAJ" paper="8k81kl-MbHgC" %}</span>
  </summary>
  <div class="pub-body">
    <div class="pub-fig"><img src="images/papers/ssl_disentangled.png" alt="Self-supervised learning without augmentation" width="2680" height="600" loading="lazy"></div>
    <p class="pub-desc">Learns disentangled timestamp-level and instance-level representations of multivariate time series with self-supervised objectives, reducing reliance on augmentation-induced inductive biases; the workshop precursor to TimeDRL.</p>
  </div>
</details>

</div>

<script>
(function () {
  var list = document.getElementById('pub-list');
  if (!list) return;
  var featured = Array.prototype.slice.call(list.querySelectorAll('.pub'));
  var cites = null;
  function yearOf(card) {
    var badge = card.querySelector('.pub-badge');
    var m = badge ? badge.textContent.match(/(19|20)\d{2}/) : null;
    return m ? parseInt(m[0], 10) : 0;
  }
  function loadCites() {
    if (cites) return Promise.resolve(cites);
    return fetch('https://raw.githubusercontent.com/blacksnail789521/blacksnail789521.github.io/google-scholar-stats/gs_data.json')
      .then(function (r) { return r.json(); })
      .then(function (j) {
        cites = {};
        Object.keys(j.publications || {}).forEach(function (k) {
          cites[k.split(':').pop()] = j.publications[k].num_citations || 0;
        });
        return cites;
      });
  }
  function reorder(order) {
    order.forEach(function (c) { list.appendChild(c); });
  }
  function apply(mode) {
    if (mode === 'year') {
      reorder(featured.slice().sort(function (a, b) { return yearOf(b) - yearOf(a); }));
    } else if (mode === 'citations') {
      loadCites().then(function () {
        var n = function (c) { return cites[c.getAttribute('data-scholar-id')] || 0; };
        reorder(featured.slice().sort(function (a, b) { return n(b) - n(a); }));
      }).catch(function () { /* crawler snapshot unreachable — keep current order */ });
    } else {
      reorder(featured.slice());
    }
  }
  document.querySelectorAll('.pub-sort-btn').forEach(function (btn) {
    btn.addEventListener('click', function () {
      document.querySelectorAll('.pub-sort-btn').forEach(function (b) { b.classList.remove('active'); });
      btn.classList.add('active');
      apply(btn.getAttribute('data-sort'));
    });
  });
})();
</script>


# 🎖 Honors and Awards

- *2025.12* **Financial Assistance Award**, NeurIPS 2025, San Diego, USA  
- *2025.06* **Outstanding Reviewer Award (Top 10% of Reviewers)**, KDD 2025, Toronto, Canada  
- *2024.11* **Overseas Postgraduate Research Fellowship Program**, National Science and Technology Council, Taipei, Taiwan  
- *2024.06* **International Conference Scholarship**, National Yang Ming Chiao Tung University, Taipei, Taiwan  
- *2024.05* **International Conference Scholarship**, National Science and Technology Council, Taipei, Taiwan  
- *2024.02* **AAAI Student Scholarship**, 38th AAAI Conference on Artificial Intelligence, Vancouver, Canada  
- *2022.02* **Xin Miao Key Technology Doctoral Scholarship**, Xin Miao Education Foundation, Taipei, Taiwan  
- *2021.09* **Industry-Academia Cooperative PhD Project Scholarship**, Ministry of Education Republic of China (Taiwan), Taipei, Taiwan  

# 💬 Invited Talks
- *2025.09*, **Time Series AI for Strategic Business Intelligence and Manufacturing Optimization**, *TSMC AI4BI Innovation Center*
  
  Delivered a talk on leveraging AI-driven time series analysis to generate actionable business intelligence.
  [![](https://img.shields.io/badge/Slides-grey?style=flat)](https://drive.google.com/file/d/1oSLXOhx9DsBxLB8m9pm_-qHbnNIGPHxf/view?usp=sharing)

- *2025.06*, **Advanced Time Series Analysis Techniques for Industrial Applications**, *University of Southern California (USC)*
  
  Delivered a talk on cutting-edge time series analysis methods tailored for deployment in industrial and manufacturing settings.
  [![](https://img.shields.io/badge/Slides-grey?style=flat)](https://drive.google.com/file/d/1eD-53hLCqnPFsS0EYF8BpSBT8IRjnZSv/view?usp=sharing)

- *2023.08*, **Time Series Analysis with LLMs**, *LLM Industry-Academia Technical Exchange Conference, National Center for High-Performance Computing*
  
  Discussed the use of large language models for analyzing time series data and their potential applications in industry.  
  Shared the stage with **Hung-Yi Lee** and **Hsiang-Tsung Kung**. [![](https://img.shields.io/badge/Website-grey?style=flat)](https://nycuaib.web.nycu.edu.tw/) [![](https://img.shields.io/badge/Slides-grey?style=flat)](https://drive.google.com/file/d/1eRCoS0OoDHh_-kxDZ4pckEiLAWY6jB9q/view?usp=sharing) [![](https://img.shields.io/badge/Video-grey?style=flat)](https://youtu.be/QJOEW8PUidY)

# 🎓 Academic Services  

- **Reviewer for Conferences**: NeurIPS, ICLR, ICML, KDD, AAAI, WWW, ICDE
- **Reviewer for Journals**: TNNLS, TIST, TMLR, TSC, ESWA

# 👤 Visitors

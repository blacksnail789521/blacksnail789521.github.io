---
permalink: /
title: "Ching (Jason) Chang | AI Researcher | UCLA & NYCU"
excerpt: "Personal website of Ching (Jason) Chang, PhD candidate at NYCU and Visiting Researcher at UCLA. Research in AI, Time Series Analysis, Causal Discovery."
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

Hello 👋, My name is Ching Chang, also known as Jason Chang, and I am a PhD candidate (ABD) in Computer Science at National Yang Ming Chiao Tung University (NYCU), Taiwan, advised by [Prof. Wen-Chih Peng](https://sites.google.com/site/wcpeng/). Currently, I am a Visiting Graduate Researcher in Computer Science at UCLA, working with [Prof. Wei Wang](http://web.cs.ucla.edu/~weiwang/).  

My research focuses on Time Series Analysis, Large Foundation Models, Causal Discovery, and Multimodal Reasoning. I have published multiple papers in top AI and data science conferences and journals, including NeurIPS, AAAI, ICDE, CIKM, and ACM TIST, with total
<a href='https://scholar.google.com/citations?user=OXCVj48AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=google citations"></a>.
I have also served as a reviewer for 49 papers across top-tier conferences and journals, including ICML, KDD, NeurIPS, ICLR, AAAI, WWW, TNNLS, and ACM TIST.

<!-- If you're interested in collaboration, feel free to contact me at blacksnail789521@gmail.com.  -->
If you're interested in collaboration, feel free to contact me at [blacksnail789521@gmail.com](mailto:blacksnail789521@gmail.com).
You can also check out my [CV here 📄](https://drive.google.com/file/d/1eRdYM8OSQdDivrsxibaa-aeC_EphcOlx/view?usp=sharing).

<!-- # 🔥 News

- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. -->

# 📖 Education

- *2021.09 – 2026.03 (Expected)*, **National Yang Ming Chiao Tung University (NYCU), Taiwan**, PhD in Computer Science (ABD)  
- *2025.02 – 2026.02 (Expected)*, **University of California, Los Angeles (UCLA), USA**, Visiting Graduate Researcher in Computer Science  
- *2016.09 – 2018.09*, **National Chiao Tung University (NCTU), Taiwan**, MSc in Computer Science and Engineering  
- *2012.09 – 2016.06*, **National Chiao Tung University (NCTU), Taiwan**, BSc in Electrical and Computer Engineering

# 💻 Work Experience

- *2022.09 – 2025.02*, **Research Scientist (Intern)**, TSMC, Hsinchu, Taiwan  
  Root Cause Analysis · Causal Discovery · Time Series Analysis  

- *2021.01 – 2025.01*, **Research Scientist (Intern)**, GoEdge.ai, Hsinchu, Taiwan  
  Time Series Analysis · Large Foundation Models · Causal Discovery  

- *2019.07 – 2020.12*, **Machine Learning Engineer**, TSMC, Hsinchu, Taiwan  
  Root Cause Analysis  

- *2018.04 – 2018.09*, **Machine Learning Engineer (Intern)**, EPISTAR, Hsinchu, Taiwan  
  Root Cause Analysis  

- *2016.07 – 2016.08*, **Software Engineer (Intern)**, MediaTek, Hsinchu, Taiwan  
  Multimedia Firmware

# 📝 Publications

<style>
.paper-box-image {
  background-color: white; /* force white behind image */
}

.paper-box-image img {
  background-color: white; /* if PNG has transparency */
  display: block;
  width: 100%;
}
</style>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">NeurIPS 2025</div>
      <img src='images/papers/timeimm.png' alt="Time-IMM" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[A Survey of Reasoning and Agentic Systems in Time Series with Large Language Models](https://arxiv.org/abs/2506.10412)

**Ching Chang**, Jeehyun Hwang, Yidan Shi, Haixin Wang, Wen-Chih Peng, Tien-Fu Chen, Wei Wang

<strong><span class='show_paper_citations' data='OXCVj48AAAAJ:qxL8FJ1GzNcC'></span></strong> \| [![](https://img.shields.io/github/stars/blacksnail789521/Time-Series-Reasoning-Survey?style=social&label=Code+Stars)](https://github.com/blacksnail789521/Time-Series-Reasoning-Survey)

- Time-IMM is a comprehensive benchmark and open-source library designed for irregular, multimodal time series. It introduces nine real-world datasets across diverse domains and provides tools for fusing asynchronous text with numeric signals, showing that multimodal integration can significantly enhance forecasting in complex, real-world settings.

</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">arXiv 2025</div>
      <img src='images/papers/tsreasoningsurvey.png' alt="Time-Series-Reasoning-Survey" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[A Survey of Reasoning and Agentic Systems in Time Series with Large Language Models](https://arxiv.org/abs/2509.11575)

**Ching Chang**, Yidan Shi, Defu Cao, Wei Yang, Jeehyun Hwang, Haixin Wang, Jiacheng Pang, Wei Wang, Yan Liu, Wen-Chih Peng, Tien-Fu Chen

<strong><span class='show_paper_citations' data='OXCVj48AAAAJ:Wp0gIr-vW9MC'></span></strong> \| [![](https://img.shields.io/github/stars/blacksnail789521/Time-Series-Reasoning-Survey?style=social&label=Code+Stars)](https://github.com/blacksnail789521/Time-Series-Reasoning-Survey)

- Defines **time-series reasoning** through a **two-level taxonomy** (reasoning topology × primary objectives) and a compact **attribute tag set** (e.g., decomposition, verification, tool use, multimodality, alignment), while curating research and non-research works with guidance on evaluation and deployment.

</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ACM TIST 2025</div>
      <img src='images/papers/llm4ts.png' alt="LLM4TS" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[LLM4TS: Aligning Pre-Trained LLMs as Data-Efficient Time-Series Forecasters](https://dl.acm.org/doi/10.1145/3719207)

**Ching Chang**, Wei-Yao Wang, Wen-Chih Peng, Tien-Fu Chen

<strong><span class='show_paper_citations' data='OXCVj48AAAAJ:Zph67rFs4hoC'></span></strong> \| [![](https://img.shields.io/github/stars/blacksnail789521/LLM4TS?style=social&label=Code+Stars)](https://github.com/blacksnail789521/LLM4TS)

- LLM4TS is a framework that adapts pre-trained Large Language Models for multivariate time series forecasting through a two-stage fine-tuning process. It captures multi-scale temporal patterns and achieves state-of-the-art performance across full-shot and few-shot settings.

</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">CIKM 2025</div>
      <img src='images/papers/prompttss.png' alt="PromptTSS" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[PromptTSS: A Prompt-based Framework for Time Series Forecasting](https://doi.org/10.1145/3746252.3761142)

**Ching Chang**, Ming-Chih Lo, Wen-Chih Peng, Tien-Fu Chen

<strong><span class='show_paper_citations' data='OXCVj48AAAAJ:aqlVkmm33-oC'></span></strong> \| [![](https://img.shields.io/github/stars/blacksnail789521/PromptTSS?style=social&label=Code+Stars)](https://github.com/blacksnail789521/PromptTSS)

- PromptTSS is a framework that unifies coarse- and fine-grained time series segmentation using prompts for dynamic adaptation. It achieves substantial accuracy gains in segmentation and transfer learning, showing strong effectiveness for hierarchical, evolving time series.

</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ICDE 2024</div>
      <img src='images/papers/timedrl.png' alt="TimeDRL" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[TimeDRL: Disentangled Representation Learning for Multivariate Time-Series](https://arxiv.org/abs/2312.04142)

**Ching Chang**, Chiao-Tung Chan, Wei-Yao Wang, Wen-Chih Peng, Tien-Fu Chen

<strong><span class='show_paper_citations' data='OXCVj48AAAAJ:WF5omc3nYNoC'></span></strong> \| 
[![](https://img.shields.io/github/stars/blacksnail789521/TimeDRL?style=social&label=Code+Stars)](https://github.com/blacksnail789521/TimeDRL) 
[![YouTube](https://img.shields.io/badge/YouTube-Video-red?logo=youtube&style=flat-square)](https://youtu.be/LyDl77cS7Ko)

- TimeDRL is a self-supervised learning framework for multivariate time series data that learns disentangled timestamp- and instance-level embeddings without relying on augmentations. It introduces dual-level objectives for predictive and contrastive learning, and achieves strong performance across forecasting and classification tasks, even in low-label scenarios.

</div>
</div>


<!-- - ``ACM TIST 2025`` [LLM4TS: Aligning Pre-Trained LLMs as Data-Efficient Time-Series Forecasters](https://dl.acm.org/doi/10.1145/3719207), **Ching Chang**, Wei-Yao Wang, Wen-Chih Peng, Tien-Fu Chen. [![](https://img.shields.io/github/stars/blacksnail789521/LLM4TS?style=social&label=Code+Stars)](https://github.com/blacksnail789521/LLM4TS)   -->

- ``AAAI 2025 (Workshop: AI4TS)`` [PromptTSS: A Unified Model for Time Series Segmentation with Multi-Granularity States](https://github.com/AI4TS/AI4TS.github.io/blob/main/Camera_Ready_AAAI2025/23%5CCameraReady%5CPromptTSS__AAAI_2025_workshop_.pdf), **Ching Chang**, Ming-Chih Lo, Wen-Chih Peng, Tien-Fu Chen.

- ``NeurIPS 2024 (Workshop: Time Series in the Age of Large Models)`` [Align and Fine-Tune: Enhancing LLMs for Time-Series Forecasting](https://openreview.net/forum?id=AaRCmJieG4), **Ching Chang**, Wei-Yao Wang, Wen-Chih Peng, Tien-Fu Chen, Sagar Samtani.

- ``NeurIPS 2024 (Workshop: Self-Supervised Learning - Theory and Practice)`` [Self-Supervised Learning of Disentangled Representations for Multivariate Time-Series](https://openreview.net/forum?id=GnME2Gx5H3), **Ching Chang**, Chan Chiao-Tung, Wei-Yao Wang, Wen-Chih Peng, Tien-Fu Chen.

- ``NeurIPS 2024 (Workshop: Time Series in the Age of Large Models)`` [Text2Freq: Learning Series Patterns from Text via Frequency Domain](https://arxiv.org/abs/2411.00929), Ming-Chih Lo, **Ching Chang**, Wen-Chih Peng.

<!-- - ``ICDE 2024`` [TimeDRL: Disentangled Representation Learning for Multivariate Time-Series](https://arxiv.org/abs/2312.04142), **Ching Chang**, Chiao-Tung Chan, Wei-Yao Wang, Wen-Chih Peng, Tien-Fu Chen. [![](https://img.shields.io/github/stars/blacksnail789521/TimeDRL?style=social&label=Code+Stars)](https://github.com/blacksnail789521/TimeDRL) [![YouTube](https://img.shields.io/badge/YouTube-Video-red?logo=youtube&style=flat-square)](https://youtu.be/LyDl77cS7Ko) -->

- ``CIKM 2024`` [COKE: Causal Discovery with Chronological Order and Expert Knowledge in High Proportion of Missing Manufacturing Data](https://arxiv.org/abs/2312.04142), Ting-Yun Ou, **Ching Chang**, Wen-Chih Peng. [![](https://img.shields.io/github/stars/outingyun/coke?style=social&label=Code+Stars)](https://github.com/outingyun/coke)  

- ``AAAI 2024`` [Root Cause Analysis in Microservice Using Neural Granger Causal Discovery](https://arxiv.org/abs/2402.01140), Zheng-Ming Lin, **Ching Chang**, Wei-Yao Wang, Kuang-Da Wang, Wen-Chih Peng. [![](https://img.shields.io/github/stars/zmlin1998/RUN?style=social&label=Code+Stars)](https://github.com/zmlin1998/RUN)

- ``Preprint`` [Detecting and Ranking Causal Anomalies in End-to-End Complex System](https://arxiv.org/abs/2301.07281), **Ching Chang**, Wen-Chih Peng.

# 🎖 Honors and Awards

- *2025.06* **Outstanding Reviewer Award (Top 10% of Reviewers)**, KDD 2025, Toronto, Canada  
- *2024.11* **Overseas Postgraduate Research Fellowship Program**, National Science and Technology Council, Taipei, Taiwan  
- *2024.06* **International Conference Scholarship**, National Yang Ming Chiao Tung University, Taipei, Taiwan  
- *2024.05* **International Conference Scholarship**, National Science and Technology Council, Taipei, Taiwan  
- *2024.02* **AAAI Student Scholarship**, 38th AAAI Conference on Artificial Intelligence, Vancouver, Canada  
- *2022.02* **Xin Miao Key Technology Doctoral Scholarship**, Xin Miao Education Foundation, Taipei, Taiwan  
- *2021.09* **Industry-Academia Cooperative PhD Project Scholarship**, Ministry of Education Republic of China (Taiwan), Taipei, Taiwan  

# 💬 Invited Talks
- *2025.06*, **Advanced Time Series Analysis Techniques for Industrial and Manufacturing Applications**, *University of Southern California (USC)*
  Delivered a talk on cutting-edge time series analysis methods tailored for deployment in industrial and manufacturing settings.
  [![Slides](https://img.shields.io/badge/Slides-PDF-green?logo=google-drive&style=flat-square)](https://drive.google.com/file/d/1eD-53hLCqnPFsS0EYF8BpSBT8IRjnZSv/view?usp=sharing)

- *2023.08*, **Time Series Analysis with LLMs**, *LLM Industry-Academia Technical Exchange Conference, National Center for High-Performance Computing*
  Discussed the use of large language models for analyzing time series data and their potential applications in industry.  
  Shared the stage with **Hung-Yi Lee** and **Hsiang-Tsung Kung**. [![Website](https://img.shields.io/badge/Website-Link-blue?logo=google-chrome&style=flat-square)](https://nycuaib.web.nycu.edu.tw/) [![Slides](https://img.shields.io/badge/Slides-PDF-green?logo=google-drive&style=flat-square)](https://drive.google.com/file/d/1eRCoS0OoDHh_-kxDZ4pckEiLAWY6jB9q/view?usp=sharing) [![YouTube](https://img.shields.io/badge/YouTube-Video-red?logo=youtube&style=flat-square)](https://youtu.be/QJOEW8PUidY)

# 🎓 Academic Services  

- **Reviewer for Conferences**: ICDE'24, KDD'24, NeurIPS'24, ICLR'25, AAAI'25, KDD'25, ICML'25, NeurIPS'25, KDD'26, AAAI'26, WWW'26, ICLR'26
- **Reviewer for Journals**: TNNLS'25, TIST'25, TMLR'25, TSC'25, ESWA'25
- **Student Volunteer**: AAAI'24

# 👤 Visitors
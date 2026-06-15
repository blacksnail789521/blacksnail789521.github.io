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

Hello 👋, My name is Ching Chang, also known as Jason Chang. I am currently a Staff ML Research Scientist at [Pravāh](https://pravah.com/). I received my PhD in Computer Science from National Yang Ming Chiao Tung University (NYCU), Taiwan, advised by [Prof. Wen-Chih Peng](https://sites.google.com/site/wcpeng/). Previously, I was a Visiting Graduate Researcher in Computer Science at UCLA, working with [Prof. Wei Wang](http://web.cs.ucla.edu/~weiwang/).  

My research focuses on Time Series Analysis, Foundation Models, Multimodal Learning, Agentic Reinforcement Learning, and Reasoning. I have published multiple papers in top AI and data science conferences and journals, including NeurIPS, AAAI, ICDE, CIKM, and ACM TIST, with total
<a href='https://scholar.google.com/citations?user=OXCVj48AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=google citations"></a>.

**Work Authorization:** EB-1A I-140 Approved • Currently on O-1A (new O-1A petition required for transfer)


# 📖 Education

- *2021.09 – 2026.03*, **National Yang Ming Chiao Tung University (NYCU), Taiwan**, PhD in Computer Science  
- *2025.02 – 2026.02*, **University of California, Los Angeles (UCLA), USA**, Visiting Graduate Researcher in Computer Science  
- *2016.09 – 2018.09*, **National Chiao Tung University (NCTU), Taiwan**, MSc in Computer Science and Engineering  
- *2012.09 – 2016.06*, **National Chiao Tung University (NCTU), Taiwan**, BSc in Electrical and Computer Engineering

# 💻 Work Experience

- *2026.03 – Now*, **Staff ML Research Scientist**, Pravah, San Francisco, CA, USA (Remote)  

- *2025.09 – 2026.02*, **Research Consultant**, TSMC, Hsinchu, Taiwan  

- *2022.09 – 2025.02*, **Research Scientist (Intern)**, TSMC, Hsinchu, Taiwan  

- *2021.01 – 2025.01*, **Research Scientist (Intern)**, GoEdge.ai, Hsinchu, Taiwan  

- *2019.07 – 2020.12*, **Machine Learning Engineer**, TSMC, Hsinchu, Taiwan  

- *2018.04 – 2018.09*, **Machine Learning Engineer (Intern)**, EPISTAR, Hsinchu, Taiwan

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
      <img src='images/papers/timeimm.png' alt="Time-IMM" width="1593" height="794" loading="lazy" style="width:100%;height:auto">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[Time-IMM: A Dataset and Benchmark for Irregular Multimodal Multivariate Time Series](https://arxiv.org/abs/2506.10412)

**Ching Chang**, Jeehyun Hwang, Yidan Shi, Haixin Wang, Wen-Chih Peng, Tien-Fu Chen, Wei Wang

{% include scholar_citation_button.html user="OXCVj48AAAAJ" paper="qxL8FJ1GzNcC" %} [![](https://img.shields.io/github/stars/blacksnail789521/Time-IMM?style=social&label=Code+Stars)](https://github.com/blacksnail789521/Time-IMM)
[![](https://img.shields.io/github/stars/blacksnail789521/IMM-TSF?style=social&label=Dataset+Stars)](https://github.com/blacksnail789521/IMM-TSF)
[![](https://img.shields.io/badge/Project-Page-grey?style=flat)](https://blacksnail789521.github.io/time-imm-project-page/)
[![](https://img.shields.io/badge/Video-grey?style=flat)](https://recorder-v3.slideslive.com/?share=103254&s=e5709e82-503d-4a79-88b1-271b89b1f69f)
[![](https://img.shields.io/badge/Slides-grey?style=flat)](https://docs.google.com/presentation/d/199W1ktlDa3lwBfGAhLSSGoD7LDLzlgO5/edit?usp=sharing)


- Time-IMM is a comprehensive benchmark and open-source library designed for irregular, multimodal time series. It introduces nine real-world datasets across diverse domains and provides tools for fusing asynchronous text with numeric signals, showing that multimodal integration can significantly enhance forecasting in complex, real-world settings.

</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">TechRxiv 2025</div>
      <img src='images/papers/agentic_rl_survey.png' alt="Agentic RL Survey" width="1589" height="703" loading="lazy" style="width:100%;height:auto">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[Training Recipes for Agentic Reinforcement Learning in LLMs: A Survey](https://www.techrxiv.org/users/1020340/articles/1380448-training-recipes-for-agentic-reinforcement-learning-in-llms-a-survey)

**Ching Chang**, Yijia Xiao,Jade Xu,Fred Xu,Chenchen Ye,Ruoyan Li,Junkai Zhang,Yihe Deng,Kyle Zheng,Ethan Ji,Alexander K Taylor,Weikai Li,Maryam Haghifam,Anthony Cuturrufo,Renliang Sun,Jiahang Sha,Yidan Shi,Wen-Chih Peng,Yizhou Sun,Wei Wang

<!-- {% include scholar_citation_button.html user="OXCVj48AAAAJ" paper="Wp0gIr-vW9MC" %}  -->
[![](https://img.shields.io/github/stars/blacksnail789521/Agentic-RL-Training-Recipes?style=social&label=Code+Stars)](https://github.com/blacksnail789521/Agentic-RL-Training-Recipes)

- This survey systematizes the training recipes, infrastructure, and environments of Agentic Reinforcement Learning to provide a unified framework for building robust, generalist autonomous agents from scratch, addressing the shortcomings of standard alignment methods like RLHF.

</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">TMLR 2026</div>
      <img src='images/papers/ts_reasoning_survey.png' alt="Time-Series-Reasoning-Survey" width="2153" height="956" loading="lazy" style="width:100%;height:auto">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[A Survey of Reasoning and Agentic Systems in Time Series with Large Language Models](https://openreview.net/forum?id=l3QW42g6u3)

**Ching Chang**, Yidan Shi, Defu Cao, Wei Yang, Jeehyun Hwang, Haixin Wang, Jiacheng Pang, Wei Wang, Yan Liu, Wen-Chih Peng, Tien-Fu Chen

{% include scholar_citation_button.html user="OXCVj48AAAAJ" paper="Wp0gIr-vW9MC" %} [![](https://img.shields.io/github/stars/blacksnail789521/Time-Series-Reasoning-Survey?style=social&label=Code+Stars)](https://github.com/blacksnail789521/Time-Series-Reasoning-Survey)

- Defines time-series reasoning through a two-level taxonomy (reasoning topology × primary objectives) and a compact attribute tag set (e.g., decomposition, verification, tool use, multimodality, alignment), while curating research and non-research works with guidance on evaluation and deployment.

</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ACM TIST 2025</div>
      <img src='images/papers/llm4ts.png' alt="LLM4TS" width="1952" height="900" loading="lazy" style="width:100%;height:auto">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[LLM4TS: Aligning Pre-Trained LLMs as Data-Efficient Time-Series Forecasters](https://dl.acm.org/doi/10.1145/3719207)

**Ching Chang**, Wei-Yao Wang, Wen-Chih Peng, Tien-Fu Chen

{% include scholar_citation_button.html user="OXCVj48AAAAJ" paper="Zph67rFs4hoC" %} [![](https://img.shields.io/github/stars/blacksnail789521/LLM4TS?style=social&label=Code+Stars)](https://github.com/blacksnail789521/LLM4TS)

- LLM4TS is a framework that adapts pre-trained Large Language Models for multivariate time series forecasting through a two-stage fine-tuning process. It captures multi-scale temporal patterns and achieves state-of-the-art performance across full-shot and few-shot settings.

</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">CIKM 2025</div>
      <img src='images/papers/prompttss.png' alt="PromptTSS" width="3491" height="1369" loading="lazy" style="width:100%;height:auto">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[PromptTSS: A Prompting-Based Approach for Interactive Multi-Granularity Time Series Segmentation](https://doi.org/10.1145/3746252.3761142)

**Ching Chang**, Ming-Chih Lo, Wen-Chih Peng, Tien-Fu Chen

{% include scholar_citation_button.html user="OXCVj48AAAAJ" paper="aqlVkmm33-oC" %} [![](https://img.shields.io/github/stars/blacksnail789521/PromptTSS?style=social&label=Code+Stars)](https://github.com/blacksnail789521/PromptTSS)
[![](https://img.shields.io/badge/Slides-grey?style=flat)](https://docs.google.com/presentation/d/1V0LVSP-4VTjj-B81AIC64TM9LHXgisJo/edit?usp=sharing&ouid=102526612289511924674&rtpof=true&sd=true)
[![](https://img.shields.io/badge/Video-grey?style=flat)](https://youtu.be/u5teQmsHsHI)

- PromptTSS is a framework that unifies coarse- and fine-grained time series segmentation using prompts for dynamic adaptation. It achieves substantial accuracy gains in segmentation and transfer learning, showing strong effectiveness for hierarchical, evolving time series.

</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ICDE 2024</div>
      <img src='images/papers/timedrl.png' alt="TimeDRL" width="2048" height="894" loading="lazy" style="width:100%;height:auto">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[TimeDRL: Disentangled Representation Learning for Multivariate Time-Series](https://arxiv.org/abs/2312.04142)

**Ching Chang**, Chiao-Tung Chan, Wei-Yao Wang, Wen-Chih Peng, Tien-Fu Chen

{% include scholar_citation_button.html user="OXCVj48AAAAJ" paper="WF5omc3nYNoC" %} [![](https://img.shields.io/github/stars/blacksnail789521/TimeDRL?style=social&label=Code+Stars)](https://github.com/blacksnail789521/TimeDRL)
[![](https://img.shields.io/badge/Video-grey?style=flat)](https://youtu.be/LyDl77cS7Ko)

- TimeDRL is a self-supervised learning framework for multivariate time series data that learns disentangled timestamp- and instance-level embeddings without relying on augmentations. It introduces dual-level objectives for predictive and contrastive learning, and achieves strong performance across forecasting and classification tasks, even in low-label scenarios.

</div>
</div>


<!-- - ``ACM TIST 2025`` [LLM4TS: Aligning Pre-Trained LLMs as Data-Efficient Time-Series Forecasters](https://dl.acm.org/doi/10.1145/3719207), **Ching Chang**, Wei-Yao Wang, Wen-Chih Peng, Tien-Fu Chen. [![](https://img.shields.io/github/stars/blacksnail789521/LLM4TS?style=social&label=Code+Stars)](https://github.com/blacksnail789521/LLM4TS)   -->

- ``Under Review (ICDM 2026)`` Perseus: Interactive Time Series Segmentation with Sparse Supervision via Stateful Memory, **Ching Chang**, Ming-Chih Lo, Chiao-Tung Chan, Wen-Chih Peng, Tien-Fu Chen.

- ``Under Review (NeurIPS 2026)`` FraMe: Fractal Generative Framework for Molecular Dynamics, Yidan Shi, Fang Sun, Yuanzhou Chen, Yanqiao Zhu, Jeehyun Hwang, **Ching Chang**, Yizhou Sun, Wei Wang.

- ``ICML 2026`` [Position: Beyond Prediction: Toward Verifiable Physiological Waveform Reasoning with Foundation Models and Agentic LLMs](https://doi.org/10.36227/techrxiv.177092226.67693184/v1), Xiaoda Wang, **Ching Chang**, Defu Cao, Kaiqiao Han, Fang Sun, Yue Huang, Minxiao Wang, Chang Xu, Xiao Luo, Runze Yan, Xiangliang Zhang, Xiao Hu, Yan Liu, Yizhou Sun, Wei Wang, Carl Yang.

- ``KDD 2026`` [FD-Bench: A Modular and Fair Benchmark for Data-driven Fluid Simulation](https://arxiv.org/abs/2505.20349), Haixin Wang, Ruoyan Li, Fred Xu, Fang Sun, Kaiqiao Han, Zijie Huang, **Ching Chang**, Xiao Luo, Wei Wang, Yizhou Sun. [![](https://img.shields.io/github/stars/WillDreamer/FD-Bench?style=social&label=Code+Stars)](https://github.com/WillDreamer/FD-Bench)

- ``AAAI 2025 (Workshop: AI4TS)`` [PromptTSS: A Unified Model for Time Series Segmentation with Multi-Granularity States](https://github.com/AI4TS/AI4TS.github.io/blob/main/Camera_Ready_AAAI2025/23%5CCameraReady%5CPromptTSS__AAAI_2025_workshop_.pdf), **Ching Chang**, Ming-Chih Lo, Wen-Chih Peng, Tien-Fu Chen.

- ``NeurIPS 2024 (Workshop: Time Series in the Age of Large Models)`` [Align and Fine-Tune: Enhancing LLMs for Time-Series Forecasting](https://openreview.net/forum?id=AaRCmJieG4), **Ching Chang**, Wei-Yao Wang, Wen-Chih Peng, Tien-Fu Chen, Sagar Samtani.

- ``NeurIPS 2024 (Workshop: Self-Supervised Learning - Theory and Practice)`` [Self-Supervised Learning of Disentangled Representations for Multivariate Time-Series](https://openreview.net/forum?id=GnME2Gx5H3), **Ching Chang**, Chan Chiao-Tung, Wei-Yao Wang, Wen-Chih Peng, Tien-Fu Chen.

- ``NeurIPS 2024 (Workshop: Time Series in the Age of Large Models)`` [Text2Freq: Learning Series Patterns from Text via Frequency Domain](https://arxiv.org/abs/2411.00929), Ming-Chih Lo, **Ching Chang**, Wen-Chih Peng.

<!-- - ``ICDE 2024`` [TimeDRL: Disentangled Representation Learning for Multivariate Time-Series](https://arxiv.org/abs/2312.04142), **Ching Chang**, Chiao-Tung Chan, Wei-Yao Wang, Wen-Chih Peng, Tien-Fu Chen. [![](https://img.shields.io/github/stars/blacksnail789521/TimeDRL?style=social&label=Code+Stars)](https://github.com/blacksnail789521/TimeDRL) [![YouTube](https://img.shields.io/badge/YouTube-Video-red?logo=youtube&style=flat)](https://youtu.be/LyDl77cS7Ko) -->

- ``CIKM 2024`` [COKE: Causal Discovery with Chronological Order and Expert Knowledge in High Proportion of Missing Manufacturing Data](https://arxiv.org/abs/2407.12254), Ting-Yun Ou, **Ching Chang**, Wen-Chih Peng. [![](https://img.shields.io/github/stars/outingyun/coke?style=social&label=Code+Stars)](https://github.com/outingyun/coke)  

- ``AAAI 2024`` [Root Cause Analysis in Microservice Using Neural Granger Causal Discovery](https://arxiv.org/abs/2402.01140), Zheng-Ming Lin, **Ching Chang**, Wei-Yao Wang, Kuang-Da Wang, Wen-Chih Peng. [![](https://img.shields.io/github/stars/zmlin1998/RUN?style=social&label=Code+Stars)](https://github.com/zmlin1998/RUN)

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

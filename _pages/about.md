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

# 🧑‍💻 Biography

I am now a fourth-year Ph.D. student at <a href='https://www.ai.pku.edu.cn'>the Institute for Artificial Intelligence</a>, Peking University, advised by <a href='https://muhanzhang.github.io'>Prof. Muhan Zhang</a>. I have interned at the <a href='https://klingai.com/global/'>Kling Team</a> and the <a href='https://www.happyhorse.com/'>HappyHorse Team</a> for video generation research and indursrial model development.


# 🔬 Research Interests

My research focuses on scalable generative models spanning multiple modalities, including videos, images, and molecules. I am interested in both theoretical foundations (e.g., representations expressiveness) and practical systems (e.g., architectures, acceleration, and industrial deployment). Recently, I have been particularly interested in video generation. My research interests include:

- **Video Generation:** architectures, pretraining paradigms, few-step distillation, refiners, and generation-friendly VAEs.
- **AI for Science:** geometric representations, molecule pretraining and generation paradigms, few-step generation, ai for biology.

If you are interested in these areas, feel free to reach out!

# 🎖 Honors and Awards
- **2025.10**, Doctoral Dean’s Scholarship, Institute for Artificial Intelligence, Peking University
- **2020.12, 2021.12, 2022.12**, National Scholarship for Undergraduate Student
- **2021.12**, Outstanding Student Pioneer of Tianjin University (Nomination Award) (only 10 awardees and 5 nominated awardees university-wide per year)
- **2021.08**, First Prize of National Zhou Peiyuan Competition on Mechanics (~0.3%)
- **2021.04**, Meritorious Winner (First Prize) of ICM: Interdisciplinary Contest In Modeling

# 📖 Educations
- <img src="../images/PKU logo.png" alt="PKU Logo" style="zoom:25%;" />        **2023.09 -**, Ph.D. student, Institute for Artificial Intelligence, Peking University
- <img src="../images/TJU logo.png" alt="TJU Logo" style="zoom:5.95%;" />        **2019.09 - 2023.07**, B.E., School of Future Technology, Tianjin University

# 💻 Internships
- <img src="../images/HH.png" alt="TJU Logo" style="zoom:25%;" /> **2026.05 - now**, <a href='https://www.happyhorse.com/'>HappyHorse Team</a>, Alibaba Token Foundry (T-star intern)
  - *Development of the next-generation Happy Horse series*
- <img src="../images/kling.png" alt="TJU Logo" style="zoom:25%;" /> **2026.01 - 2026.05**, <a href='https://klingai.com/global/'>Kling Team</a>, Kuaishou
  - *Autoregressive Video Generation; World Model*
<!-- - **2021.08 - 2022.04**, <a href='http://fi.ee.tsinghua.edu.cn'>Fib-Lab</a>, Tsinghua University -->


# 📃 Publications

<div class="pub-list">
  <div class="pub-item">
    <div class="pub-title-row">
      <span class="pub-title">DUET: A Diversity-Quality Duet of Distillation Experts for Two-Step Video Generation</span>
      <span class="pub-links">
        <a href="https://arxiv.org/abs/2608.09637" title="Paper" aria-label="Paper"><i class="ai ai-arxiv"></i></a>
      </span>
    </div>
    <div class="pub-authors"><strong>Zian Li</strong>, Litong Gong, Borui Liao, Pengfei Liu, Xinyu Wang, Xinyuan Wei, Yifan Gao, Tiezheng Ge, Muhan Zhang</div>
  </div>

  <div class="pub-item">
    <div class="pub-title-row">
      <span class="pub-title">CanvasMAR: Improving Masked Autoregressive Video Generation With Canvas</span>
      <span class="pub-venue">NeurIPS 2026</span>
      <span class="pub-links">
        <a href="https://arxiv.org/abs/2510.13669" title="Paper" aria-label="Paper"><i class="ai ai-arxiv"></i></a>
      </span>
    </div>
    <div class="pub-authors"><strong>Zian Li</strong>, Muhan Zhang</div>
  </div>

  <div class="pub-item">
    <div class="pub-title-row">
      <span class="pub-title">Toward Better Geometric Representations for Molecule Generative Models</span>
      <span class="pub-venue">NeurIPS 2026</span>
      <span class="pub-links">
        <a href="https://arxiv.org/abs/2605.07693" title="Paper" aria-label="Paper"><i class="ai ai-arxiv"></i></a>
      </span>
    </div>
    <div class="pub-authors">Shaoheng Yan<sup>&#42;</sup>, <strong>Zian Li</strong><sup>&#42;</sup>, Cai Zhou, Qiaojing Huang, Kai Liu, Muhan Zhang</div>
  </div>

  <div class="pub-item">
    <div class="pub-title-row">
      <span class="pub-title">FlashMol: High-Quality Molecule Generation in as Few as Four Steps</span>
      <span class="pub-venue">NeurIPS 2026</span>
      <span class="pub-links">
        <a href="https://arxiv.org/abs/2605.07020" title="Paper" aria-label="Paper"><i class="ai ai-arxiv"></i></a>
        <a href="https://github.com/MuLabPKU/FlashMol" title="Code" aria-label="Code"><i class="fab fa-github"></i></a>
      </span>
    </div>
    <div class="pub-authors">Xinyuan Wei<sup>&#42;</sup>, <strong>Zian Li</strong><sup>&#42;</sup>, Shaoheng Yan, Cai Zhou, Muhan Zhang</div>
  </div>

  <div class="pub-item">
    <div class="pub-title-row">
      <span class="pub-title">In-Parameter Learning: Why Lifelong AI Systems Need More Than Longer Context</span>
      <span class="pub-links">
        <a href="https://github.com/MuLabPKU/In-Parameter-Learning/blob/main/Beyond_longer_context.pdf" title="Paper" aria-label="Paper"><i class="far fa-file-pdf"></i></a>
        <a href="https://github.com/MuLabPKU/In-Parameter-Learning" title="Code" aria-label="Code"><i class="fab fa-github"></i></a>
      </span>
    </div>
    <div class="pub-authors">Yiding Wang<sup>&#42;</sup>, Haotong Yang<sup>&#42;</sup>, Pingzhi Tang<sup>&#42;</sup>, ..., <strong>Zian Li</strong>, ..., Xing Sun<sup>&#8224;</sup>, Muhan Zhang<sup>&#8224;&#8225;</sup></div>
  </div>

  <div class="pub-item">
    <div class="pub-title-row">
      <span class="pub-title">SubjectAnchor: Subject-Aware Memory-to-Video for Multi-Shot Storytelling</span>
      <span class="pub-venue">ACMMM 2026</span>
    </div>
    <div class="pub-authors">Xinyu Wang, Huafeng Shi, <strong>Zian Li</strong>, Yan Zhou, Xiaoqiang Liu, Yue Ma, Pengfei Wan</div>
  </div>

  <div class="pub-item">
    <div class="pub-title-row">
      <span class="pub-title">Rethinking Diffusion Models with Symmetries through Canonicalization with Applications to Molecular Graph Generation</span>
      <span class="pub-links">
        <a href="https://arxiv.org/abs/2602.15022" title="Paper" aria-label="Paper"><i class="ai ai-arxiv"></i></a>
      </span>
    </div>
    <div class="pub-authors">Cai Zhou, Zijie Chen, <strong>Zian Li</strong>, Jike Wang, Kaiyi Jiang, Pan Li, Rose Yu, Muhan Zhang, Stephen Bates, Tommi Jaakkola</div>
  </div>

  <div class="pub-item">
    <div class="pub-title-row">
      <span class="pub-title">GeoRecon: Graph-Level Representation Learning for 3D Molecules via Reconstruction-Based Pretraining</span>
      <span class="pub-venue">ICML 2026 GenBio Workshop</span>
      <span class="pub-links">
        <a href="https://arxiv.org/abs/2506.13174" title="Paper" aria-label="Paper"><i class="ai ai-arxiv"></i></a>
      </span>
    </div>
    <div class="pub-authors">Shaoheng Yan, <strong>Zian Li</strong>, Muhan Zhang</div>
  </div>

  <div class="pub-item">
    <div class="pub-title-row">
      <span class="pub-title">Geometric Representation Condition Improves Equivariant Molecule Generation</span>
      <span class="pub-venue">ICML 2025</span>
      <span class="pub-note">Spotlight</span>
      <span class="pub-links">
        <a href="https://arxiv.org/abs/2410.03655" title="Paper" aria-label="Paper"><i class="ai ai-arxiv"></i></a>
        <a href="https://github.com/GraphPKU/GeoRCG" title="Code" aria-label="Code"><i class="fab fa-github"></i></a>
      </span>
    </div>
    <div class="pub-authors"><strong>Zian Li</strong><sup>&#42;</sup>, Cai Zhou<sup>&#42;</sup>, Xiyuan Wang, Xingang Peng, Muhan Zhang</div>
  </div>

  <div class="pub-item">
    <div class="pub-title-row">
      <span class="pub-title">On the Completeness of Invariant Geometric Deep Learning Models</span>
      <span class="pub-venue">ICLR 2025</span>
      <span class="pub-links">
        <a href="https://arxiv.org/abs/2402.04836" title="Paper" aria-label="Paper"><i class="ai ai-arxiv"></i></a>
        <a href="https://github.com/GraphPKU/GeoNGNN" title="Code" aria-label="Code"><i class="fab fa-github"></i></a>
      </span>
    </div>
    <div class="pub-authors"><strong>Zian Li</strong>, Xiyuan Wang, Shijia Kang, Muhan Zhang</div>
  </div>

  <div class="pub-item">
    <div class="pub-title-row">
      <span class="pub-title">Is Distance Matrix Enough for Geometric Deep Learning?</span>
      <span class="pub-venue">NeurIPS 2023</span>
      <span class="pub-links">
        <a href="https://arxiv.org/pdf/2302.05743" title="Paper" aria-label="Paper"><i class="ai ai-arxiv"></i></a>
        <a href="https://github.com/GraphPKU/DisGNN" title="Code" aria-label="Code"><i class="fab fa-github"></i></a>
      </span>
    </div>
    <div class="pub-authors"><strong>Zian Li</strong>, Xiyuan Wang, Yinan Huang, Muhan Zhang</div>
  </div>
</div>

<script type="text/javascript" id="clustrmaps" src="//cdn.clustrmaps.com/map_v2.js?cl=9b6b48&w=a&t=n&d=-Yj2y8ATNu3_ZP_ifvFgzhjGrfygQELILQknou-AYAs&co=e3c887&w=400"></script>

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

<div style="display:flex; flex-wrap:wrap; align-items:center; justify-content:space-between; gap:1.5rem; margin-bottom:1.8rem; padding:1.2rem 0 0.4rem 0;">
  <div style="flex:1 1 560px; min-width:280px;">
    <h1 style="margin-bottom:0.4rem;">Zhiyang Deng</h1>
    <p style="font-size:1.05rem; line-height:1.8; margin-bottom:0.9rem;">
      I'm currently a Master's student in Computing at the National University of Singapore (NUS), and a Generative AI Research Intern at Riot Games. Previously, I worked as a Research Assistant at <a href="https://njusz.nju.edu.cn/main.htm">Nanjing University (Suzhou Campus)</a>. Before joining NUS, I received my bachelor's degree from <a href="https://www.hnu.edu.cn/">Hunan University</a>, where I was advised by <a href="http://csee.hnu.edu.cn/people/liruihui">Prof. Ruihui Li</a>.
    </p>
    <p style="font-size:1rem; line-height:1.8; margin-bottom:1rem;">
      My research interests lie in computer graphics and generative models, with a particular focus on reconstruction and generation of 3D digital humans.
    </p>

    <div style="display:flex; flex-wrap:wrap; gap:0.55rem; margin-top:0.6rem;">
      <span style="padding:0.28rem 0.75rem; border-radius:999px; background:#f3f6fb; border:1px solid #e2e8f0; font-size:0.92rem;">3D Digital Humans</span>
      <span style="padding:0.28rem 0.75rem; border-radius:999px; background:#f3f6fb; border:1px solid #e2e8f0; font-size:0.92rem;">Reconstruction</span>
      <span style="padding:0.28rem 0.75rem; border-radius:999px; background:#f3f6fb; border:1px solid #e2e8f0; font-size:0.92rem;">Generative Modeling</span>
      <span style="padding:0.28rem 0.75rem; border-radius:999px; background:#f3f6fb; border:1px solid #e2e8f0; font-size:0.92rem;">Computer Graphics</span>
    </div>
  </div>

  <div style="flex:0 1 260px; min-width:220px; display:flex; flex-direction:column; gap:0.9rem;">
    <div style="background:#ffffff; border:1px solid #e5e7eb; border-radius:14px; padding:0.9rem 1rem; box-shadow:0 2px 10px rgba(0,0,0,0.04); text-align:center;">
      <img src="/images/nus-logo.png" alt="NUS logo" style="max-width:100%; max-height:52px; object-fit:contain;">
      <div style="margin-top:0.45rem; font-size:0.92rem; color:#555;">National University of Singapore</div>
    </div>

    <div style="background:#ffffff; border:1px solid #e5e7eb; border-radius:14px; padding:0.9rem 1rem; box-shadow:0 2px 10px rgba(0,0,0,0.04); text-align:center;">
      <img src="/images/riot-logo.png" alt="Riot Games logo" style="max-width:100%; max-height:44px; object-fit:contain;">
      <div style="margin-top:0.45rem; font-size:0.92rem; color:#555;">Generative AI Research Intern</div>
    </div>
  </div>
</div>

<hr style="margin: 1.2rem 0 1.6rem 0;">

## 🔥 News
- *2026.01*: 🎉 One paper has been accepted by **ICASSP 2026**.
- *2025.12*: 🎉 I received an internship offer from **Riot Games Singapore**, starting in January 2026.
- *2025.11*: One paper was submitted to **CVPR 2026**, where I am listed as first author and co-first author.
- *2025.05*: 🎉 I received an offer for the **Master of Computing** program at the **National University of Singapore**.
- *2025.04*: Two papers were submitted to **ACM MM 2025**, where I am listed as first author and co-first author.
- *2024.11*: 🎉 I officially started working as a **Research Assistant** at **NJU(SZ)**. Feel free to reach out for a coffee chat!

## 📖 Education
- *2025.08 - 2027.01*, **Master of Computing**, National University of Singapore.
- *2021.09 - 2025.06*, **B.Sc. in Mathematics and Applied Mathematics**, Hunan University.

## 📝 Publications

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Under Review</div>
      <img src='images/GridACharacter_teaser.png' alt="Grid-A-Character teaser" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

**Grid-A-Character: Delving into Grid Condition Strategy for Unlocking Consistent and Controllable Character Generation**

**Zhiyang Deng**, Zhuofan Xiao, Jian Yang, Zhenyu Zhang†

[Project] [Paper] [Code]

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ICASSP 2026</div>
      <img src='images/MotionAvatar_teaser.png' alt="HM-Avatar teaser" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

**HM-Avatar: Towards Realistic Loose Garment Modeling with Hierarchical MLPs**

Hongyu Wang*, **Zhiyang Deng***, Wenzhe He, Xiaojun Chen, Ying Liu, Ruihui Li†

[Project] [Paper] [Code]

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Under Review</div>
      <img src='images/TextureAvatar_teaser.png' alt="TextureAvatar teaser" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

**TextureAvatar: Texture-Enhanced 3D Gaussian Splatting for Avatar Modeling from Monocular Videos**

**Zhiyang Deng**, Hongyu Wang, Xiaojun Chen, Ying Liu, Ruihui Li†

[Project] [Paper] [Code]

  </div>
</div>

## 🎖 Honors and Awards
- *2024.12* Hunan University 2023–2024 Individual Scholarship.
- *2023.12* Hunan University 2022–2023 Individual Scholarship.
- *2022.12* Hunan University 2021–2022 Individual Scholarship.

## 💼 Experience
- *2026.01 - Present*, **Generative AI Research Intern**, Riot Games.
- *2024.11 - 2025.12*, **Research Assistant**, NJU(SZ).
- *2024.10 - 2025.04*, **Research Intern**, PolyU.

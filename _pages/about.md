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

<style>
/* overall */
.page__content {
  font-size: 16px;
  line-height: 1.8;
}

.anchor {
  display: block;
  position: relative;
  top: -80px;
  visibility: hidden;
}

/* intro */
.profile-intro {
  font-size: 1.08rem;
  line-height: 1.9;
  color: #333;
  margin-bottom: 1rem;
}

.inline-logo {
  height: 1.12em;
  vertical-align: -0.16em;
  margin: 0 0.18em 0 0.18em;
}

/* section title */
.cv-section-title {
  margin-top: 2rem;
  margin-bottom: 1rem;
  font-size: 1.45rem;
  font-weight: 800;
}

/* card layout */
.cv-card {
  display: flex;
  align-items: flex-start;
  gap: 1.2rem;
  margin: 1rem 0 1.25rem 0;
  padding: 1rem 1.1rem;
  border-radius: 16px;
  background: #fafafa;
  border: 1px solid #e8e8e8;
  box-shadow: 0 3px 12px rgba(0,0,0,0.04);
}

.cv-card-logo {
  width: 118px;
  min-width: 118px;
  height: 118px;
  object-fit: contain;
  border-radius: 12px;
  background: #fff;
  padding: 0.6rem;
  border: 1px solid #efefef;
}

.cv-card-content {
  flex: 1;
}

.cv-card-org {
  font-size: 1.22rem;
  font-weight: 800;
  color: #111;
  margin-bottom: 0.15rem;
}

.cv-card-role {
  font-size: 1.03rem;
  font-weight: 700;
  color: #222;
  margin-bottom: 0.2rem;
}

.cv-card-time {
  font-size: 0.96rem;
  color: #666;
  margin-bottom: 0.65rem;
}

.cv-card-content ul {
  margin-top: 0.3rem;
  margin-bottom: 0;
}

.cv-card-content li {
  margin-bottom: 0.35rem;
  line-height: 1.75;
}

/* news */
.news-box {
  padding: 0.8rem 1rem;
  border-radius: 14px;
  background: #fcfcfc;
  border: 1px solid #ececec;
}

/* publication buttons */
.paper-links {
  margin-top: 0.6rem;
}

.paper-btn {
  display: inline-block;
  margin-right: 0.5rem;
  margin-top: 0.35rem;
  padding: 0.22rem 0.72rem;
  border-radius: 999px;
  border: 1px solid #d9d9d9;
  background: #ffffff;
  font-size: 0.92rem;
  font-weight: 600;
  color: #333 !important;
  text-decoration: none !important;
}

.paper-btn:hover {
  background: #f5f5f5;
  text-decoration: none !important;
}

/* paper box refinement */
.paper-box {
  margin-bottom: 1.35rem;
}

/* badge a bit cleaner */
.badge {
  display: inline-block;
  padding: 0.2rem 0.55rem;
  border-radius: 999px;
  font-size: 0.82rem;
  font-weight: 700;
}

/* mobile */
@media (max-width: 768px) {
  .cv-card {
    flex-direction: column;
  }

  .cv-card-logo {
    width: 92px;
    min-width: 92px;
    height: 92px;
  }
}
</style>

<span class='anchor' id='about-me'></span>

<div class="profile-intro">
  I am currently a Master’s student in Computing at
  <img class="inline-logo" src="/images/nus-logo.jpg" alt="NUS logo">
  <a href="https://www.nus.edu.sg/">National University of Singapore (NUS)</a>.
  At the same time, I am working as a Generative AI Research Intern at
  <img class="inline-logo" src="/images/riot-logo.png" alt="Riot Games logo">
  <a href="https://www.riotgames.com/">Riot Games</a>.
  Previously, I worked as a Research Assistant at
  <img class="inline-logo" src="/images/nju-logo.png" alt="Nanjing University logo">
  <a href="https://njusz.nju.edu.cn/main.htm">Nanjing University (Suzhou Campus)</a>.
  Before joining NUS, I received my bachelor’s degree from
  <img class="inline-logo" src="/images/hnu-logo.png" alt="Hunan University logo">
  <a href="https://www.hnu.edu.cn/">Hunan University</a>.
</div>

<div class="profile-intro" style="margin-top:-0.2rem; margin-bottom:1.5rem;">
  My research interests lie in computer graphics and generative models, with a particular focus on 3D digital human reconstruction and generation.
</div>

## 🔥 News

<div class="news-box">

- *2026.01*: 🎉 One paper has been accepted by **ICASSP 2026**.
- *2025.12*: 🎉 I received an internship offer from **Riot Games Singapore**, starting in January 2026.
- *2025.11*: One paper was submitted to **CVPR 2026**, where I am listed as first author and co-first author.
- *2025.05*: 🎉 I received an offer for the **Master of Computing** program at the **National University of Singapore**.
- *2025.04*: Two papers were submitted to **ACM MM 2025**, where I am listed as first author and co-first author.
- *2024.11*: 🎉 I officially started working as a **Research Assistant** at **NJU(SZ)**. Feel free to reach out for a coffee chat!

</div>

<h2 class="cv-section-title">📖 Education</h2>

<div class="cv-card">
  <img class="cv-card-logo" src="/images/nus-logo.jpg" alt="NUS logo">
  <div class="cv-card-content">
    <div class="cv-card-org">National University of Singapore</div>
    <div class="cv-card-role">Master of Computing</div>
    <div class="cv-card-time">Aug. 2025 – Jan. 2027</div>
    <ul>
      <li>Currently pursuing a Master’s degree in Computing.</li>
      <li>Research focus: computer graphics, generative modeling, and 3D digital humans.</li>
    </ul>
  </div>
</div>

<div class="cv-card">
  <img class="cv-card-logo" src="/images/hnu-logo.png" alt="Hunan University logo">
  <div class="cv-card-content">
    <div class="cv-card-org">Hunan University</div>
    <div class="cv-card-role">B.Sc. in Mathematics and Applied Mathematics</div>
    <div class="cv-card-time">Sep. 2021 – Jun. 2025</div>
    <ul>
      <li>Completed undergraduate training in mathematics and applied mathematics.</li>
      <li>Built research experience in graphics and related computational methods during this period.</li>
    </ul>
  </div>
</div>

<h2 class="cv-section-title">💼 Experience</h2>

<div class="cv-card">
  <img class="cv-card-logo" src="/images/riot-logo.png" alt="Riot Games logo">
  <div class="cv-card-content">
    <div class="cv-card-org">Riot Games</div>
    <div class="cv-card-role">Generative AI Research Intern</div>
    <div class="cv-card-time">Jan. 2026 – Present</div>
    <ul>
      <li>Work on generative AI research and development for image generation and editing related tasks.</li>
      <li>Explore practical research problems and system-level applications of generative models.</li>
    </ul>
  </div>
</div>

<div class="cv-card">
  <img class="cv-card-logo" src="/images/nju-logo.png" alt="Nanjing University logo">
  <div class="cv-card-content">
    <div class="cv-card-org">Nanjing University (Suzhou Campus)</div>
    <div class="cv-card-role">Research Assistant</div>
    <div class="cv-card-time">Nov. 2024 – Dec. 2025</div>
    <ul>
      <li>Worked on research projects related to computer graphics and 3D human modeling.</li>
      <li>Contributed to experiments, implementation, and paper writing.</li>
    </ul>
  </div>
</div>

<div class="cv-card">
  <img class="cv-card-logo" src="/images/polyu-logo.png" alt="PolyU logo">
  <div class="cv-card-content">
    <div class="cv-card-org">The Hong Kong Polytechnic University</div>
    <div class="cv-card-role">Research Intern</div>
    <div class="cv-card-time">Oct. 2024 – Apr. 2025</div>
    <ul>
      <li>Participated in research projects as a research intern.</li>
      <li>Focused on topics related to graphics and visual computing.</li>
    </ul>
  </div>
</div>

<h2 class="cv-section-title">📝 Publications</h2>

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

<div class="paper-links">
  <a class="paper-btn" href="#">Project</a>
  <a class="paper-btn" href="#">Paper</a>
  <a class="paper-btn" href="#">Code</a>
</div>

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

<div class="paper-links">
  <a class="paper-btn" href="#">Project</a>
  <a class="paper-btn" href="#">Paper</a>
  <a class="paper-btn" href="#">Code</a>
</div>

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

<div class="paper-links">
  <a class="paper-btn" href="#">Project</a>
  <a class="paper-btn" href="#">Paper</a>
  <a class="paper-btn" href="#">Code</a>
</div>

  </div>
</div>

<h2 class="cv-section-title">🎖 Honors and Awards</h2>

- *2024.12* Hunan University 2023–2024 Individual Scholarship.
- *2023.12* Hunan University 2022–2023 Individual Scholarship.
- *2022.12* Hunan University 2021–2022 Individual Scholarship.

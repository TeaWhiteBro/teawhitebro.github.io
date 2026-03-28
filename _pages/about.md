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
.page__content {
  font-size: 16px;
  line-height: 1.85;
}

/* intro */
.profile-intro {
  font-size: 1.06rem;
  line-height: 1.9;
  color: #333;
  margin-bottom: 1rem;
}

.inline-logo {
  height: 1.08em;
  vertical-align: -0.14em;
  margin: 0 0.16em;
}

/* section title */
.cv-section-title {
  margin-top: 2rem;
  margin-bottom: 0.9rem;
  font-size: 1.45rem;
  font-weight: 800;
}

/* news */
.news-panel {
  background: #fcfcfc;
  border: 1px solid #e9e9e9;
  border-radius: 14px;
  padding: 0.9rem 1.15rem;
  margin-bottom: 1.8rem;
}

.news-list {
  margin: 0;
  padding-left: 1.25rem;
}

.news-list li {
  margin: 0.45rem 0;
  line-height: 1.85;
}

/* entry card */
.entry-card {
  display: grid;
  grid-template-columns: 90px 1fr;
  gap: 1rem;
  align-items: start;
  margin: 0.95rem 0 1.1rem 0;
  padding: 1rem 1.1rem;
  border: 1px solid #e8e8e8;
  border-radius: 14px;
  background: #fff;
  box-shadow: 0 2px 8px rgba(0,0,0,0.03);
}

.entry-logo-wrap {
  width: 90px;
  height: 90px;
  border-radius: 12px;
  background: #fafafa;
  border: 1px solid #efefef;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
}

.entry-logo {
  width: 72%;
  height: 72%;
  object-fit: contain;
}

/* 对横版 logo 稍微放大一点 */
.entry-logo-wide {
  width: 82%;
  height: 56%;
  object-fit: contain;
}

.entry-title {
  font-size: 1.22rem;
  font-weight: 800;
  color: #111;
  margin-bottom: 0.2rem;
}

.entry-subtitle {
  font-size: 1.02rem;
  font-weight: 700;
  color: #222;
  margin-bottom: 0.15rem;
}

.entry-time {
  font-size: 0.95rem;
  color: #666;
  margin-bottom: 0.55rem;
}

.entry-desc {
  margin: 0;
  padding-left: 1.15rem;
}

.entry-desc li {
  margin-bottom: 0.32rem;
  line-height: 1.8;
}

/* publication buttons */
.paper-links {
  margin-top: 0.55rem;
}

.paper-btn {
  display: inline-block;
  margin-right: 0.45rem;
  margin-top: 0.35rem;
  padding: 0.2rem 0.72rem;
  border-radius: 999px;
  border: 1px solid #dddddd;
  background: #fff;
  font-size: 0.9rem;
  font-weight: 600;
  color: #333 !important;
  text-decoration: none !important;
}

.paper-btn:hover {
  background: #f6f6f6;
  text-decoration: none !important;
}

@media (max-width: 768px) {
  .entry-card {
    grid-template-columns: 1fr;
  }

  .entry-logo-wrap {
    width: 78px;
    height: 78px;
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

<div class="news-panel">
  <ul class="news-list">
    <li><strong>2026.01</strong>: 🎉 One paper has been accepted by <strong>ICASSP 2026</strong>.</li>
    <li><strong>2025.12</strong>: 🎉 I received an internship offer from <strong>Riot Games Singapore</strong>, starting in January 2026.</li>
    <li><strong>2025.11</strong>: One paper was submitted to <strong>CVPR 2026</strong>, where I am listed as first author and co-first author.</li>
    <li><strong>2025.05</strong>: 🎉 I received an offer for the <strong>Master of Computing</strong> program at the <strong>National University of Singapore</strong>.</li>
    <li><strong>2025.04</strong>: Two papers were submitted to <strong>ACM MM 2025</strong>, where I am listed as first author and co-first author.</li>
    <li><strong>2024.11</strong>: 🎉 I officially started working as a <strong>Research Assistant</strong> at <strong>NJU(SZ)</strong>. Feel free to reach out for a coffee chat!</li>
  </ul>
</div>

<h2 class="cv-section-title">📖 Education</h2>

<div class="entry-card">
  <div class="entry-logo-wrap">
    <img class="entry-logo entry-logo-wide" src="/images/nus-logo.jpg" alt="NUS logo">
  </div>
  <div>
    <div class="entry-title">National University of Singapore</div>
    <div class="entry-subtitle">Master of Computing</div>
    <div class="entry-time">Aug. 2025 – Jan. 2027</div>
    <ul class="entry-desc">
      <li>Currently pursuing a Master’s degree in Computing.</li>
      <li>Research focus: computer graphics, generative modeling, and 3D digital humans.</li>
    </ul>
  </div>
</div>

<div class="entry-card">
  <div class="entry-logo-wrap">
    <img class="entry-logo" src="/images/hnu-logo.png" alt="Hunan University logo">
  </div>
  <div>
    <div class="entry-title">Hunan University</div>
    <div class="entry-subtitle">B.Sc. in Mathematics and Applied Mathematics</div>
    <div class="entry-time">Sep. 2021 – Jun. 2025</div>
    <ul class="entry-desc">
      <li>Completed undergraduate training in mathematics and applied mathematics.</li>
      <li>Built research experience in graphics and related computational methods during this period.</li>
    </ul>
  </div>
</div>

<h2 class="cv-section-title">💼 Experience</h2>

<div class="entry-card">
  <div class="entry-logo-wrap">
    <img class="entry-logo" src="/images/riot-logo.png" alt="Riot Games logo">
  </div>
  <div>
    <div class="entry-title">Riot Games</div>
    <div class="entry-subtitle">Generative AI Research Intern</div>
    <div class="entry-time">Jan. 2026 – Present</div>
    <ul class="entry-desc">
      <li>Work on generative AI research and development for image generation and editing related tasks.</li>
      <li>Explore practical research problems and system-level applications of generative models.</li>
    </ul>
  </div>
</div>

<div class="entry-card">
  <div class="entry-logo-wrap">
    <img class="entry-logo" src="/images/nju-logo.png" alt="Nanjing University logo">
  </div>
  <div>
    <div class="entry-title">Nanjing University (Suzhou Campus)</div>
    <div class="entry-subtitle">Research Assistant</div>
    <div class="entry-time">Nov. 2024 – Dec. 2025</div>
    <ul class="entry-desc">
      <li>Worked on research projects related to computer graphics and 3D human modeling.</li>
      <li>Contributed to experiments, implementation, and paper writing.</li>
    </ul>
  </div>
</div>

<div class="entry-card">
  <div class="entry-logo-wrap">
    <img class="entry-logo entry-logo-wide" src="/images/polyu-logo.png" alt="PolyU logo">
  </div>
  <div>
    <div class="entry-title">The Hong Kong Polytechnic University</div>
    <div class="entry-subtitle">Research Intern</div>
    <div class="entry-time">Oct. 2024 – Apr. 2025</div>
    <ul class="entry-desc">
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

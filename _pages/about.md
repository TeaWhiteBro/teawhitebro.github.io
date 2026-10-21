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

.inline-logo-wide {
  height: 0.9em;
  vertical-align: -0.05em;
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

/* section anchors: keep headings clear of the sticky top bar */
.page__content h2[id] {
  scroll-margin-top: 4rem;
}

/* video thumbnail, sized like the image thumbnails */
.paper-box .paper-box-image video {
  max-width: 400px;
  height: auto;
}

/* publication thumbnails: rounded corners, softer shadow */
.paper-box .paper-box-image img,
.paper-box .paper-box-image video {
  border-radius: 8px;
  box-shadow: 0 2px 12px rgba(0, 0, 0, 0.12);
}

.paper-box .badge {
  border-radius: 4px;
}

/* pinned news item */
.news-list li.news-pinned {
  list-style: none;
  margin: 0 0 0.7rem -1.25rem;
  padding: 0.5rem 0.85rem;
  background: #fff8ec;
  border: 1px solid #f3e0bb;
  border-radius: 10px;
}

.news-pin {
  display: inline-block;
  margin-right: 0.35rem;
  padding: 0 0.55rem;
  border-radius: 999px;
  background: #ffe8bd;
  color: #8a5a00;
  font-size: 0.78rem;
  font-weight: 700;
  line-height: 1.7;
}

/* marker legend under the Publications heading */
.pub-note {
  margin: -0.3rem 0 0.4rem;
  font-size: 0.88rem;
  color: #777;
}

/* buttons whose link is not public yet */
.paper-btn.is-soon {
  color: #aaa !important;
  border-color: #e8e8e8;
  cursor: default;
}

.paper-btn.is-soon:hover {
  background: #fff;
}
</style>

<span class='anchor' id='about-me'></span>

<div class="profile-intro">
  I am currently a Master’s student in Computing at
  <img class="inline-logo" src="/images/nus-logo.jpg" alt="NUS logo">
  <a href="https://www.nus.edu.sg/">National University of Singapore (NUS)</a>.
  At the same time, I am working as a World Model Research Intern at
  <img class="inline-logo inline-logo-wide" src="/images/Tencent_EN.png" alt="Tencent logo">
  <a href="https://www.tencent.com/">Tencent</a>, supervised by Dr. <a href="https://jinyeying.github.io/">Yeying Jin</a>.
  Previously, I worked as a Generative AI Research Intern at
  <img class="inline-logo" src="/images/riot-logo.png" alt="Riot Games logo">
  <a href="https://www.riotgames.com/">Riot Games</a>, and as a Research Assistant at
  <img class="inline-logo" src="/images/nju-logo.png" alt="Nanjing University logo">
  <a href="https://njusz.nju.edu.cn/main.htm">Nanjing University (Suzhou Campus)</a>, supervised by Prof. <a href="https://jessezhang92.github.io/index.html">Zhenyu Zhang</a>.
  Before joining NUS, I received my bachelor’s degree from
  <img class="inline-logo" src="/images/hnu-logo.png" alt="Hunan University logo">
  <a href="https://www.hnu.edu.cn/">Hunan University</a>, mentored by Prof. <a href="https://csee.hnu.edu.cn/people/liruihui">Ruihui Li</a>.
</div>

<div class="profile-intro" style="margin-top:-0.2rem; margin-bottom:1.5rem;">
  My research interests lie in <strong>image generation</strong>, <strong>video generation</strong>, <strong>world models</strong>, and <strong>3D generation</strong>.
</div>

<h2 class="cv-section-title" id="-news">🔥 News</h2>

<div class="news-panel">
  <ul class="news-list">
    <li class="news-pinned"><span class="news-pin">📌 Pinned</span> <strong>2027.01</strong>: I will be joining <strong>Riot Games Singapore</strong> as a full-time <strong>Machine Learning Engineer and Researcher</strong>.</li>
    <li><strong>2026.10</strong>: 🚀 <a href="https://jimntu.github.io/gamedirector/"><strong>GameDirector</strong></a>, <a href="https://teawhite.cn/ActionRoPE/"><strong>ActionRoPE</strong></a>, and <a href="https://teawhite.cn/GameCrafter/"><strong>GameCrafter</strong></a> are released.</li>
    <li><strong>2026.08</strong>: 🚀 <a href="https://teawhite.cn/WorldMind/"><strong>WorldMind</strong></a> is released.</li>
    <li><strong>2026.05</strong>: 🎉 I started a new internship as a <strong>World Model Research Intern</strong> at <strong>Tencent</strong>.</li>
    <li><strong>2026.01</strong>: 🎉 One paper has been accepted by <strong>ICASSP 2026</strong>.</li>
    <li><strong>2025.12</strong>: 🎉 I received an internship offer from <strong>Riot Games Singapore</strong>, starting in January 2026.</li>
    <li><strong>2025.05</strong>: 🎉 I received an offer for the <strong>Master of Computing</strong> program at the <strong>National University of Singapore</strong>.</li>
    <li><strong>2024.11</strong>: 🎉 I officially started working as a <strong>Research Assistant</strong> at <strong>NJU(SZ)</strong>. Feel free to reach out for a coffee chat!</li>
  </ul>
</div>

<h2 class="cv-section-title" id="-education">📖 Education</h2>

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
      <li>Research focus: image generation, video generation, world models, and 3D generation.</li>
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

<h2 class="cv-section-title" id="-experience">💼 Experience</h2>

<div class="entry-card">
  <div class="entry-logo-wrap">
    <img class="entry-logo entry-logo-wide" src="/images/Tencent_EN.png" alt="Tencent logo">
  </div>
  <div>
    <div class="entry-title">Tencent</div>
    <div class="entry-subtitle">World Model Research Intern</div>
    <div class="entry-time">May 2026 – Present</div>
    <ul class="entry-desc">
      <li>Work on world model related research topics.</li>
    </ul>
  </div>
</div>

<div class="entry-card">
  <div class="entry-logo-wrap">
    <img class="entry-logo" src="/images/riot-logo.png" alt="Riot Games logo">
  </div>
  <div>
    <div class="entry-title">Riot Games</div>
    <div class="entry-subtitle">Generative AI Research Intern</div>
    <div class="entry-time">Jan. 2026 – May 2026</div>
    <ul class="entry-desc">
      <li>Worked on generative AI research and development for image generation and editing related tasks.</li>
      <li>Explored practical research problems and system-level applications of generative models.</li>
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

<h2 class="cv-section-title" id="-publications">📝 Publications</h2>

<p class="pub-note">* Equal contribution &nbsp;&nbsp; † Corresponding author</p>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Under Review</div>
      <img src='images/GameCrafter_teaser_thumb.jpg' alt="GameCrafter teaser" width="100%" loading="lazy" decoding="async">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

**GameCrafter: An Agentic Framework for Multi-Gameplay Game World Generation**

**Zhiyang Deng**\*, Xiyao Deng\*, Yeying Jin

<div class="paper-links">
  <a class="paper-btn" href="https://teawhite.cn/GameCrafter/">Project</a>
  <span class="paper-btn is-soon" title="Coming soon">Paper</span>
  <span class="paper-btn is-soon" title="Coming soon">Code</span>
</div>

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Under Review</div>
      <img src='images/ActionRoPE_method_thumb.jpg' alt="ActionRoPE method overview" width="100%" loading="lazy" decoding="async">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

**ActionRoPE: Action as Coordinates for Spatially Consistent Control in Planar-Camera Game World Models**

**Zhiyang Deng**, Yuzhe Wu, Zijun Lin, Yeying Jin

<div class="paper-links">
  <a class="paper-btn" href="https://teawhite.cn/ActionRoPE/">Project</a>
  <a class="paper-btn" href="https://arxiv.org/abs/2610.25861">Paper</a>
  <span class="paper-btn is-soon" title="Coming soon">Code</span>
</div>

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Under Review</div>
      <img src='images/GameDirector_method_thumb.jpg' alt="GameDirector framework" width="100%" loading="lazy" decoding="async">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

**GameDirector: Decoupling Gameplay Logic from Rendering for Player-Configurable Game World Models**

Zijun Lin\*, **Zhiyang Deng**\*, Yuzhe Wu, Bihan Wen, Yeying Jin

<div class="paper-links">
  <a class="paper-btn" href="https://jimntu.github.io/gamedirector/">Project</a>
  <a class="paper-btn" href="https://arxiv.org/abs/2609.25652">Paper</a>
  <a class="paper-btn" href="https://github.com/Jimntu/GameDirector_code">Code</a>
</div>

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Under Review</div>
      <video src='images/WorldMind_promo.mp4' poster='images/WorldMind_promo_poster.jpg' width="100%" muted loop playsinline preload="none" data-play-in-view aria-label="WorldMind promo video"></video>
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

**WorldMind: Decoupled Game World Model for State-Aware NPC Behavior**

**Zhiyang Deng**, Boran Zhang, Danze Chen, Yeying Jin

<div class="paper-links">
  <a class="paper-btn" href="https://teawhite.cn/WorldMind/">Project</a>
  <a class="paper-btn" href="https://arxiv.org/abs/2608.21439">Paper</a>
  <a class="paper-btn" href="https://github.com/TeaWhiteBro/WorldMind">Code</a>
</div>

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Under Review</div>
      <img src='images/GridACharacter_teaser_thumb.jpg' alt="Grid-A-Character teaser" width="100%" loading="lazy" decoding="async">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

**Grid-A-Character: Delving into Grid Condition Strategy for Unlocking Consistent and Controllable Character Generation**

**Zhiyang Deng**\*, Zhuofan Xiao\*, Jian Yang, Zhenyu Zhang†

<div class="paper-links">
  <span class="paper-btn is-soon" title="Coming soon">Project</span>
  <span class="paper-btn is-soon" title="Coming soon">Paper</span>
  <span class="paper-btn is-soon" title="Coming soon">Code</span>
</div>

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ICASSP 2026</div>
      <img src='images/MotionAvatar_teaser_thumb.jpg' alt="HM-Avatar teaser" width="100%" loading="lazy" decoding="async">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

**HM-Avatar: Towards Realistic Loose Garment Modeling with Hierarchical MLPs**

Hongyu Wang\*, **Zhiyang Deng**\*, Wenzhe He, Xiaojun Chen, Ying Liu, Ruihui Li†

<div class="paper-links">
  <span class="paper-btn is-soon" title="Coming soon">Project</span>
  <a class="paper-btn" href="https://ieeexplore.ieee.org/abstract/document/11462401">Paper</a>
  <span class="paper-btn is-soon" title="Coming soon">Code</span>
</div>

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Under Review</div>
      <img src='images/TextureAvatar_teaser_thumb.jpg' alt="TextureAvatar teaser" width="100%" loading="lazy" decoding="async">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

**TextureAvatar: Texture-Enhanced 3D Gaussian Splatting for Avatar Modeling from Monocular Videos**

**Zhiyang Deng**, Hongyu Wang, Xiaojun Chen, Ying Liu, Ruihui Li†

<div class="paper-links">
  <span class="paper-btn is-soon" title="Coming soon">Project</span>
  <span class="paper-btn is-soon" title="Coming soon">Paper</span>
  <span class="paper-btn is-soon" title="Coming soon">Code</span>
</div>

  </div>
</div>

<h2 class="cv-section-title" id="-honors-and-awards">🎖 Honors and Awards</h2>

- *2024.12* Hunan University 2023–2024 Individual Scholarship.
- *2023.12* Hunan University 2022–2023 Individual Scholarship.
- *2022.12* Hunan University 2021–2022 Individual Scholarship.

<script>
(function () {
  var videos = document.querySelectorAll('video[data-play-in-view]');
  if (!videos.length) return;
  if (!('IntersectionObserver' in window)) {
    videos.forEach(function (v) { v.play().catch(function () {}); });
    return;
  }
  var observer = new IntersectionObserver(function (entries) {
    entries.forEach(function (e) {
      if (e.isIntersecting) { e.target.play().catch(function () {}); }
      else { e.target.pause(); }
    });
  }, { rootMargin: '200px 0px' });
  videos.forEach(function (v) { observer.observe(v); });
})();
</script>

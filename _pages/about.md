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
  grid-template-columns: 80px 1fr;
  gap: 1.15rem;
  align-items: start;
  margin: 0.8rem 0 0.95rem 0;
  padding: 1rem 1.2rem;
  border: 1px solid #e8e8e8;
  border-radius: 14px;
  background: #fff;
  box-shadow: 0 2px 8px rgba(0,0,0,0.03);
}

.entry-logo-wrap {
  width: 80px;
  height: 80px;
  border-radius: 12px;
  background: #fff;
  border: 1px solid #ececec;
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
  font-size: 1.2rem;
  font-weight: 800;
  color: #111;
  line-height: 1.4;
  margin-bottom: 0.1rem;
}

.entry-subtitle {
  font-size: 1rem;
  font-weight: 600;
  color: #333;
  line-height: 1.45;
  margin-bottom: 0.45rem;
}

.entry-time {
  font-size: 0.92rem;
  color: #777;
  white-space: nowrap;
  font-variant-numeric: tabular-nums;
}

.entry-desc {
  margin: 0;
  padding-left: 1.15rem;
}

.entry-desc li {
  margin-bottom: 0.25rem;
  line-height: 1.75;
}

/* wide screens: dates sit on the title line, right-aligned */
.entry-card > div:last-child {
  display: grid;
  grid-template-columns: 1fr auto;
  column-gap: 1rem;
  align-items: baseline;
}

.entry-card .entry-title { grid-area: 1 / 1; }
.entry-card .entry-time { grid-area: 1 / 2; }
.entry-card .entry-subtitle { grid-area: 2 / 1 / 3 / 3; }
.entry-card .entry-desc { grid-area: 3 / 1 / 4 / 3; }

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
  /* phones: small logo beside the heading lines, bullets full width below */
  .entry-card {
    grid-template-columns: 48px 1fr;
    column-gap: 0.85rem;
    row-gap: 0;
    padding: 0.9rem 1rem;
  }

  .entry-logo-wrap {
    width: 48px;
    height: 48px;
    border-radius: 10px;
    grid-area: 1 / 1 / 4 / 2;
  }

  .entry-card > div:last-child {
    display: contents;
  }

  .entry-card .entry-title { grid-area: 1 / 2; }
  .entry-card .entry-subtitle { grid-area: 2 / 2; margin-bottom: 0.1rem; }
  .entry-card .entry-time { grid-area: 3 / 2; white-space: normal; }
  .entry-card .entry-desc { grid-area: 4 / 1 / 5 / 3; margin-top: 0.55rem; }
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

.paper-box .badge.badge-accepted {
  background-color: #1f7a3a;
}

.paper-box .badge.badge-arxiv {
  background-color: #b31b1b;
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

/* small brand icons inside the paper buttons */
.paper-btn .btn-icon {
  width: 1em;
  height: 1em;
  margin-right: 0.35em;
  vertical-align: -0.14em;
  fill: currentColor;
}
</style>

<div class="icon-sprite" aria-hidden="true" style="position:absolute;width:0;height:0;overflow:hidden"><svg xmlns="http://www.w3.org/2000/svg"><symbol id="ic-arxiv" viewBox="0 0 24 24"><path d="M3.8423 0a1.0037 1.0037 0 0 0-.922.6078c-.1536.3687-.0438.6275.2938 1.1113l6.9185 8.3597-1.0223 1.1058a1.0393 1.0393 0 0 0 .003 1.4229l1.2292 1.3135-5.4391 6.4444c-.2803.299-.4538.823-.2971 1.1986a1.0253 1.0253 0 0 0 .9585.635.9133.9133 0 0 0 .6891-.3405l5.783-6.126 7.4902 8.0051a.8527.8527 0 0 0 .6835.2597.9575.9575 0 0 0 .8777-.6138c.1577-.377-.017-.7502-.306-1.1407l-7.0518-8.3418 1.0632-1.13a.9626.9626 0 0 0 .0089-1.3165L4.6336.4639s-.3733-.4535-.768-.463zm0 .272h.0166c.2179.0052.4874.2715.5644.3639l.005.006.0052.0055 10.169 10.9905a.6915.6915 0 0 1-.0072.945l-1.0666 1.133-1.4982-1.7724-8.5994-10.39c-.3286-.472-.352-.6183-.2592-.841a.7307.7307 0 0 1 .6704-.4401Zm14.341 1.5701a.877.877 0 0 0-.6554.2418l-5.6962 6.1584 1.6944 1.8319 5.3089-6.5138c.3251-.4335.479-.6603.3247-1.0292a1.1205 1.1205 0 0 0-.9763-.689zm-7.6557 12.2823 1.3186 1.4135-5.7864 6.1295a.6494.6494 0 0 1-.4959.26.7516.7516 0 0 1-.706-.4669c-.1119-.2682.0359-.6864.2442-.9083l.0051-.0055.0047-.0055z"></path></symbol><symbol id="ic-github" viewBox="0 0 24 24"><path d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"></path></symbol><symbol id="ic-hf" viewBox="0 0 24 24"><path d="M12.025 1.13c-5.77 0-10.449 4.647-10.449 10.378 0 1.112.178 2.181.503 3.185.064-.222.203-.444.416-.577a.96.96 0 0 1 .524-.15c.293 0 .584.124.84.284.278.173.48.408.71.694.226.282.458.611.684.951v-.014c.017-.324.106-.622.264-.874s.403-.487.762-.543c.3-.047.596.06.787.203s.31.313.4.467c.15.257.212.468.233.542.01.026.653 1.552 1.657 2.54.616.605 1.01 1.223 1.082 1.912.055.537-.096 1.059-.38 1.572.637.121 1.294.187 1.967.187.657 0 1.298-.063 1.921-.178-.287-.517-.44-1.041-.384-1.581.07-.69.465-1.307 1.081-1.913 1.004-.987 1.647-2.513 1.657-2.539.021-.074.083-.285.233-.542.09-.154.208-.323.4-.467a1.08 1.08 0 0 1 .787-.203c.359.056.604.29.762.543s.247.55.265.874v.015c.225-.34.457-.67.683-.952.23-.286.432-.52.71-.694.257-.16.547-.284.84-.285a.97.97 0 0 1 .524.151c.228.143.373.388.43.625l.006.04a10.3 10.3 0 0 0 .534-3.273c0-5.731-4.678-10.378-10.449-10.378M8.327 6.583a1.5 1.5 0 0 1 .713.174 1.487 1.487 0 0 1 .617 2.013c-.183.343-.762-.214-1.102-.094-.38.134-.532.914-.917.71a1.487 1.487 0 0 1 .69-2.803m7.486 0a1.487 1.487 0 0 1 .689 2.803c-.385.204-.536-.576-.916-.71-.34-.12-.92.437-1.103.094a1.487 1.487 0 0 1 .617-2.013 1.5 1.5 0 0 1 .713-.174m-10.68 1.55a.96.96 0 1 1 0 1.921.96.96 0 0 1 0-1.92m13.838 0a.96.96 0 1 1 0 1.92.96.96 0 0 1 0-1.92M8.489 11.458c.588.01 1.965 1.157 3.572 1.164 1.607-.007 2.984-1.155 3.572-1.164.196-.003.305.12.305.454 0 .886-.424 2.328-1.563 3.202-.22-.756-1.396-1.366-1.63-1.32q-.011.001-.02.006l-.044.026-.01.008-.03.024q-.018.017-.035.036l-.032.04a1 1 0 0 0-.058.09l-.014.025q-.049.088-.11.19a1 1 0 0 1-.083.116 1.2 1.2 0 0 1-.173.18q-.035.029-.075.058a1.3 1.3 0 0 1-.251-.243 1 1 0 0 1-.076-.107c-.124-.193-.177-.363-.337-.444-.034-.016-.104-.008-.2.022q-.094.03-.216.087-.06.028-.125.063l-.13.074q-.067.04-.136.086a3 3 0 0 0-.135.096 3 3 0 0 0-.26.219 2 2 0 0 0-.12.121 2 2 0 0 0-.106.128l-.002.002a2 2 0 0 0-.09.132l-.001.001a1.2 1.2 0 0 0-.105.212q-.013.036-.024.073c-1.139-.875-1.563-2.317-1.563-3.203 0-.334.109-.457.305-.454m.836 10.354c.824-1.19.766-2.082-.365-3.194-1.13-1.112-1.789-2.738-1.789-2.738s-.246-.945-.806-.858-.97 1.499.202 2.362c1.173.864-.233 1.45-.685.64-.45-.812-1.683-2.896-2.322-3.295s-1.089-.175-.938.647 2.822 2.813 2.562 3.244-1.176-.506-1.176-.506-2.866-2.567-3.49-1.898.473 1.23 2.037 2.16c1.564.932 1.686 1.178 1.464 1.53s-3.675-2.511-4-1.297c-.323 1.214 3.524 1.567 3.287 2.405-.238.839-2.71-1.587-3.216-.642-.506.946 3.49 2.056 3.522 2.064 1.29.33 4.568 1.028 5.713-.624m5.349 0c-.824-1.19-.766-2.082.365-3.194 1.13-1.112 1.789-2.738 1.789-2.738s.246-.945.806-.858.97 1.499-.202 2.362c-1.173.864.233 1.45.685.64.451-.812 1.683-2.896 2.322-3.295s1.089-.175.938.647-2.822 2.813-2.562 3.244 1.176-.506 1.176-.506 2.866-2.567 3.49-1.898-.473 1.23-2.037 2.16c-1.564.932-1.686 1.178-1.464 1.53s3.675-2.511 4-1.297c.323 1.214-3.524 1.567-3.287 2.405.238.839 2.71-1.587 3.216-.642.506.946-3.49 2.056-3.522 2.064-1.29.33-4.568 1.028-5.713-.624"></path></symbol><symbol id="ic-home" viewBox="0 0 24 24"><path d="M10 20v-6h4v6h5v-8h3L12 3 2 12h3v8z"></path></symbol><symbol id="ic-doc" viewBox="0 0 24 24"><path d="M14 2H6c-1.1 0-1.99.9-1.99 2L4 20c0 1.1.89 2 1.99 2H18c1.1 0 2-.9 2-2V8l-6-6zm2 16H8v-2h8v2zm0-4H8v-2h8v2zm-3-5V3.5L18.5 9H13z"></path></symbol></svg></div>

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
      <li>Mentored by Prof. <a href="https://csee.hnu.edu.cn/people/liruihui">Ruihui Li</a>.</li>
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
      <li>Research on world models for games, supervised by Dr. <a href="https://jinyeying.github.io/">Yeying Jin</a>.</li>
      <li>Projects: <a href="https://teawhite.cn/WorldMind/">WorldMind</a>, <a href="https://jimntu.github.io/gamedirector/">GameDirector</a>, <a href="https://teawhite.cn/ActionRoPE/">ActionRoPE</a>, and <a href="https://teawhite.cn/GameCrafter/">GameCrafter</a>.</li>
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
      <li>Supervised by Prof. <a href="https://jessezhang92.github.io/index.html">Zhenyu Zhang</a>.</li>
      <li>Worked on research projects related to computer graphics and 3D human modeling.</li>
      <li>Contributed to experiments, implementation, and paper writing.</li>
    </ul>
  </div>
</div>

<div class="entry-card">
  <div class="entry-logo-wrap">
    <img class="entry-logo" src="/images/polyu-emblem.png" alt="PolyU logo">
  </div>
  <div>
    <div class="entry-title">The Hong Kong Polytechnic University</div>
    <div class="entry-subtitle">Research Intern</div>
    <div class="entry-time">Oct. 2024 – Apr. 2025</div>
    <ul class="entry-desc">
      <li>Focused on topics related to graphics and visual computing.</li>
    </ul>
  </div>
</div>

<h2 class="cv-section-title" id="-publications">📝 Publications</h2>

<p class="pub-note">* Equal contribution &nbsp;&nbsp; † Corresponding author</p>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge badge-arxiv">arXiv 2026</div>
      <img src='images/GameCrafter_teaser_thumb.jpg' alt="GameCrafter teaser" width="100%" loading="lazy" decoding="async">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

**GameCrafter: An Agentic Framework for Multi-Gameplay Game World Generation**

**Zhiyang Deng**\*, Xiyao Deng\*, Yeying Jin

<div class="paper-links">
  <a class="paper-btn" href="https://teawhite.cn/GameCrafter/"><svg class="btn-icon" aria-hidden="true"><use href="#ic-home"></use></svg>Project</a>
  <span class="paper-btn is-soon" title="Coming soon"><svg class="btn-icon" aria-hidden="true"><use href="#ic-doc"></use></svg>Paper</span>
  <span class="paper-btn is-soon" title="Coming soon"><svg class="btn-icon" aria-hidden="true"><use href="#ic-github"></use></svg>Code</span>
</div>

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge badge-arxiv">arXiv 2026</div>
      <video src='images/ActionRoPE_promo.mp4' poster='images/ActionRoPE_promo_poster.jpg' width="100%" muted loop playsinline preload="none" data-play-in-view aria-label="ActionRoPE promo video"></video>
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

**ActionRoPE: Action as Coordinates for Spatially Consistent Control in Planar-Camera Game World Models**

**Zhiyang Deng**, Yuzhe Wu, Zijun Lin, Yeying Jin

<div class="paper-links">
  <a class="paper-btn" href="https://teawhite.cn/ActionRoPE/"><svg class="btn-icon" aria-hidden="true"><use href="#ic-home"></use></svg>Project</a>
  <a class="paper-btn" href="https://arxiv.org/abs/2610.25861"><svg class="btn-icon" aria-hidden="true"><use href="#ic-arxiv"></use></svg>arXiv</a>
  <a class="paper-btn" href="https://github.com/TeaWhiteBro/ActionRoPE"><svg class="btn-icon" aria-hidden="true"><use href="#ic-github"></use></svg>Code</a>
  <a class="paper-btn" href="https://huggingface.co/teawhite/ActionRoPE"><svg class="btn-icon" aria-hidden="true"><use href="#ic-hf"></use></svg>Model</a>
</div>

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge badge-arxiv">arXiv 2026</div>
      <video src='images/GameDirector_promo.mp4' poster='images/GameDirector_promo_poster.jpg' width="100%" muted loop playsinline preload="none" data-play-in-view aria-label="GameDirector promo video"></video>
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

**GameDirector: Decoupling Gameplay Logic from Rendering for Player-Configurable Game World Models**

Zijun Lin\*, **Zhiyang Deng**\*, Yuzhe Wu, Bihan Wen, Yeying Jin

<div class="paper-links">
  <a class="paper-btn" href="https://jimntu.github.io/gamedirector/"><svg class="btn-icon" aria-hidden="true"><use href="#ic-home"></use></svg>Project</a>
  <a class="paper-btn" href="https://arxiv.org/abs/2609.25652"><svg class="btn-icon" aria-hidden="true"><use href="#ic-arxiv"></use></svg>arXiv</a>
  <a class="paper-btn" href="https://github.com/Jimntu/GameDirector_code"><svg class="btn-icon" aria-hidden="true"><use href="#ic-github"></use></svg>Code</a>
</div>

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge badge-arxiv">arXiv 2026</div>
      <video src='images/WorldMind_promo.mp4' poster='images/WorldMind_promo_poster.jpg' width="100%" muted loop playsinline preload="none" data-play-in-view aria-label="WorldMind promo video"></video>
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

**WorldMind: Decoupled Game World Model for State-Aware NPC Behavior**

**Zhiyang Deng**, Boran Zhang, Danze Chen, Yeying Jin

<div class="paper-links">
  <a class="paper-btn" href="https://teawhite.cn/WorldMind/"><svg class="btn-icon" aria-hidden="true"><use href="#ic-home"></use></svg>Project</a>
  <a class="paper-btn" href="https://arxiv.org/abs/2608.21439"><svg class="btn-icon" aria-hidden="true"><use href="#ic-arxiv"></use></svg>arXiv</a>
  <a class="paper-btn" href="https://github.com/TeaWhiteBro/WorldMind"><svg class="btn-icon" aria-hidden="true"><use href="#ic-github"></use></svg>Code</a>
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
  <span class="paper-btn is-soon" title="Coming soon"><svg class="btn-icon" aria-hidden="true"><use href="#ic-home"></use></svg>Project</span>
  <span class="paper-btn is-soon" title="Coming soon"><svg class="btn-icon" aria-hidden="true"><use href="#ic-doc"></use></svg>Paper</span>
  <span class="paper-btn is-soon" title="Coming soon"><svg class="btn-icon" aria-hidden="true"><use href="#ic-github"></use></svg>Code</span>
</div>

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge badge-accepted">ICASSP 2026</div>
      <img src='images/MotionAvatar_teaser_thumb.jpg' alt="HM-Avatar teaser" width="100%" loading="lazy" decoding="async">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

**HM-Avatar: Towards Realistic Loose Garment Modeling with Hierarchical MLPs**

Hongyu Wang\*, **Zhiyang Deng**\*, Wenzhe He, Xiaojun Chen, Ying Liu, Ruihui Li†

<div class="paper-links">
  <span class="paper-btn is-soon" title="Coming soon"><svg class="btn-icon" aria-hidden="true"><use href="#ic-home"></use></svg>Project</span>
  <a class="paper-btn" href="https://ieeexplore.ieee.org/abstract/document/11462401"><svg class="btn-icon" aria-hidden="true"><use href="#ic-doc"></use></svg>Paper</a>
  <span class="paper-btn is-soon" title="Coming soon"><svg class="btn-icon" aria-hidden="true"><use href="#ic-github"></use></svg>Code</span>
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
  <span class="paper-btn is-soon" title="Coming soon"><svg class="btn-icon" aria-hidden="true"><use href="#ic-home"></use></svg>Project</span>
  <span class="paper-btn is-soon" title="Coming soon"><svg class="btn-icon" aria-hidden="true"><use href="#ic-doc"></use></svg>Paper</span>
  <span class="paper-btn is-soon" title="Coming soon"><svg class="btn-icon" aria-hidden="true"><use href="#ic-github"></use></svg>Code</span>
</div>

  </div>
</div>

<h2 class="cv-section-title" id="-honors-and-awards">🎖 Honors and Awards</h2>

<div class="news-panel">
  <ul class="news-list">
    <li><strong>2024.12</strong>: Hunan University 2023–2024 Individual Scholarship.</li>
    <li><strong>2023.12</strong>: Hunan University 2022–2023 Individual Scholarship.</li>
    <li><strong>2022.12</strong>: Hunan University 2021–2022 Individual Scholarship.</li>
  </ul>
</div>

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

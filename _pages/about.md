---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div class="intro-container">
  <p>
    Hi!👋 My name is Hanqian Li (李翰乾). I am currently an <strong>M.Phil student</strong> in the
    <strong>AI Thrust, Information Hub</strong> at the <strong>HKUST(GZ)</strong>, supervised by
    <a href="https://xuminghu.github.io/">Prof. Xuming Hu</a>. Previously, I received my
    <strong>B.Eng. degree in Automation</strong> from <strong>Shandong University (SDU)</strong> in 2025.
  </p>

  <p>My research interests include:</p>
  <ul>
    <li>Watermarking for generative models, including watermark for LLMs and diffusion models.</li>
    <li>Enhancing reasoning ability of LLMs, including VLMs</li>
  </ul>

  <p>
    I am honored to collaborate with <a href="https://exlaw.github.io/">Dr. Aiwei Liu</a>,
    <a href="https://scholar.google.com.hk/citations?user=IL98pCsAAAAJ&hl=zh-CN">Dr. Sirui Huang</a>, and
    <a href="https://openreview.net/profile?id=~Jungang_Li1">Jungang Li</a> on research projects. 
    I am happy to chat and <strong>collaborate</strong> on research. Feel free to contact me at my email.
  </p>
</div>



<h2 class="section-title">🔥 News</h2>
<ul class="news-container">
  <li class="news-item">
    <span class="news-date">[2025.06]</span>
    I have graduated from Shandong University, majoring in Automation Engineering. 🎓
  </li>
  <li class="news-item">
    <span class="news-date">[2025.04]</span>
    A paper on enhancing LLMs for structured knowledge has been accepted at
    <a href="https://sigir2025.dei.unipd.it/" class="news-link">SIGIR 2025</a>.
  </li>
</ul>



## 📕 Publications

<div class="paper-container">
  <div class="paper-image">
    <img src="images/hyperg.jpg" alt="HyperG: Hypergraph-Enhanced LLMs for Structured Knowledge">
  </div>

  <div class="paper-text">
    <div class="paper-title">HyperG: Hypergraph-Enhanced LLMs for Structured Knowledge</div>
    <p class="paper-authors">Sirui Huang*, <strong style="text-decoration-line: underline;">Hanqian Li*</strong>, Yanggan Gu, Xuming Hu, Qing Li, Guandong Xu</p>
    <p class="paper-venue">Proceedings of SIGIR 2025</p>
    <p class="paper-links">
      <a href="https://dl.acm.org/doi/10.1145/3726302.3730002">[Paper]</a>
      <a href="https://github.com/s1ruihuang/HyperG">[Code]</a>
    </p>
  </div>
</div>

<div class="paper-container">
  <div class="paper-image">
    <img src="images/VideoMark.jpg" alt="VideoMark: A Distortion-Free Robust Watermarking Framework for Video Diffusion Models">
  </div>

  <div class="paper-text">
    <div class="paper-title">VideoMark: A Distortion-Free Robust Watermarking Framework for Video Diffusion Models</div>
    <p class="paper-authors">Xuming Hu*, <strong style="text-decoration-line: underline;">Hanqian Li*</strong>, Jungang Li*, Yu Huang, Shuliang Liu, Aiwei Liu</p>
    <p class="paper-venue">arXiv preprint. 2504.16359</p>
    <p class="paper-links">
      <a href="https://arxiv.org/pdf/2504.16359">[Paper]</a>
      <a href="https://github.com/KYRIE-LI11/VideoMark">[Code]</a>
    </p>
  </div>
</div>

<h2 class="section-title">📖 Educations</h2>
<ul class="edu-container">
  <li class="edu-item">
    <span class="edu-date">2025.08 - present</span>, M.Phil Student, <span class="edu-school">HKUST (GZ)</span>
  </li>
  <li class="edu-item">
    <span class="edu-date">2021.09 - 2025.06</span>, Undergraduate Student, <span class="edu-school">Shandong University</span>
  </li>
</ul>

<h2 class="section-title">🖥️ Internship</h2>
<ul class="intern-container">
  <li class="intern-item">
    <span class="intern-date">2025.10 - present</span>, Research Intern, <span class="intern-org">Ant Group</span>
  </li>
  <li class="intern-item">
    <span class="intern-date">2024.02 - 2025.06</span>, Research Intern, <span class="intern-org">HKUST (GZ)</span>
  </li>
</ul>

<h2 class="section-title">📝 Reviewing Services</h2>
<ul class="service-container">
  <li class="service-item">
    <strong>Conferences:</strong> 
    ICME 2025, AAAI 2026, AAAI 2025 Workshop on PDLM
  </li>
  <li class="service-item">
    <strong>Journals:</strong> 
    IEEE Transactions on Circuits and Systems for Video Technology (TCSVT)
  </li>
</ul>



<style>
/* Paper containers */
.paper-container {
  display: flex;
  gap: 18px;
  margin: 20px 0;
  padding: 22px;
  border-radius: 12px;
  background: #fff;
  box-shadow: 0 3px 15px rgba(0,0,0,0.06);
  transition: transform 0.3s, box-shadow 0.3s;
  border: 1px solid rgba(0,0,0,0.05);
}



.paper-image {
  flex: 0 0 350px;
  min-width: 0;
  display: flex;
  align-items: center;
  overflow: hidden;
  border-radius: 8px;
}

.paper-image img {
  width: 100%;
  height: auto;
  object-fit: cover;
  transition: transform 0.4s;
}

.paper-container:hover .paper-image img {
  transform: scale(1.04);
}

.paper-text {
  flex: 1;
  min-width: 0;
}

.paper-title {
  font-weight: 500;
  font-size: 1.2rem;
  margin: 0 0 8px 0;
  color: #000;
  line-height: 1.2;
  letter-spacing: -0.01em;
}

.paper-authors {
  margin: 8px 0;
  font-size: 0.95rem;
  color: rgba(0,0,0,0.75);
  line-height: 1.5;
}

.paper-venue {
  color: #505053ff;
  font-family: "Microsoft YaHei";
  font-style: italic;
  font-size: 1rem;
  margin: 8px 0;
  font-weight: 500;
}

.paper-links {
  margin: 12px 0 5px 0;
}

.paper-links a {
  display: inline-block;
  padding: 5px 12px;
  margin-right: 10px;
  background: linear-gradient(to bottom, #f7f7f7, #efefef);
  color: #0e82c5ff;
  text-decoration: none;
  border-radius: 6px;
  font-size: 0.85rem;
  font-weight: 500;
  border: 1px solid #e5e5e5;
  transition: all 0.2s;
  box-shadow: 0 1px 3px rgba(0,0,0,0.05);
}

.paper-links a:hover {
  background: linear-gradient(to bottom, #f0f0f0, #e8e8e8);
  color: #000;
  border-color: #d5d5d5;
  transform: translateY(-1px);
  box-shadow: 0 3px 5px rgba(99,41,145,0.15);
}
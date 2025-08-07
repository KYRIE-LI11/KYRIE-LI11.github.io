---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<div class="intro-container">

Hi!👋 My name is Hanqian Li(李翰乾). I am currently an **M.Phil student** in the **AI Thrust, Information Hub** at the **Hong Kong University of Science and Technology (Guangzhou)**, supervised by [Prof. Xuming Hu](https://xuminghu.github.io/).  Previously, I received my **B.Eng. degree in Automation** from **Shandong University (SDU)**.I am honored to collaborate with [Dr. Aiwei Liu](https://exlaw.github.io/), [Dr. Sirui Huang](https://scholar.google.com.hk/citations?user=IL98pCsAAAAJ&hl=zh-CN), and [Dr. Jungang Li](https://openreview.net/profile?id=~Jungang_Li1) on research projects.

My research interests focus on **trustworthy large language models** and **multimodal video understanding**. Currently, I am focusing on topics such as text watermarking in LLMs and video watermarking, and I am conducting in-depth research in these areas.
<div>

## 🔥 News
- [2025.06] I have graduated from Shandong University, majoring in Automation Engineering.🎓
- [2025.04] A paper on enhancing LLMs for structured knowledge has been accepted at [SIGIR 2025](https://sigir2025.dei.unipd.it/).

## 📕 Publications

<div class="paper-container">
  <div class="paper-image">
    <img src="images/hyperg.jpg" alt="HyperG: Hypergraph-Enhanced LLMs for Structured Knowledge">
  </div>

  <div class="paper-text">
    <div class="paper-title">HyperG: Hypergraph-Enhanced LLMs for Structured Knowledge</div>
    <p class="paper-authors">Sirui Huang†, <strong style="text-decoration-line: underline;">Hanqian Li†</strong>, Yanggan Gu, Xuming Hu, Qing Li, Guandong Xu</p>
    <p class="paper-venue">SIGIR 2025</p>
    <p class="paper-links">
      <a href="https://dl.acm.org/doi/10.1145/3726302.3730002">[Paper]</a>
      <a href="https://github.com/s1ruihuang/HyperG">[Code]</a>
    </p>
  </div>
</div>

## 📖 Educations
- 2025.08 - present, M.Phil Student, HKUST(GZ)
- 2021.09 - 2025.06, Undergraduate Student, Shandong University

##  🖥️ Internship
- 2024.02 - 2025.06, Research Intern, HKUST(GZ)


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
  color: #0e82c5ff;
  font-family: 'Comic Sans MS', cursive, sans-serif;
  font-size: 1.3rem;
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
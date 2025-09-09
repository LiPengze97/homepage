---
layout: splash
title: "Funding"
permalink: /funding/
author_profile: false
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.35"
  overlay_image: /assets/images/main_banner.jpg
  actions:
    - label: "See Projects"
      url: "/projects/"
excerpt: "Our work is supported by federal agencies and foundations including NIH, NIAID, AHA, CPRIT, and others."

# ← 把原先的 funding_highlight 数组放到这里
feature_row:
  - title: "ACTS (AD Clinical Trial Simulation)"
    excerpt: "Advanced informatics for clinical trial simulation with large-scale EHR."
    url: "https://tao-ai-group.github.io/home/posts/ACTS-md/"
    image_path: "assets/images/funding/ACTs.png"
  - title: "MCC-AD"
    excerpt: "Studying MCC impact on Alzheimer's disease using harmonized EHR."
    url: "https://mcc-ad.github.io/home/"
    image_path: "assets/images/funding/ACTs.png"
  - title: "IMPACT MH"
    excerpt: "Coordinating individually measured phenotypes to advance mental health research."
    url: "#"
    image_path: "assets/images/funding/ACTs.png"
---

<!-- 轻量美化：卡片/徽章/分隔线；若你有自定义样式表，可把这一段移到 _sass/_custom.scss -->
<style>
.funding-nav {
  display:flex; gap:.5rem; flex-wrap:wrap; margin: .25rem 0 1rem;
}
.funding-nav a {
  display:inline-block; padding:.35rem .65rem; border-radius:999px; border:1px solid rgba(0,0,0,.08);
  text-decoration:none; font-weight:600; font-size:.9rem; background:#fff;
}
.funding-nav a:hover { filter:brightness(.98); }
.badge { display:inline-block; font-size:.75rem; padding:.15rem .5rem; border-radius:999px; background:rgba(42,122,226,.12); color:#1e63c6; margin-right:.4rem; }
.funding-list { display:grid; grid-template-columns:repeat(auto-fit,minmax(320px,1fr)); gap:1rem; margin: .75rem 0 1.25rem; }
.funding-card {
  background:#fff; border:1px solid rgba(0,0,0,.06); border-radius:14px; padding:1rem; box-shadow:0 6px 18px rgba(0,0,0,.05);
  transition:transform .18s ease, box-shadow .18s ease;
}
.funding-card:hover { transform:translateY(-2px); box-shadow:0 12px 28px rgba(0,0,0,.08); }
.funding-card h3 { margin:.2rem 0 .35rem; font-size:1.05rem; }
.funding-meta { font-size:.88rem; opacity:.85; margin-bottom:.35rem; }
.funding-meta strong { font-weight:700; }
.funding-card p { margin:.35rem 0; }
.funding-muted { font-size:.9rem; opacity:.8; }
details.funding-detail { margin:.4rem 0 0; }
details.funding-detail summary { cursor:pointer; font-weight:600; }
.feature__wrapper .archive__item-teaser img { object-fit:cover; aspect-ratio: 16/9; }
.section-title{
  margin-top: 1.25rem; margin-bottom:.5rem; border-left:4px solid #2a7ae2; padding-left:.5rem;
}
.last-updated { text-align:right; font-style:italic; opacity:.8; }
</style>

<!-- 顶部高亮：直接用 front matter 的 feature_row -->
{% include feature_row %}

<div class="funding-nav">
  <a href="#active">Active Grants</a>
  <a href="#completed">Completed Grants</a>
</div>

<div class="last-updated">Last update: April 11, 2024</div>

## Active Grants
{:.section-title #active}

<div class="funding-list">

<div class="funding-card">
  <span class="badge">NIH</span> <span class="badge">EHR</span>
  <h3>ACTS: AD Clinical Trial Simulation</h3>
  <div class="funding-meta">
    <strong>Period:</strong> 2021–2027 &nbsp; | &nbsp; <strong>PI/MPI:</strong> Cui Tao (Mayo), GZ Zhang (UTHealth), Jiang Bian (UF)
  </div>
  <p>Developing advanced informatics approaches for an Alzheimer's Disease clinical trial simulation system.</p>
  <p class="funding-muted"><a href="https://tao-ai-group.github.io/home/posts/ACTS-md/" target="_blank" rel="noopener">Project page →</a></p>
</div>

<div class="funding-card">
  <span class="badge">NIH</span> <span class="badge">MCC</span>
  <h3>MCC-AD: MCC’s Impact on AD</h3>
  <div class="funding-meta">
    <strong>Period:</strong> 2023–2027 &nbsp; | &nbsp; <strong>MPI:</strong> Xiaoqian Jiang (UTHealth), Cui Tao (Mayo), Jiang Bian (UF)
  </div>
  <p>End-to-end informatics framework to study multiple chronic conditions’ impact on Alzheimer's disease using harmonized EHR.</p>
  <p class="funding-muted"><a href="https://mcc-ad.github.io/home/" target="_blank" rel="noopener">Project page →</a></p>
</div>

<div class="funding-card">
  <span class="badge">NIH</span> <span class="badge">Mental Health</span>
  <h3>IMPACT MH</h3>
  <div class="funding-meta">
    <strong>Period:</strong> 2024–2029 &nbsp; | &nbsp; <strong>MPI:</strong> Hua Xu (Yale), Cui Tao (Mayo), Yong Chen (UPenn)
  </div>
  <p>Coordinating individually measured phenotypes to advance mental health research.</p>
</div>

<div class="funding-card">
  <span class="badge">NIAID</span> <span class="badge">VAERS</span>
  <h3>Dynamic Learning for Post-Vaccine Event Prediction</h3>
  <div class="funding-meta">
    <strong>Period:</strong> 2017-02-01 – 2024-01-31 &nbsp; | &nbsp; <strong>PI/MPI:</strong> Cui Tao (PI), Yong Chen (MPI)
  </div>
  <details class="funding-detail"><summary>Details</summary>
    Using temporal information in VAERS for post-vaccine event prediction with dynamic learning.
  </details>
</div>

<div class="funding-card">
  <span class="badge">NIH · NIAID</span>
  <h3>VIOLIN 2.0</h3>
  <div class="funding-meta">
    <strong>Period:</strong> 2022-08-19 – 2027-05-31 &nbsp; | &nbsp; <strong>PI/MPI:</strong> Cui Tao (Mayo), Oliver He (UMich), Junguk Hur (UND)
  </div>
  <p>Vaccine Information and Ontology Linked kNowledgebase.</p>
</div>

<div class="funding-card">
  <span class="badge">UPenn · NIH</span>
  <h3>CICADA</h3>
  <div class="funding-meta">
    <strong>Period:</strong> 2021-08-01 – 2023-05-31 &nbsp; | &nbsp; <strong>PI/MPI:</strong> Cui Tao (Mayo), Yong Chen (UPenn)
  </div>
  <p>Clinical informatics and computational approaches for drug-repositioning.</p>
</div>

<div class="funding-card">
  <span class="badge">CPRIT</span>
  <h3>AI-Based Conversational Agent for HPV Education</h3>
  <div class="funding-meta">
    <strong>Period:</strong> 2022-03-01 – 2026-02-28 &nbsp; | &nbsp; <strong>PI:</strong> Cui Tao (Mayo)
  </div>
</div>

<div class="funding-card">
  <span class="badge">AHA</span>
  <h3>AI-Aided Personalization on DAPT after Stent</h3>
  <div class="funding-meta">
    <strong>Period:</strong> 2019-12-01 – 2023-11-30 &nbsp; | &nbsp; <strong>PI:</strong> Cui Tao (Mayo)
  </div>
</div>

<div class="funding-card">
  <span class="badge">NIH</span>
  <h3>Observational Studies of AD/ADRD using Ontology & NLP</h3>
  <div class="funding-meta">
    <strong>Period:</strong> 2021-05-01 – 2024-04-30 &nbsp; | &nbsp; <strong>MPI:</strong> Hua Xu (Yale), Cui Tao (Mayo), Hongfang Liu (UTHealth)
  </div>
</div>

<div class="funding-card">
  <span class="badge">NIH</span>
  <h3>SUDEP Risk Marker Identification & Assessment</h3>
  <div class="funding-meta">
    <strong>Period:</strong> 2020-05-15 – 2025-04-30 &nbsp; | &nbsp; <strong>PI:</strong> Licong Cui
  </div>
</div>

</div> <!-- /funding-list -->

## Completed Grants
{:.section-title #completed}

<div class="funding-list">

<div class="funding-card">
  <span class="badge">NIH</span>
  <h3>Predicting HIV Transmission Risk in MSM</h3>
  <div class="funding-meta">
    <strong>Period:</strong> 2020-09-01 – 2022-08-31 &nbsp; | &nbsp; <strong>PI/MPI:</strong> Cui Tao, Kayo Fujimoto, John Schneider
  </div>
  <p>Using big data and deep learning to predict HIV transmission risks.</p>
</div>

<div class="funding-card">
  <span class="badge">NIH</span>
  <h3>Ontology Completeness: Auditing & Enhancement</h3>
  <div class="funding-meta">
    <strong>Period:</strong> 2019-05-01 – 2022-08-31 &nbsp; | &nbsp; <strong>PI:</strong> Licong Cui
  </div>
  <p>Automated, scalable methods for finding and fixing incompleteness in biomedical ontologies.</p>
</div>

<div class="funding-card">
  <span class="badge">NIH</span>
  <h3>Interface Ontology for AD Research</h3>
  <div class="funding-meta">
    <strong>Period:</strong> 2020-09-15 – 2022-05-31 &nbsp; | &nbsp; <strong>PI:</strong> Licong Cui
  </div>
  <p>Novel interface ontology and web tools for managing and exploring AD data.</p>
</div>

<div class="funding-card">
  <span class="badge">NIH</span>
  <h3>Terminology QA for Clinical Queries over EHR</h3>
  <div class="funding-meta">
    <strong>Period:</strong> 2020-08-01 – 2022-07-31 &nbsp; | &nbsp; <strong>PI:</strong> Licong Cui
  </div>
  <p>Automatic change-suggestion framework and impact assessment on clinical queries.</p>
</div>

<div class="funding-card">
  <span class="badge">NIH</span>
  <h3>Informed Consent: Interpretability & Interoperability</h3>
  <div class="funding-meta">
    <strong>Period:</strong> 2020-09-16 – 2021-09-15 &nbsp; | &nbsp; <strong>PI/Co-I:</strong> Cui Tao, Amy Franklin, Muhammad Amith
  </div>
  <p>Semantic metadata and tools for consent permissions and computable linkage.</p>
</div>

<div class="funding-card">
  <span class="badge">NIH</span>
  <h3>Metadata for Biorepository Data Regulation & Sharing</h3>
  <div class="funding-meta">
    <strong>Period:</strong> 2016-09-28 – 2020-07-31 &nbsp; | &nbsp; <strong>PI:</strong> Cui Tao
  </div>
</div>

<div class="funding-card">
  <span class="badge">NIH</span>
  <h3>Patient Medical History: Representation & Inference</h3>
  <div class="funding-meta">
    <strong>Period:</strong> 2014-09-01 – 2020-08-31 &nbsp; | &nbsp; <strong>PI:</strong> Cui Tao
  </div>
  <p>Ontology/semantic-based temporal reasoning over EHR.</p>
</div>

<div class="funding-card">
  <span class="badge">NIH</span>
  <h3>OncoSphere for Kentucky Cancer Registry</h3>
  <div class="funding-meta">
    <strong>Period:</strong> 2018-06-06 – 2021-07-31 &nbsp; | &nbsp; <strong>MPI:</strong> Licong Cui, GQ Zhang
  </div>
  <p>Ontology-driven faceted query system for registry data exploration.</p>
</div>

</div> <!-- /funding-list -->

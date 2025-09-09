---
layout: single
title: "Projects"
permalink: /projects/
classes: wide
author_profile: false
toc: false
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: /assets/images/main_banner.jpg
---

<style>
@media (min-width: 1024px) {
  .projects-grid {
    grid-template-columns: 1fr; /* 依然单列 */
    max-width: 900px; /* 限制总宽度，居中 */
    margin-left: auto;
    margin-right: auto;
  }
}
.project-card{
  background:#fff;border:1px solid rgba(0,0,0,.06);border-radius:14px;padding:1rem;
  box-shadow:0 6px 18px rgba(0,0,0,.05);
  transition:transform .18s ease, box-shadow .18s ease;
}
.project-card:hover{ transform: translateY(-2px); box-shadow:0 12px 28px rgba(0,0,0,.08); }
.project-card h3{ margin:.2rem 0 .35rem; font-size:1.05rem; }
.project-meta{ font-size:.88rem; opacity:.85; margin:.15rem 0 .35rem; }
.badge{ display:inline-block; font-size:.75rem; padding:.15rem .5rem; border-radius:999px; background:rgba(42,122,226,.12); color:#1e63c6; margin-right:.35rem; }
.project-actions{ margin-top:.5rem; display:flex; gap:.5rem; flex-wrap:wrap; }
.project-btn,
.project-btn--primary {
  outline: none;
}

.project-btn:focus-visible,
.project-btn--primary:focus-visible {
  outline: 2px solid #1e63c6;
  outline-offset: 2px;
}
.project-btn,
.project-btn--primary {
  -webkit-tap-highlight-color: transparent;
}
@media (hover: hover) {
  .project-btn--primary:hover {
    filter: brightness(0.98);
  }
}
.project-btn--primary:active {
  filter: none;
}
.feature__wrapper .archive__item-teaser img{ object-fit:cover; aspect-ratio:16/9; }
.section-title{ margin-top: 1.1rem; margin-bottom:.5rem; border-left:4px solid #2a7ae2; padding-left:.5rem; }
</style>

# Projects
{:.section-title}

<div class="projects-grid">

<div class="project-card" id="acts">
  <span class="badge">EHR</span><span class="badge">Simulation</span>
  <h3>Alzheimer’s Disease Clinical Trial Simulation (ACTS)</h3>
  <div class="project-meta"><strong>Lead:</strong> Team ACTS</div>
  <p>
    Clinical trial simulation helps assess feasibility, test assumptions, and optimize designs before running real-world trials.
    We are building a reusable framework for investigators that: (1) represents eligibility criteria in a formal, standards-compliant way compatible with EHR to retrieve cohorts and phenotypes; and (2) provides an end-to-end pipeline that aligns with large-scale EHR data.
  </p>
  <div class="project-actions">
    <a class="project-btn project-btn--primary" href="https://tao-ai-group.github.io/ACTS/" target="_blank" rel="noopener">Project Website</a>
  </div>
</div>

<div class="project-card" id="mcc-ad">
  <span class="badge">Harmonization</span><span class="badge">Alzheimer’s</span>
  <h3>Multiple Chronic Conditions’ Impact on Alzheimer’s Disease (MCC-AD)</h3>
  <div class="project-meta"><strong>Collaborators:</strong> UTHealth Houston · Mayo Clinic · University of Florida</div>
  <p>
    We enhance interoperability and utility of EHR data to accelerate AD research. The project reduces manual annotation burdens and
    enables privacy-preserving, multi-site analyses to understand how multi-morbidities influence AD.
  </p>
  <div class="project-actions">
    <a class="project-btn project-btn--primary" href="https://mcc-ad.github.io/home/" target="_blank" rel="noopener">Project Website</a>
  </div>
</div>

<div class="project-card" id="cv-llm">
  <span class="badge">LLM</span><span class="badge">Cardiology</span>
  <h3>Large Language Model for Cardiovascular Diseases</h3>
  <div class="project-meta"><strong>Lead:</strong> Dr. Jianfu Li</div>
  <p>
    We explore algorithms and frameworks that support risk prediction, treatment recommendation, disease detection, and other
    clinical tasks using large language models and modern NLP techniques.
  </p>
</div>

<div class="project-card" id="liver-dl">
  <span class="badge">Deep Learning</span><span class="badge">Transplant</span>
  <h3>Deep Learning for Liver Transplant</h3>
  <div class="project-meta"><strong>Lead:</strong> Dr. Ahmed Abdelhameed</div>
  <p>
    We study deep learning on de-identified EHR to predict major risks in liver transplantation.
    Next, we will integrate multimodal signals to strengthen models and provide actionable clinical insight for risk prediction.
  </p>
</div>

</div>

<!-- ## Details
{:.section-title}

### Alzheimer’s Disease Clinical Trial Simulation
Alzheimer’s disease (AD) is the most common cause (60%–80%) of dementia and a leading cause of death in the United States.
Despite approved drugs, therapeutic effects remain modest and AD/ADRD continues to be intractable.  
Clinical trial simulation is an effective way to assess feasibility, investigate assumptions, and optimize study design before trials.

### Multiple Chronic Conditions & AD
This end-to-end framework harmonizes EHR to enable robust, multi-site, privacy-preserving analyses and accelerates AD research.

### Cardiovascular LLM
LLM-based systems for cardiovascular care support risk prediction, treatment recommendation, and disease detection.

### Liver Transplant Modeling
We develop and validate models for risk prediction after liver transplant, moving toward multimodal learning for improved performance. -->

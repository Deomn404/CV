---
layout: home
---

<style>
/* ===== Global Style ===== */
body {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", "Helvetica Neue",
               Arial, "Noto Sans", "PingFang SC", "Microsoft YaHei", sans-serif;
  line-height: 1.75;
  color: #24292f;
}

.wrapper {
  max-width: 980px;
}

h1, h2, h3 {
  letter-spacing: -0.02em;
}

h2 {
  margin-top: 2.4rem;
  padding-bottom: 0.35rem;
  border-bottom: 2px solid #eaeef2;
  color: #1f2937;
}

h3 {
  color: #374151;
  margin-top: 1.6rem;
}

a {
  color: #0969da;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

/* ===== Hero Section ===== */
.hero {
  padding: 2.2rem 2rem;
  margin: 1rem 0 2rem 0;
  border-radius: 18px;
  background: linear-gradient(135deg, #f8fbff 0%, #eef5ff 45%, #f7faff 100%);
  border: 1px solid #dbeafe;
  box-shadow: 0 8px 24px rgba(15, 23, 42, 0.06);
}

.hero h1 {
  margin-bottom: 0.3rem;
  font-size: 2.3rem;
  color: #0f172a;
}

.hero .subtitle {
  font-size: 1.08rem;
  color: #475569;
  margin-bottom: 1rem;
}

.contact-line {
  display: flex;
  flex-wrap: wrap;
  gap: 0.55rem;
  margin-top: 1rem;
}

.contact-item {
  display: inline-block;
  padding: 0.32rem 0.72rem;
  border-radius: 999px;
  background: #ffffff;
  border: 1px solid #dbeafe;
  color: #334155;
  font-size: 0.92rem;
}

/* ===== Badges ===== */
.badge {
  display: inline-block;
  padding: 0.18rem 0.55rem;
  margin: 0.12rem;
  border-radius: 999px;
  font-size: 0.78rem;
  font-weight: 600;
  vertical-align: middle;
}

.badge-blue {
  background: #dbeafe;
  color: #1d4ed8;
}

.badge-green {
  background: #dcfce7;
  color: #166534;
}

.badge-purple {
  background: #ede9fe;
  color: #6d28d9;
}

.badge-orange {
  background: #ffedd5;
  color: #c2410c;
}

.badge-gray {
  background: #f1f5f9;
  color: #475569;
}

/* ===== Highlight Cards ===== */
.highlight-grid {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  gap: 0.8rem;
  margin: 1.5rem 0 2rem 0;
}

.highlight-card {
  padding: 1rem 0.8rem;
  text-align: center;
  border-radius: 14px;
  background: #ffffff;
  border: 1px solid #e5e7eb;
  box-shadow: 0 4px 14px rgba(15, 23, 42, 0.04);
}

.highlight-card .number {
  font-size: 1.55rem;
  font-weight: 800;
  color: #1d4ed8;
}

.highlight-card .label {
  font-size: 0.83rem;
  color: #64748b;
}

/* ===== Publication Cards ===== */
.pub-card {
  padding: 1rem 1.1rem;
  margin: 0.9rem 0;
  border-radius: 14px;
  background: #ffffff;
  border: 1px solid #e5e7eb;
  box-shadow: 0 4px 14px rgba(15, 23, 42, 0.04);
}

.pub-title {
  font-weight: 700;
  color: #111827;
  margin-bottom: 0.25rem;
}

.pub-meta {
  color: #475569;
  font-size: 0.94rem;
}

.pub-role {
  margin-top: 0.35rem;
}

/* ===== Experience Cards ===== */
.exp-card {
  padding: 1.15rem 1.25rem;
  margin: 1rem 0 1.2rem 0;
  border-left: 4px solid #2563eb;
  border-radius: 12px;
  background: #f8fafc;
  border-top: 1px solid #e5e7eb;
  border-right: 1px solid #e5e7eb;
  border-bottom: 1px solid #e5e7eb;
}

.exp-title {
  font-weight: 700;
  font-size: 1.05rem;
  color: #111827;
}

.exp-subtitle {
  color: #475569;
  margin: 0.15rem 0 0.6rem 0;
  font-size: 0.95rem;
}

/* ===== Tables ===== */
table {
  width: 100%;
  border-collapse: collapse;
  margin: 1rem 0;
  overflow: hidden;
  border-radius: 12px;
  font-size: 0.95rem;
}

th {
  background: #f1f5f9;
  color: #334155;
  font-weight: 700;
}

th, td {
  padding: 0.72rem 0.85rem;
  border: 1px solid #e5e7eb;
}

tr:nth-child(even) {
  background: #fafafa;
}

/* ===== Skill Tags ===== */
.skill-group {
  margin: 0.8rem 0;
}

.skill-title {
  font-weight: 700;
  color: #334155;
  margin-bottom: 0.3rem;
}

.skill-tag {
  display: inline-block;
  padding: 0.3rem 0.65rem;
  margin: 0.2rem 0.15rem;
  border-radius: 999px;
  background: #f1f5f9;
  color: #334155;
  font-size: 0.9rem;
  border: 1px solid #e2e8f0;
}

/* ===== Footer ===== */
.footer-note {
  margin-top: 2.5rem;
  padding-top: 1rem;
  border-top: 1px solid #e5e7eb;
  color: #64748b;
  font-size: 0.9rem;
  text-align: center;
}

/* ===== Responsive ===== */
@media (max-width: 760px) {
  .hero {
    padding: 1.5rem 1.2rem;
  }

  .hero h1 {
    font-size: 1.8rem;
  }

  .highlight-grid {
    grid-template-columns: repeat(2, 1fr);
  }

  table {
    font-size: 0.86rem;
  }

  th, td {
    padding: 0.55rem;
  }
}
</style>

<div class="hero">

# Ziyang ZHOU 周子阳

<div class="subtitle">
Master of Engineering in Artificial Intelligence · Shantou University
</div>

<span class="badge badge-blue">Artificial Intelligence</span>
<span class="badge badge-green">Computer Vision</span>
<span class="badge badge-purple">Multimodal Learning</span>
<span class="badge badge-orange">Medical AI</span>
<span class="badge badge-gray">Scientific Computing</span>

<div class="contact-line">
  <span class="contact-item">📍 Sichuan, China</span>
  <span class="contact-item">📧 <a href="mailto:24zyzhou1@stu.edu.cn">24zyzhou1@stu.edu.cn</a></span>
  <span class="contact-item">🌐 <a href="https://github.com/你的用户名">GitHub</a></span>
  <span class="contact-item">📄 <a href="https://scholar.google.com/你的链接">Google Scholar</a></span>
</div>

</div>

## About Me

I am currently pursuing a **Master of Engineering in Artificial Intelligence** at **Shantou University**. My research interests include **computer vision**, **unsupervised optical flow estimation**, **multimodal representation learning**, **medical image analysis**, and **AI-assisted intelligent systems**.

My recent work focuses on developing deep learning methods for visual perception, medical AI, multimodal sentiment analysis, and physics-model-driven scientific computing.

---

## Highlights

<div class="highlight-grid">
  <div class="highlight-card">
    <div class="number">5</div>
    <div class="label">Publications</div>
  </div>
  <div class="highlight-card">
    <div class="number">2</div>
    <div class="label">First-author Works</div>
  </div>
  <div class="highlight-card">
    <div class="number">1</div>
    <div class="label">Patent Application</div>
  </div>
  <div class="highlight-card">
    <div class="number">5</div>
    <div class="label">Selected Awards</div>
  </div>
  <div class="highlight-card">
    <div class="number">91.7%</div>
    <div class="label">Master Average Score</div>
  </div>
</div>

---

## 🔬 Publications & Patents

### Publications

<div class="pub-card">
  <div class="pub-title">
    Shape-Aware Unsupervised Optical Flow via Multi-Scale Recurrent Refinement and Texture-Aware Loss
  </div>
  <div class="pub-meta">
    <strong>Zhou, Z.</strong>, Huang, G., Cai, Z., et al.  
    <em>Pattern Recognition</em>, JCR Q1, IF: 9.1. [07/2026]
  </div>
  <div class="pub-role">
    <span class="badge badge-blue">First Author</span>
    <span class="badge badge-green">Computer Vision</span>
    <span class="badge badge-purple">Optical Flow</span>
  </div>
</div>

<div class="pub-card">
  <div class="pub-title">
    Dual-Space Joint Representation Learning for Robust Multimodal Sentiment Analysis with Incomplete Modalities
  </div>
  <div class="pub-meta">
    <strong>Zhou, Z.</strong>, Huang, G., Cai, Z., et al.  
    <em>IEEE International Conference on Systems, Man, and Cybernetics</em>，SMC 2026, CORE B. [06/2026]
  </div>
  <div class="pub-role">
    <span class="badge badge-blue">First Author</span>
    <span class="badge badge-orange">Multimodal Learning</span>
  </div>
</div>

<div class="pub-card">
  <div class="pub-title">
    Spatiotemporal Decouple Before Act: Disentanglement Representation Learning for Multimodal Sentiment Analysis
  </div>
  <div class="pub-meta">
    Meng, C., <strong>Zhou, Z.</strong>, et al.  
    <em>ICASSP 2026</em>, CORE B, Oral. [05/2026]
  </div>
  <div class="pub-role">
    <span class="badge badge-green">Second Author</span>
    <span class="badge badge-purple">Oral Presentation</span>
  </div>
</div>

<div class="pub-card">
  <div class="pub-title">
    From Collaboration to Cognition: Mapping a Decade of Thematic Evolution
  </div>
  <div class="pub-meta">
    Cai, Z., Zhang, D., <strong>Zhou, Z.</strong>, et al.  
    <em>CSCWD 2026</em>, CORE C, Book Chapter. [05/2026]
  </div>
  <div class="pub-role">
    <span class="badge badge-gray">Third Author</span>
    <span class="badge badge-orange">Book Chapter</span>
  </div>
</div>

<div class="pub-card">
  <div class="pub-title">
    High-Fidelity Retinal Image Synthesis via Dual-Conditioned Diffusion for Improved Vessel and Optic Disc Segmentation
  </div>
  <div class="pub-meta">
    Cai, Z., Zhang, D., <strong>Zhou, Z.</strong>, et al.  
    Submitted to <em>Computer Methods and Programs in Biomedicine</em>, JCR Q2.
  </div>
  <div class="pub-role">
    <span class="badge badge-gray">Third Author</span>
    <span class="badge badge-green">Medical Image Analysis</span>
    <span class="badge badge-purple">Diffusion Model</span>
  </div>
</div>

### Patents

<div class="pub-card">
  <div class="pub-title">
    Medical Question-Answering Method, Apparatus, Device, and Program Product
  </div>
  <div class="pub-meta">
    Invention Patent Application. Application No. <strong>202510982167.0</strong>. [06/2026]
  </div>
  <div class="pub-role">
    <span class="badge badge-blue">Invention Patent</span>
    <span class="badge badge-orange">Medical AI</span>
  </div>
</div>

---

## 🏆 Selected Awards & Honors

| Date | Award | Level |
|------|-------|-------|
| 12/2025 | National Second Prize — "Huawei Cup" Postgraduate Mathematical Modelling Competition | 🥈 National |
| 06/2025 | National Second Prize — "Teddy Cup" National Data Mining Challenge, Graduate Group | 🥈 National |
| 09/2022 | Honourable Mention — "ShuWei Cup" International College Students' Mathematical Modelling Competition | 🏅 International |
| 08/2022 | Silver Award — "Challenge Cup" Liaoning Provincial College Students' Business Plan Competition | 🥈 Provincial |
| 05/2022 | National Second Prize — "ShuWei Cup" National College Students' Mathematical Modelling Competition, Undergraduate Group | 🥈 National |

---

## 🔧 Research Experience

<div class="exp-card">
  <div class="exp-title">
    AI-Assisted Skin Health Condition Analysis System
  </div>
  <div class="exp-subtitle">
    Research Member · Patent Application Project · 10/2025 – 06/2026
  </div>

- Built and fine-tuned a **lesion segmentation model** for AI-assisted skin health analysis, leveraging disease-specific visual features and **LLM-assisted reasoning**
- Improved segmentation of skin lesion regions for downstream visual feature extraction in medical image analysis
- Contributed to an **invention patent application** for medical question-answering methods, devices, equipment, and program products

</div>

<div class="exp-card">
  <div class="exp-title">
    Physics-Model-Driven Deep Learning for Full-Resolution Heat Transfer Analysis
  </div>
  <div class="exp-subtitle">
    Research Assistant · Guangdong Provincial Natural Science Foundation, General Programme · 2023 – Present
  </div>

- Developed an **unsupervised velocity field estimation module** for full-resolution heat transfer analysis in physical experimental settings without ground-truth labels
- Designed a **multi-scale recurrent refinement framework** for high-resolution optical flow estimation in real-world fluid flow scenarios
- Proposed a **texture-aware photometric loss** weighted by local information entropy to enhance robustness under complex material textures and irregular deformations
- Contributed to the manuscript: *Shape-Aware Unsupervised Optical Flow via Multi-Scale Recurrent Refinement and Texture-Aware Loss*

</div>

---

## 💼 Internship Experience

<div class="exp-card">
  <div class="exp-title">
    AI-Driven Digital Human Live-Streaming Project
  </div>
  <div class="exp-subtitle">
    Core Technical Developer · SERES Group "SaiChuang Cup" Competition · 03/2026 – Present
  </div>

- Served as a **core technical developer** in an AI-driven digital human live-streaming project jointly developed with the Overseas Business Unit of SERES Group
- Took primary responsibility for the technical development and implementation of the **digital human live-streaming system** for overseas market scenarios
- Contributed to the integration of AI-based digital human technologies into live-streaming workflows, supporting **automated product presentation** and **interactive audience engagement**
- Coordinated with the Overseas BU team to align technical design with business requirements for international market promotion

</div>

---

## 🎓 Education

### Shantou University — School of Engineering, Guangdong, China

**Master of Engineering in Artificial Intelligence**  
09/2024 – Present

- **Average Score: 91.7%**
- Selected Courses & Grades:

| Course | Grade |
|--------|-------|
| Optimization Methods | 98% |
| Research Methods & Academic Paper Writing | 97% |
| Numerical Analysis | 93% |
| Statistical Learning Methods | 92% |
| Scientific Writing in Foreign Languages | 92% |
| Modern Signal Processing | 90% |
| Modern Neural Networks | 86% |
| Python and Machine Learning | 85% |

### Shenyang Aerospace University — School of Aeronautical Engines, Liaoning, China

**Bachelor of Engineering in Flight Vehicle Propulsion Engineering**  
09/2020 – 06/2024

- Selected Courses: Computer Programming, Probability Theory & Mathematical Statistics, Fluid Mechanics, Engineering Testing Technology, Finite Element Method

---

## 🛠 Skills

<div class="skill-group">
  <div class="skill-title">Programming</div>
  <span class="skill-tag">Python</span>
  <span class="skill-tag">C++</span>
  <span class="skill-tag">C</span>
  <span class="skill-tag">MATLAB</span>
  <span class="skill-tag">LaTeX</span>
</div>

<div class="skill-group">
  <div class="skill-title">AI / Machine Learning</div>
  <span class="skill-tag">PyTorch</span>
  <span class="skill-tag">NumPy</span>
  <span class="skill-tag">Matplotlib</span>
  <span class="skill-tag">Deep Learning</span>
  <span class="skill-tag">Computer Vision</span>
  <span class="skill-tag">Multimodal Learning</span>
</div>

<div class="skill-group">
  <div class="skill-title">Web & Systems</div>
  <span class="skill-tag">HTML</span>
  <span class="skill-tag">CSS</span>
  <span class="skill-tag">Linux</span>
</div>

<div class="skill-group">
  <div class="skill-title">Languages</div>
  <span class="skill-tag">Mandarin, Native</span>
  <span class="skill-tag">English, IELTS 6.5</span>
</div>

---

## 📊 Summary

- 📝 **5 publications**, including **2 first-author works**
- 🔬 Research experience in **computer vision**, **medical AI**, **multimodal learning**, and **physics-model-driven deep learning**
- 📜 **1 invention patent application**
- 🏆 **5 selected awards**, including national, international, and provincial honors
- 💼 Industry experience in **AI-driven digital human live-streaming system development**
- 🎓 Master average score: **91.7%**

<div class="footer-note">
  Last updated: July 2026 · Built with GitHub Pages
</div>

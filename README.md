<h1 align="center">Hi there, I'm Alvie Wang 👋</h1>

<p align="center">
  <em>MPhil @ CUHK(SZ) · AI Institute · Multimodal AI & Embodied Intelligence</em>
</p>

<p align="center">
  <a href="mailto:hrwang1001@outlook.com"><img src="https://img.shields.io/badge/Email-hrwang1001%40outlook.com-blue?style=flat&logo=gmail"/></a>
  <a href="https://github.com/AlvieWang"><img src="https://img.shields.io/github/followers/AlvieWang?label=Followers&style=social"/></a>
  <a href="https://scholar.google.com/"><img src="https://img.shields.io/badge/Google%20Scholar-4285F4?style=flat&logo=googlescholar&logoColor=white"/></a>
  <a href="https://github.com/AlvieWang"><img src="https://komarev.com/ghpvc/?username=AlvieWang&style=flat-square&color=blue" alt="Profile Views"/></a>
</p>

---

## 🧑‍💻 Quick Snapshot

| 📌 | |
|:---|:---|
| **Name** | 王洪榕 (Hongrong Wang) / Alvie Wang |
| **Role** | MPhil Student @ [CUHK(Shenzhen)](https://www.cuhk.edu.cn/) — AI Institute |
| **Advisor** | [Prof. Zhizheng Wu (武执政)](https://sai.cuhk.edu.cn/teacher/106) |
| **Research** | Vision-Language-Action (VLA) Models · Embodied AI · Preference Alignment (DPO) · Sim-to-Real Transfer |
| **Location** | 📍 Shenzhen, China |
| **Email** | hrwang1001@outlook.com |
| **GitHub** | [@AlvieWang](https://github.com/AlvieWang) |

---

## 🔬 Research Interests

```
Multimodal LLM ──► Vision-Language-Action (VLA) Models
        │
        ├── Embodied AI & Robot Task Planning
        │   └── AI2-THOR + 6-DoF Manipulation
        ├── Preference Alignment (DPO / RLHF)
        │   └── Bias-aware Negative Sample Construction
        └── Sim-to-Real Transfer Learning
            └── Domain Randomization + Policy Adaptation
```

---

## 📚 Education

### 🎓 CUHK(Shenzhen) — Master of Philosophy in Computer Science
**AI Institute** | *2025.09 – Present (Expected 2027)*
- **Advisor**: Prof. Zhizheng Wu (武执政)
- **Focus**: Multimodal Large Language Models for Embodied Intelligence
- **Key Courses**: CEC5000 Advanced Topics in AI · Deep Learning · Machine Learning Theory
- **Thesis Direction**: Staged Vision-Language Learning for Physically-Grounded Embodied Task Planning ([SVLL](#svll--staged-vision-language-learning-for-embodied-task-planning))

### 🎓 Guangdong University of Technology — B.E. in Information Management & Information Systems
**School of Management** | *2021.09 – 2025.06*
- **GPA**: Top tier; Research advisor: Prof. Chen Lei (陈磊教授)
- **Core Courses**: Data Structures · Database Systems · Machine Learning · Information Retrieval · Python Programming · Mathematical Modeling
- **Capstone**: Constrained optimization models for vegetable auto-pricing & replenishment → Published at CIS 2023

---

## 💼 Research & Work Experience

#### 🤖 Research Assistant — Embodied AI Lab
[CUHK(Shenzhen)](https://www.cuhk.edu.cn/) · *Nov 2025 – Present*
- Leading the **SVLL** project: A staged VLA framework for physically-grounded embodied task planning (ECCV 2026 submission)
- Designed a **three-stage fine-tuning pipeline** on Qwen2.5-VL-7B: vision grounding → task planning → action refinement
- Built **Bias-DPO** preference dataset (<1000 negative samples) with 4-category physical violation annotation scheme
- Developed **five-dimensional evaluation system** (SR/SPL/VAR/LR/CVR) on AI2-THOR simulation benchmark
- Current SR: **78.35%** on SVLL benchmark

#### 🔍 Open Source Intern — DeepSeek-OCR Project
Institute of Automation, Chinese Academy of Sciences (ISAS/CAS) · *Feb – Aug 2025*
- Contributed to **DeepSeek-OCR** document understanding pipeline based on MindSpore framework
- Produced multi-format SFT training data for document OCR and structured information extraction
- Worked on end-to-end document image processing: layout analysis → text recognition → structured output
- Gained production-level experience in large-scale data pipelines and model deployment

#### 🏙️ Research Collaborator — Urban Vision Computing
HKUST(Guangzhou) · *2024 – 2025*
- Co-developed **BuildingView**: urban building exterior database using street view imagery and Multimodal LLM
- Leveraged MLLM for automated building attribute extraction from panoramic street-level images
- Paper accepted at **ACM SpatialDI 2025**

#### 👨‍🎓 Undergraduate Researcher — Evolutionary Computation
Guangdong University of Technology · *2023 – 2025*
- Advisor: Prof. Chen Lei (陈磊教授)
- Published work on LLM-designed evolutionary operators for Multi-objective VRP (Under review at IJCIAP)
- Built constrained single-objective optimization model for vegetable pricing (Published at **CIS 2023**)

---

## 📝 Publications

| Status | Title | Venue | Links |
|--------|-------|-------|-------|
| ⏳ *Under Review* | **SVLL**: Staged Vision-Language Learning for Physically-Grounded Embodied Task Planning | ECCV 2026 | [📄 arXiv](https://arxiv.org/) |
| ✅ *Published* | **BuildingView**: Constructing Urban Building Exteriors Databases with Street View Imagery and MLLM | ACM SpatialDI 2025 | [💻 Code](https://github.com/Jasper0122/BuildingView) |
| ⏳ *Under Review* | Transfer Learning-Based Evolutionary Algorithm with LLM-designed Operators for MO-VRP | IJCIAP | — |
| ✅ *Published* | Constrained Optimization Model for Vegetable Auto Pricing & Replenishment | CIS 2023 | — |

> 📄 Full publication list: [Google Scholar](https://scholar.google.com/) · [arXiv Author](https://arxiv.org/search/?query=Alvie+Wang)

---

## 🧪 Featured Projects

<a name="svll--staged-vision-language-learning-for-embodied-task-planning"></a>
### 🧠 SVLL — Staged VLLM for Embodied Task Planning
**ECCV 2026 Submission** | *Flagship research project*

> A novel staged fine-tuning framework that adapts general-purpose VLMs into effective embodied task planners through progressive skill acquisition.

<details>
<summary><b>🔧 Technical Deep Dive</b></summary>

| Component | Details |
|-----------|---------|
| **Base Model** | Qwen2.5-VL-7B (Vision-Language Model) |
| **Stage 1: Vision Grounding** | Object localization, attribute recognition, spatial relation understanding |
| **Stage 2: Task Planning** | High-level goal decomposition, sub-task sequencing |
| **Stage 3: Action Refinement** | Low-level action parameter prediction, physical constraint reasoning |
| **Training Method** | Bias-DPO (Direct Preference Optimization with bias-aware negative sampling) |
| **Dataset** | <1000 carefully curated negative samples across 4 physical violation categories |
| **Benchmark** | AI2-THOR (indoor household environment simulator) |
| **Metrics** | Success Rate (SR): 78.35% · Success weighted by Path Length (SPL) · Variance (VAR) · Learning Rate (LR) · Coverage Rate (CVR) |

**Key Innovation:** Three-stage curriculum learning reduces catastrophic forgetting while Bias-DPO handles the long-tail distribution of physical constraint violations.
</details>

---

### 🏙️ BuildingView — Urban Building Exterior Database
**ACM SpatialDI 2025** | [Code](https://github.com/Jasper0122/BuildingView)

> Automated construction of building exterior databases at city scale by leveraging street view imagery and Multimodal Large Language Models.

<details>
<summary><b>🔧 Technical Details</b></summary>

- **Data Source**: Panoramic street view images (Baidu/Street View APIs)
- **MLLM Backbone**: Used for zero-shot building attribute extraction
- **Output**: Structured database with building height, facade style, material, color, window patterns
- **Scale**: City-level coverage with automated quality control pipeline
- **Impact**: Enables large-scale urban computing applications (energy estimation, 3D reconstruction)
</details>

---

### 🔤 DeepSeek-OCR — Document Understanding Pipeline
**Internship @ ISAS, CAS** | *MindSpore Framework*

> Production-grade document image processing system supporting multi-format input and structured output.

<details>
<summary><b>🔧 Technical Details</b></summary>

- **Framework**: Huawei MindSpore deep learning framework
- **Pipeline**: Document image → Layout Analysis → Text Detection → OCR Recognition → Structured Output
- **Contribution**: SFT data production for model fine-tuning, covering invoices, receipts, forms, certificates
- **Formats Supported**: PDF, image (PNG/JPG), scanned documents
- **Deployment**: End-to-end inference service with batch processing capability
</details>

---

## 🛠️ Technical Skills

### Programming Languages & Frameworks
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/MindSpore-FD7900?style=flat&logo=huawei&logoColor=white"/>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat&logo=java&logoColor=white"/>
  <img src="https://img.shields.io/badge/MATLAB-0076A8?style=flat&logo=mathworks&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white"/>
  <img src="https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyQt5-41CD52?style=flat&logo=qt&logoColor=white"/>
</p>

### AI/ML Specialization
<p>
  <img src="https://img.shields.io/badge/Qwen--VL-FF6F00?style=flat" alt="Qwen-VL"/>
  <img src="https://img.shields.io/badge/AI2--THOR-3D-E91E63?style=flat" alt="AI2-THOR"/>
  <img src="https://img.shields.io/badge/DPO/Preference%20Alignment-9C27B0?style=flat" alt="DPO"/>
  <img src="https://img.shields.io/badge/MOEA/D-009688?style=flat" alt="MOEA/D"/>
  <img src="https://img.shields.io/badge/DeepSeek--OCR-00BFFF?style=flat" alt="DeepSeek-OCR"/>
  <img src="https://img.shields.io/badge/Federated_Learning-FF6600?style=flat" alt="FL"/>
  <img src="https://img.shields.io/badge/Sim--to--Real-2196F3?style=flat" alt="Sim2Real"/>
</p>

### Domains of Expertise
`VLA Models` · `Multimodal LLM` · `Embodied AI` · `Preference Alignment (DPO)` · `Federated Learning` · `Document AI (OCR)` · `Evolutionary Computation`

---

## 🏆 Honors & Awards

| Year | Award | Level |
|------|-------|-------|
| 2025 | 🥇 Ministry of Education — Huawei "Smart Base" Scholarship | Top 0.05% nationwide |
| 2024 | 🏅 National **First Prize**, Statistical Modeling Competition | National |
| 2024 | 🏅 National **Second Prize**, Mathematical Modeling Competition | National |
| 2023–25 | 📜 **6 Software Copyrights** | Weather Prediction · Image Processing · Air Quality · Clustering Analysis (+2 before 2025) |
| 2024–25 | 🤝 **Huawei Student Developer (HSD) Ambassador** | Campus Developer Alliance |
| 2023 | ✅ Best Paper Award Nominee, CIS 2023 | Conference |

---

## 🎯 Currently Working On

- 🧠 **[SVLL](#svll--staged-vision-language-learning-for-embodied-task-planning)** — ECCV 2026 submission deadline approaching! Fine-tuning final stage.
- 🤖 Building **AI2-THOR + 6-DoF manipulation** experimental platform for next paper
- 📖 Reading notes: [paper-notes](https://github.com/AlvieWang/paper-notes) (updating weekly)
- 📝 Exploring **VLA + Federated Learning** intersection for privacy-preserving robot learning

---

## 📫 Contact & Social

<p float="left">
  <a href="mailto:hrwang1001@outlook.com"><img height="28" src="https://img.shields.io/badge/Email-hrwang1001%40outlook.com-blue?style=for-the-badge&logo=microsoft-outlook&logoColor=white"/></a>
  &nbsp;
  <a href="https://github.com/AlvieWang"><img height="28" src="https://img.shields.io/badge/GitHub-%40AlvieWang-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

---

<details open>
<summary><h3>📄 Full CV (Download)</h3></summary>

> 💡 **Looking for internship opportunities** in Multimodal LLM / Embodied AI / Data Production & Evaluation (Summer/Fall 2026)

**Target Roles:** Algorithm Engineer (Multimodal/Agent/Data) @ Tencent · ByteDance · Alibaba · DeepSeek · Research Labs

<details>
<summary><b>👇 Click to expand complete CV</b></summary>

### Personal Information
- **Name**: 王洪榕 (Hongrong Wang / Alvie Wang)
- **Education**: MPhil CS @ CUHK(Shenzhen), AI Institute (2025–2027)
- **B.E.** Information Management & IS @ Guangdong Univ. of Tech (2021–2025)
- **Research Advisor**: Prof. Zhizheng Wu (武执政) @ CUHK(SZ); Prof. Chen Lei (陈磊) @ GDUT
- **Email**: hrwang1001@outlook.com
- **Location**: Shenzhen, China
- **GitHub**: github.com/AlvieWang

### Core Competencies
1. **Multimodal LLM Engineering**: VLA model design, vision-language fine-tuning (Qwen2.5-VL), DPO preference alignment
2. **Embodied AI**: AI2-THOR simulation, task planning, physical constraint reasoning, five-dimensional evaluation
3. **Data Pipeline**: SFT data production (DeepSeek-OCR), multi-format document processing, bias-aware sampling
4. **Research Skills**: Literature survey, experiment design, paper writing (LaTeX), academic presentation

### Key Projects (Summary)
| # | Project | Role | Outcome |
|---|---------|------|---------|
| 1 | SVLL (VLA for Embodied Planning) | Lead | ECCV 2026 submission, SR=78.35% |
| 2 | BuildingView (Urban DB w/ MLLM) | Co-author | ACM SpatialDI 2025 |
| 3 | DeepSeek-OCR (Document AI) | Intern | Production data pipeline @ CAS |
| 4 | MOEA/D + LLM Operators | Researcher | IJCIAP under review |
| 5 | Vegetable Pricing Optimization | Lead | CIS 2023 published |

### Intellectual Property
- 6 Software Copyrights registered (weather prediction, image processing, air quality assessment, clustering analysis, +2 additional before 2025)
</details>

</details>

---

<details>
<summary><b>🎵 Now Playing</b></summary>
<br>
<em>Current vibe: Dream Is Possible 🎹</em>
<br><br>
<i>"Keep chasing dreams, one line of code at a time."</i>
</details>

---

<p align="center">
  <em>⭐ If you find my work interesting, consider giving a star! Feel free to reach out for collaboration.</em>
  <br>
  <strong>Last updated: 2026-05-10</strong>
</p>

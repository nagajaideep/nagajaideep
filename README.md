# Naga Jaideep Chowdary

**AI/ML Engineer · Software Engineer · Builder**
B.Tech CSE (AIML) @ MGIT, Hyderabad · 2023–2027 · CGPA 9.21/10

[![Email](https://img.shields.io/badge/Email-jaideepchowdary2%40gmail.com-red?style=flat-square)](mailto:jaideepchowdary2@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-NagaJaideep-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/naga-jaideep-c-8b6040285/)
[![GitHub](https://img.shields.io/badge/GitHub-nagajaideep-181717?style=flat-square&logo=github)](https://github.com/nagajaideep)
[![LeetCode](https://img.shields.io/badge/LeetCode-jaideepchowdary2-FFA116?style=flat-square&logo=leetcode)](https://leetcode.com/u/jaideepchowdary2/)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-nagajaideep-yellow?style=flat-square&logo=huggingface)](https://huggingface.co/nagajaideep)

Open to **Software / AI Engineering** and **Machine Learning Engineering** roles — I build production AI systems (agents, APIs, full-stack apps) and deep learning research (medical imaging, NLP, geospatial ML). Based in Hyderabad.

---

## Experience

| Role | Organization | Period | Impact |
|---|---|---|---|
| Research Intern | IIT Hyderabad (EE & AIML) | Ongoing | — |
| Full Stack Developer Intern | Anshap | Apr 2026 – Jun 2026 | Integrated multiple LLMs into a mental health platform serving 3,000+ users; built an event-driven re-engagement pipeline (+40% DAU retention) and a LiveKit-based real-time calling system (sub-100ms latency, -60% infra cost) |
| Research Intern (Dr. Barnali Gupta Banik) | MGIT | Apr 2026 – Jun 2026 | Built BioAge-Net (ResNet-50) for biological age estimation from chest X-rays — led to an IEEE ICSCST 2026 paper |
| Software Engineering Intern | Open Science Labs (ASTx) | May 2025 – Aug 2025 | Built an ASTx-to-Python transpiler; fixed 27+ bugs, +70% transpilation performance, 100% CI test coverage |
| Tech Lead Intern — NLP & AI Pipelines | Viswam.AI × Swecha × IIIT Hyderabad | 2025 | Led a multilingual recipe translation system (mBART/MarianMT) serving 1,00,000+ daily users |
| Research Intern: Machine Learning | IIT Roorkee — CoDA Lab | Apr 2025 – May 2025 | 81.68% land cover classification accuracy (Kappa 76.6%) on Bengaluru satellite data; ANOVA/MANOVA-backed urban heat findings |

---

## Research Papers

- **Biological Age Estimation from Chest Radiographs Using Deep Learning: A ResNet-50 Based Approach with Clinical Risk Stratification** — Accepted, IEEE Xplore proceedings (ICSCST 2026). BioAge-Net achieves 4.91-year MAE, 0.8455 R², 0.9198 Pearson correlation on the NIH ChestX-ray14 dataset (112K+ images), with a three-level clinical risk stratification framework validated on an external dataset.
- **Brain Tumor MRI Classification & Risk Stratification (BrainRiskNet)** — Published, IEEE Xplore proceedings.
- **Why Do Urban Cooling Islands Exist? Understanding the Drivers of Localized Urban Cooling** — Manuscript in preparation, IIT Roorkee CoDA Lab.
- Journal paper on skin lesion classification (MILK10k dataset) — in preparation, targeting Q1 journals (e.g. *Medical Image Analysis*, *Computers in Biology and Medicine*, IEEE JBHI).

---

## 🖥️ Software / AI Engineering Projects

*Full-stack and applied-AI systems — routing, agents, product-grade APIs.*

### [AI-Powered Customer Support Agent](https://github.com/nagajaideep/AI-powered-customer-support-)
*Multi-agent architecture · TypeScript · LLM routing*
- Router-based multi-agent system that classifies user intent and dispatches to specialized sub-agents (billing, technical, general) with shared memory context
- Deployed and production-ready

### [RouteIQ — NLP-Based Query Routing Engine](https://github.com/nagajaideep) · [Live Demo]
*FastAPI · DistilBERT · Python*
- Fine-tuned a DistilBERT multi-class intent classifier, served via a FastAPI `/predict` REST API
- Sub-200ms classification latency; reduced manual ticket-sorting effort by 80%

### [ShiftCV — AI Resume Transformer](https://github.com/nagajaideep) · [Live Demo]
*React · FastAPI · PostgreSQL · Google Gemini 2.5*
- Parses uploaded PDF resumes into structured, editable LaTeX templates via an agentic Gemini 2.5 Flash pipeline (extraction → reformatting → LaTeX validation)
- Eliminated manual reformatting for 90% of users; cut conversion time from 3 hours to under 90 seconds

### Multilingual Recipe Translation System *(Viswam.AI)*
*mBART · MarianMT · Python · NLP Pipelines*
- Fine-tuned Transformer models to translate recipes across Indian languages; integrated into the main Viswam.AI API, serving 1,00,000+ daily users
- Led a team of interns as Tech Lead across data collection, annotation, and model integration; curated 20+ hours of multilingual audio-video data and 200+ annotated images

### [YT Smart Speed — Intelligent Chrome Extension](https://github.com/nagajaideep)
*JavaScript · Manifest V3 · Chrome APIs*
- Intercepts YouTube's Most Replayed heatmap (fetch wrapping + DOM/SVG fallback) to map per-video intensity to adaptive playback speed
- Production-ready Manifest V3 extension, 100% local processing

### [Restaurant Booking Voice Agent](https://github.com/nagajaideep/restaurant-booking-voice-agent)
*MERN Stack · NLP · Voice I/O*
- End-to-end voice booking pipeline: speech input → intent parsing → availability check → DB write → confirmation

### [Kitchen Talk Recorder](https://huggingface.co/spaces/nagajaideep/Kitchen-Talk-Recorder)
*Whisper-tiny · Streamlit · Hugging Face Spaces*
- Telugu voice-to-text transcription app for recipe dictation, live on Hugging Face Spaces

### [Gesture Presentation System](https://github.com/nagajaideep/Gesture-Presentation)
*Python · OpenCV · Computer Vision*
- Real-time hand-gesture recognition to control presentation slides, with freehand drawing/erasing
- 3rd place, internal college hackathon

---

## 🔬 ML Engineering / Research Projects

Alongside software engineering, I'm deeply interested in AI/ML research — deep learning model design, medical imaging, and applied research projects below.

### BioAge-Net — Biological Age Estimation from Chest Radiographs
*Python · PyTorch · ResNet-50 · Medical Imaging · Clinical Risk Stratification*
- End-to-end pipeline (CLAHE enhancement, augmentation, transfer learning) on 112K+ NIH ChestX-ray14 images, with Grad-CAM explainability
- 4.91-year MAE, 0.8455 R², 0.9198 Pearson correlation; three-tier clinical risk stratification, validated on an external dataset
- Co-authored with Dr. Barnali Gupta Banik; accepted at IEEE ICSCST 2026

### Multimodal Skin Cancer Detection System (MILK10k)
*EfficientNet-V2 · Transformers · Cross-Modal Fusion · PyTorch*
- Dual-stream network fusing dermoscopic images, clinical images, and patient metadata
- Architecture: EfficientNet-V2 encoders → cross-modal transformer fusion → GeM pooling → SE attention; Focal Loss for class imbalance, MONET concept auxiliary head for interpretability
- Ranked 55th of 165 teams globally in the ISIC MILK10k Benchmark; working toward a Q1 journal submission

### BrainRiskNet — Brain Tumor MRI Classification & Risk Stratification
*TensorFlow · CNN + ConvLSTM · Multi-GPU*
- Dual-head model for 4-class tumor classification and 3-tier risk prediction, with brain-region cropping, normalization, and augmentation
- 91.56% accuracy, 92.54% precision, 91.51% F1 — outperforming baseline by ~5%; Grad-CAM visualizations and full ROC/PR evaluation
- Published, IEEE Xplore proceedings

### Urban Land Surface Temperature & Land Cover Classification
*Google Earth Engine · Random Forest · ANOVA/MANOVA*
- Diurnal and seasonal LST analysis across Bengaluru integrating MODIS LST (2019–2022), Landsat-8 imagery, and WorldPop socio-economic data
- 81.68% land cover classification accuracy (Kappa 76.6%) using Random Forest (500 trees) on Landsat-8 spectral bands + NDVI
- Findings feeding into a manuscript on urban cooling islands and heat-mitigation planning for low-income, high-density zones

### Amazon ML Challenge 2025
*Multimodal Learning · Python*
- Built a multimodal price prediction model combining product images and text; iterated from 57% SMAPE (image + text) to 52% (text-only) after empirical analysis
- 3-day competitive ML sprint, team of 4

### Customer Churn Prediction *(ongoing)*
*Python · Scikit-learn · Jupyter*
- ML pipeline for churn prediction; feature engineering and model evaluation in progress

---

## Open Source

**[data-umbrella/du-event-board](https://github.com/data-umbrella/du-event-board)**
- Added full date filtering to the DU Event Board search experience (custom date picker + range selector)
- +457 lines changed across frontend components; merged after a 4-comment maintainer review cycle

**[arxlang/astx](https://github.com/arxlang/astx)** *(Open Science Labs internship)*
- Contributed to a Python transpiler converting AST nodes between representations; +70% efficiency improvement
- Worked under mentor Ivan Ogasawara (OSL lead) with structured code review

**GSSoC '24 & Winter of Blockchain**
- 5+ PRs merged across multiple repositories, concurrently active in both programs

---

## Achievements

- 🥈 Silver Medal — academic excellence, 2nd year B.Tech, CGPA 9.38 (MGIT)
- 🥇 1st Place — State-Level Project Expo (AI/ML project)
- 🏆 Smart India Hackathon (SIH) — winner of multiple internal rounds, qualified for national-level challenge
- 🥉 3rd Place — internal hackathon (Gesture Presentation System)
- 🚀 NASA Space Settlement Contest Winner (High School)
- Ranked 55th of 165 teams globally — ISIC MILK10k Benchmark

## Certifications

- Machine Learning Specialization — DeepLearning.AI (Coursera), Mar 2026
- Google Cloud Agentic AI Day (5-day course) — Aug 2025
- Supervised Machine Learning: Regression and Classification — DeepLearning.AI (Coursera), Jul 2025
- Network Technician Career Path — Cisco (Credly), 2025

---

## Tech Stack

**ML / AI:** PyTorch · TensorFlow · Scikit-learn · Keras · Hugging Face Transformers · mBART · MarianMT · Whisper · OpenCV · Diffusion Models · GANs
**Backend:** Python · FastAPI · Flask · Node.js · Express · Spring Boot · Java
**Frontend:** React · JavaScript · TypeScript · HTML/CSS
**Databases:** PostgreSQL · MongoDB · MySQL
**Cloud / DevOps:** AWS (EC2, S3) · Azure (App Service) · Google Earth Engine · GitHub Actions · CI/CD · Vercel · Render · Hugging Face Spaces
**Data:** Pandas · NumPy · Matplotlib · SciPy · Seaborn · SQL

---

## DSA & Competitive Programming

- 2★ CodeChef; ranked 1,290 / 12,500+ in CodeChef Starters 238
- 330+ DSA problems solved across platforms — [Codolio Profile](https://codolio.com)
- Active on LeetCode, focused on graphs, DP, greedy, and system design — [LeetCode profile](https://leetcode.com/u/jaideepchowdary2/)

---

<p align="center">
  <img width="47%" src="https://github-readme-stats.vercel.app/api?username=nagajaideep&show_icons=true&theme=default&hide_border=true&hide=stars" />
  <img width="47%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=nagajaideep&layout=compact&theme=default&hide_border=true" />
</p>

---

*Open to Software/AI Engineering and Machine Learning Engineering roles. Based in Hyderabad.*

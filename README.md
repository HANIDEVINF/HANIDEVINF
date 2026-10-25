# Hani Ghena — Applied AI Engineer | NLP, Deep Learning & LLM Systems

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Hani_Ghena-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/ghena-hani-3543a3375/)
[![Email](https://img.shields.io/badge/Email-hanighena4%40gmail.com-ec4899?style=for-the-badge&logo=gmail)](mailto:hanighena4@gmail.com)
[![Portfolio](https://img.shields.io/badge/Live_Portfolio-Interactive_Lab-8b5cf6?style=for-the-badge)](https://ais-pre-4br5xw5mjzlfdkdvyz7xyq-909472834222.europe-west2.run.app)
[![Location](https://img.shields.io/badge/Location-Algiers%2C_Algeria-10b981?style=for-the-badge)](https://maps.google.com/?q=Algiers,Algeria)

> **M.Sc. in Artificial Intelligence @ USTHB (2025–2027)** · **AI Researcher @ CERIST DTISI UbiSys Lab (2024–2025)**  
> Applied AI Engineer specializing in **Biomedical Signal Deep Learning (ECG Arrhythmia & Asthma Telemetry)**, **Multilingual NLP (Arabic, Darija, Berber, French, English)**, **LLM Evaluation & Agentic Workflows**, and **High-Reliability Client Production Systems**.

---

## 🎓 Academic Background & Experience

| Role / Degree | Institution / Organization | Period | Highlights & Validation |
| :--- | :--- | :--- | :--- |
| **Master's in Artificial Intelligence (M.Sc.)** | USTHB (*Univ. des Sciences et de la Technologie Houari Boumediene*) | **Sep 2025 – Expected June 2027** | Advanced Deep Learning, Transformers, Evidential Deep Learning, Multi-Modal Signal Processing |
| **Licence in Computer Science (B.Sc.)** | USTHB (*Univ. des Sciences et de la Technologie Houari Boumediene*) | **Sep 2022 – June 2025** *(Graduated)* | Software Engineering, Distributed Systems, PFE Capstone on IoT Telemedicine (MedGuardAI) |
| **Baccalauréat in Exact Sciences / Mathematics** | Ministère de l'Éducation Nationale | **2022** *(Graduated)* | Mathematics, Physics, Algorithmic Foundations |
| **AI Research Fellow / Intern** | CERIST (*Centre de Recherche sur l'Information Scientifique et Technique*) | **2024 – 2025** | UbiSys Team, DTISI Division. Architected MuCAT multilingual transformer & Asthma multi-task IoT framework |
| **Freelance Software & AI Systems Engineer** | Independent Client Engineering | **Jan 2024 – Present** | Deployed commercial desktop systems (Electron), medical aesthetic EHR (Clinica Tajmeel), and enterprise DZD ERPs |

---

## 🏷️ System Classification Taxonomy
Every system in this portfolio is transparently labeled according to its engineering lifecycle:
-  — Empirical peer-reviewed architectures, ablation baselines, independent cross-validation splits, and peer technical reports.
-  — Deployed commercial software operating with real enterprise workflows, desktop OS integrations, and fiscal/POS compliance.
-  — Zero-install client-side WebAssembly / JS neural inference demonstrations for rapid accessibility.
-  — Orchestrated LLM execution graphs with tool-calling contracts, verification gates, and CI/CD evaluation harnesses.

---

## 🔬 Featured Research & Deep Learning Models (CERIST & USTHB)

| System / Repository | Classification | Architecture & Methodology | Quantitative Benchmarks & Clinical Validation | Links |
| :--- | :---: | :--- | :--- | :---: |
| **[AsthmaExpertUltra](https://github.com/HANIDEVINF/asthma-expert-ultra)**<br/>*Healthcare AI & Crisis Lead-Time* |  | **PyTorch Multi-Task Transformer**<br/>• 8 multimodal IoT streams (FEV1, PEF, SpO2, RR, HR, PM2.5, Pollen, Temp)<br/>• Dual MLP heads: 4-Class Crisis Severity + Lead-Time Horizon Bins<br/>• Dempster–Shafer evidential fusion ({	ext{IA}} \otimes m_{	ext{physio}}$)<br/>• Deterministic safety override ( < 50\%$) | • **76.0% Severity Accuracy** on patient-independent  (1,000 patients / 1,440h / zero patient leakage)<br/>• **69.0% Lead-Time Accuracy** (vs 61.8% XGBoost, 59.3% LSTM, 57.7% PatchTST)<br/>• **92.3% Severe Crisis Recall** via class-weighted Focal Loss ($\gamma=2$, =[1,5,5,10]$)<br/>• **< 1.0s Android PyTorch Lite** () edge runtime | [Repo & Research Report](https://github.com/HANIDEVINF/asthma-expert-ultra) · [Notebook](https://github.com/HANIDEVINF/asthma-expert-ultra/blob/main/AsthmaExpertUltra_FINALi.ipynb) |
| **[CardioWave v7 — ECG Arrhythmia Holter](https://github.com/HANIDEVINF/deep-learning-model-for-anomaly-detection-of-ECG)**<br/>*Biomedical Signal Deep Learning* |  | **Dual-Lead 1D-CNN + 2× Transformer + 8 RR Context Features**<br/>• Lead MLII + Lead V1 Butterworth bandpass filtered (0.5–45 Hz)<br/>• Standardized 8-feature RR timing branch (prematurity & compensatory ratios)<br/>• Dual-branch fusion into 5 AAMI heartbeat classes (N, S, V, F, Q) | • **87.63% Single-Fold / 90.13% 5-Fold Ensemble** on strict de Chazal MIT-BIH DS1/DS2 inter-patient split (49,668 held-out test beats)<br/>• **16.2% S-class sensitivity** & **0.529 macro-F1** under zero patient leakage<br/>• **155.4 KB INT8 TFLite** with **0.32 ms/beat edge latency** and **99.82% agreement** with FP32 Keras baseline | [Repo & Report](https://github.com/HANIDEVINF/deep-learning-model-for-anomaly-detection-of-ECG) |
| **[MuCAT — Multilingual Transformer](https://github.com/HANIDEVINF/MUCAT-Multilingual-Transformer)**<br/>*CERIST UbiSys DTISI Lab* |  | **Uncertainty-Calibrated Attention Transformer**<br/>•  backbone + Hierarchical Attention Pooling (HAP)<br/>• Language-Aware FiLM Gating (LAG) conditioning<br/>• Evidential Dirichlet head ( = K/S$) for single forward-pass epistemic uncertainty | • **98.20% Test Accuracy** across 6 languages & dialects: Modern Standard Arabic (ar), Algerian Darija (arq), Kabyle (kab), Chaoui (shy), French (fr), English (en)<br/>• Outperforms verified baselines (**81.40% XLM-RoBERTa**, **89.60% standard mDeBERTa-v3** under aligned label index mappings)<br/>• Calibrated vacuity for out-of-domain dialect abstention | [Repo](https://github.com/HANIDEVINF/MUCAT-Multilingual-Transformer) |
| **[MedGuardAI — Medical IoT & Telemedicine](https://github.com/HANIDEVINF/MED-Guard-AI.)**<br/>*Licence PFE Capstone (USTHB)* |  | **Embedded Telemetry & Telehealth Suite**<br/>• Raspberry Pi hardware sensor interfacing (ECG AD8232, MAX30102 SpO2, Glucose)<br/>• Flask/Python telemetry server + WebRTC video consultation<br/>• Cross-platform Flutter mobile application | • Real-time patient telemetry streaming with automated threshold breach alerts<br/>• Synchronized physician dashboard and prescription dispatch | [Repo](https://github.com/HANIDEVINF/MED-Guard-AI.) |

---

## 🤖 Agentic AI, RAG & LLM Infrastructure

| Project | Classification | Architecture & Focus | Key Deliverables & Validation | Links |
| :--- | :---: | :--- | :--- | :---: |
| **[EvalGate LLM Evaluation Framework](https://github.com/HANIDEVINF/llm-evaluation-framework)** |  | **MLOps & AI Safety Test Harness**<br/> ·  ·  | Automated 150-test benchmark suite, CI/CD regression gates for grounded faithfulness, policy compliance, latency & token cost Pareto frontier scoring. Distinguishes live scoring from offline benchmark runs. | [Live App](https://llm-evaluation-framework.vercel.app) · [Code](https://github.com/HANIDEVINF/llm-evaluation-framework) |
| **[VeriCite Hybrid RAG](https://github.com/HANIDEVINF/document-qa-rag)** |  | **Information Retrieval & Guardrails**<br/> +  | Reciprocal Rank Fusion (RRF), hallucination abstention gates, and dynamic PDF chunk ingestion | [Live App](https://document-qa-rag-sand.vercel.app) · [Code](https://github.com/HANIDEVINF/document-qa-rag) |
| **[VoxScribe Speech-to-Text & Clinical NLP](https://github.com/HANIDEVINF/speech-to-text-summarization)** |  | **Dual-Engine Speech Architecture**<br/> +  | Distinguishes browser-native Web Speech API dictation from an independent 16×32 FFT acoustic spectrogram classifier for clinical keyword trigger detection | [Live App](https://speech-to-text-summarization.vercel.app) · [Code](https://github.com/HANIDEVINF/speech-to-text-summarization) |
| **[GuardRail Neural Moderation](https://github.com/HANIDEVINF/content-moderation-system)** |  | **In-Browser Neural NLP**<br/> ·  | **99.1% test accuracy** on UCI SMS Spam Corpus with single-token marginal sigmoid risk attribution & live threshold calibration | [Live App](https://content-moderation-system-psi.vercel.app) · [Code](https://github.com/HANIDEVINF/content-moderation-system) |
| **[ResolveAI Multi-Agent Orchestrator](https://github.com/HANIDEVINF/multi-agent-support-bot)** |  | **Agentic Workflows**<br/> ·  | Autonomous intent routing across Triage, Billing, SRE Diagnostics & Retention specialists with auditable tool traces | [Live App](https://multi-agent-support-bot.vercel.app) · [Code](https://github.com/HANIDEVINF/multi-agent-support-bot) |
| **[OpsPilot SRE Incident Copilot](https://github.com/HANIDEVINF/containerized-ai-api-service)** |  | **Agentic SRE & Governance**<br/> ·  | Automated root-cause incident correlation with mandatory human SRE approval gates prior to production rollback execution | [Live App](https://containerized-ai-api-service.vercel.app) · [Code](https://github.com/HANIDEVINF/containerized-ai-api-service) |

---

## 🏢 Commercial Client Production Systems (Full-Stack & Desktop)

- **[Tadjmeel Clinica — Medical Aesthetic Platform & Desktop OS](https://github.com/HANIDEVINF/clinicatajmeel)** :  
  *Live Client:* Aesthetic Medicine Clinic in Algiers (*Splendor X Dual-Wavelength Laser, HydraFacial MD, LifU LinearZ HIFU*).  
  *Architecture:* Production web portal + synchronized **Doctor Consultation Queue** and **Receptionist Billing/Intake** desktop applications.  
  👉 **[Live Platform Demo](https://hanidevinf.github.io/clinicatajmeel/)** · **[Code Repository](https://github.com/HANIDEVINF/clinicatajmeel)**

- **[Enterprise DZD Business ERP, POS & G50 Fiscal Suite](https://github.com/HANIDEVINF/ecom-dashboard)** :  
  *Domain:* Multi-role Algerian enterprise management suite denominated in Algerian Dinars (DZD).  
  *Architecture:* 4-role RBAC (*Gérant, Caissier POS, Magasinier Stock, Comptable G50 Fiscal Ledger*), automated TVA 19% / TAP / G50 tax calculations, and 58-wilaya carrier tracking.  
  👉 **[Live Platform Demo](https://hanidevinf.github.io/ecom-dashboard/)** · **[Code Repository](https://github.com/HANIDEVINF/ecom-dashboard)**

- **[ALLURE HOMME · GK STORE · CASUAL 29 — Retail & Manager OS](https://github.com/HANIDEVINF/allure)** :  
  *Live Clients:* 3 menswear retail stores in **Algiers (Birkhadem)**, **Sidi Bel Abbès (22)**, and **Mascara (29)**.  
  *Architecture:* Multi-brand responsive storefronts with 58-wilaya Yalidine/ZR Express shipping calculators, COD order dispatch, and standalone *OS Gérant* inventory control.  
  👉 **[Live Platform Demo](https://hanidevinf.github.io/allure/)** · **[Code Repository](https://github.com/HANIDEVINF/allure)**

- **[AcademiaPro — Modern EdTech Online Learning Academy](https://github.com/HANIDEVINF/edtech)** :  
  *Domain:* Commercial education platform with course catalogs, interactive video player, enrolled student dashboards, syllabus tracking, and instructor analytics.  
  👉 **[Code Repository](https://github.com/HANIDEVINF/edtech)**

---

## 🛡️ Intellectual Property & Verification Notice

Repositories contain complete model training notebooks, research technical reports, architectural documentation, and production frontend/backend code designed for peer review, academic evaluation, and technical hiring verification. Direct cloning, commercial redistributions, or unauthorized scraping of proprietary client datasets and enterprise logic are subject to intellectual property protections.

---

## 🛠️ Core Technical Stack

- **Deep Learning & Medical AI:** PyTorch, TensorFlow / Keras, Hugging Face Transformers, Custom Attention Layers, 1D-CNN / BiLSTM, TFLite INT8 Quantization, PyTorch Lite (), Dempster–Shafer Fusion, Focal Loss, Scikit-learn, SciPy DSP (Butterworth, Pan-Tompkins).
- **LLMs & Agentic Systems:** ReAct Agent DAGs, JSON Tool Calling Contracts, Vector Search & Hybrid RAG (Dense + BM25), LLM-as-a-Judge Evaluation, Guardrails & Policy Enforcement.
- **Full-Stack & Systems:** Python (FastAPI, Flask), TypeScript, Next.js 15, React 19, Tailwind CSS, Electron (Cross-Platform Desktop), Node.js, REST APIs, WebSockets.
- **Data & DevOps:** PostgreSQL, SQLite, MongoDB, Docker, Git/GitHub CI/CD, Linux.
- **Mobile & IoT:** Flutter (Dart), Raspberry Pi, Medical Sensor Interfacing (ECG AD8232, Pulse Oximetry MAX30102, Continuous Glucose Telemetry).

---

<p align=center>
  <sub>Engineered by <b>Hani Ghena</b> · Algiers, Algeria</sub>
</p>

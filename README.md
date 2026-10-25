<!-- Profile README for https://github.com/HANIDEVINF -->
<div align="center">

# Ghena Hani
### AI Engineering MSc Student · Applied AI · NLP & Deep Learning

Building and evaluating AI systems — from multilingual transformers and biomedical time-series models to LLM applications and practical software.

<p>
  <a href="https://myportfolio-rho-seven-15.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-Visit%20my%20work-6C63FF?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/ghena-hani-3543a3375/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:hanighena4@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

</div>

---

## 👋 About me

I’m a Master's student in **Artificial Intelligence Engineering at USTHB** with research experience at **CERIST** and hands-on work spanning machine learning, multilingual NLP, deep learning, model evaluation, and AI-powered applications.

I enjoy the engineering behind the model as much as the model itself: preparing data, designing experiments, comparing baselines, measuring failure cases, and turning working research into software that people can interact with.

- 🔬 **Research interests:** NLP, transformer architectures, trustworthy AI, uncertainty estimation, biomedical signals.
- 🧪 **Model development:** training and evaluation workflows with PyTorch, TensorFlow/Keras, and Hugging Face.
- 🧰 **AI engineering:** LLM applications, retrieval-augmented generation (RAG), APIs, and web interfaces.
- 🎯 **Current goal:** contribute to an Applied AI / ML Engineering team where rigorous evaluation and useful implementation both matter.

> I aim to document what a project actually does, how it was evaluated, and where its limitations remain. Metrics below are repository-reported results, not claims of clinical validation or independent reproduction.

## 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

### 🗣️ MuCAT — Multilingual Transformer
**Research · NLP · Transformers**

A multilingual text-classification research implementation using an mDeBERTa-v3 backbone with:
- Hierarchical Attention Pooling (HAP)
- Language-aware FiLM conditioning
- Evidential Dirichlet output head
- Auxiliary script prediction

Designed around MSA, Algerian Darija, Kabyle, Chaoui, French, and English.

**Evaluation note:** the repository reports 98.20% test accuracy and includes a label-mapping correction. Review its split, baselines, and evaluation notes before interpreting the score.

[**Repository →**](https://github.com/HANIDEVINF/MUCAT-Multilingual-Transformer)

</td>
<td width="50%" valign="top">

### ❤️ ECG Arrhythmia Classification v7
**Deep Learning · Healthcare Research · Edge**

A 1D-CNN + Transformer model for MIT-BIH ECG beat classification, with a patient-wise DS1/DS2 evaluation setup and an INT8 TensorFlow Lite export.

- Reported ensemble accuracy: **90.13%**
- Reported macro-F1: **0.529**
- Reported INT8 model size: **about 155 KB**

**Important limitation:** sensitivity for the S class is low in the reported evaluation. This is an experimental project, not a clinically validated diagnostic system.

[**Repository →**](https://github.com/HANIDEVINF/deep-learning-model-for-anomaly-detection-of-ECG)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧭 LLM Evaluation Framework
**LLMs · Evaluation · Developer Tools**

An evolving project exploring structured evaluation for LLM-powered applications. The goal is to make evaluation criteria, comparisons, and results easier to inspect than a single impressive demo.

See the repository for the functionality currently implemented and its reproduction instructions.

[**Repository →**](https://github.com/HANIDEVINF/llm-evaluation-framework) · [**Live demo →**](https://llm-evaluation-framework.vercel.app/)

</td>
<td width="50%" valign="top">

### 🩺 MedGuardAI
**Academic Project · Health IoT · Application Engineering**

An academic capstone exploring medical monitoring and telehealth workflows, combining an application interface with backend and sensor-oriented components.

Refer to the repository for implementation details. Any demo readings or simulated device states should be understood as demonstrations, not real patient monitoring.

[**Repository →**](https://github.com/HANIDEVINF/MED-Guard-AI)

</td>
</tr>
</table>

## 🧠 Technical toolkit

<table>
<tr>
<td valign="top" width="50%">

**AI & Machine Learning**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**LLM application development**

![RAG](https://img.shields.io/badge/RAG-Retrieval%20Pipelines-6C63FF?style=flat-square)
![NLP](https://img.shields.io/badge/NLP-Text%20Processing-0A9396?style=flat-square)
![Evaluation](https://img.shields.io/badge/LLM-Evaluation-495057?style=flat-square)

</td>
<td valign="top" width="50%">

**Software engineering**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)

**Data & deployment**

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![TFLite](https://img.shields.io/badge/TFLite-Edge%20Inference-FF6F00?style=flat-square)

</td>
</tr>
</table>

## 🔬 How I approach AI projects

1. **Define the task and data** — identify labels, splits, data quality risks, and the intended use.
2. **Establish a baseline** — compare against a simpler or established method before claiming an improvement.
3. **Evaluate beyond accuracy** — inspect macro-F1, per-class recall, confusion matrices, and relevant failure cases.
4. **Make results reproducible** — document dependencies, configuration, evaluation protocol, and limitations.
5. **Build for use** — where appropriate, connect models to APIs, interfaces, or edge-compatible exports.

## 🎓 Education & experience

- **M.Sc. — Artificial Intelligence Engineering**, USTHB (in progress)
- **Licence — Computer Science**, USTHB
- **AI research internship experience**, CERIST
- **Independent AI and software projects**, including model experimentation and application development

For exact dates, responsibilities, and current project status, please refer to my CV, LinkedIn, and the individual repositories.

## 📬 Let’s connect

Interested in junior Applied AI / Machine Learning Engineering opportunities, AI research collaborations, and projects involving NLP, transformers, LLM applications, or model evaluation.

<p align="center">
  <a href="https://myportfolio-rho-seven-15.vercel.app/">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/ghena-hani-3543a3375/">LinkedIn</a> ·
  <a href="mailto:hanighena4@gmail.com">Email</a>
</p>

<div align="center">
  <sub>Built with curiosity, careful experiments, and a commitment to documenting limitations as well as results.</sub>
</div>

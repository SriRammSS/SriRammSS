<div align="center">

# Hey, I'm Sri Ramm 

### ML Engineer · LLM Systems · Multimodal AI

*From debugging 5G radio stacks at Mavenir to building production ML pipelines at UMD —*
*I'm drawn to problems where models meet the real world.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sri_Ramm_Sekar_Sasirekha-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sri-ramm-sekar-sasirekha-1b52aa1a2/)
[![Email](https://img.shields.io/badge/Email-srirammss13@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:srirammss13@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-SriRammSS-181717?style=flat&logo=github)](https://github.com/SriRammSS)

</div>

---

## A little about me

I'm currently an MS student in **Applied Machine Learning at the University of Maryland, College Park** — but my path here wasn't a straight line.

I spent two years at **Mavenir Systems** as a 5G systems engineer, doing drive tests, analyzing Grafana/Prometheus logs, and debugging O-RAN deployments in the field. That hands-on experience with real-world data — messy, sparse, domain-specific — shaped how I think about ML now. I don't just want to run models; I want to understand *why* they work and *where* they fail.

My sweet spot is the intersection of **LLMs, multimodal AI, and real-world deployment** — building systems where a model doesn't just predict but actually helps someone make a decision.

When I'm not in the ML weeds, I published an IEEE paper on transfer learning for lung cancer detection, won a hackathon with a computer vision recovery app, and built a privacy-first local RAG system that runs entirely on-device.

---

## What I'm working on

```
 MS Applied Machine Learning @ UMD College Park  (Sep 2025 – Present)
 Privacy-first RAG systems · Applied deep learning · LLM pipelines
```

---

## Things I actually know well

**LLMs & NLP**

![Transformers](https://img.shields.io/badge/HuggingFace-Transformers-FFD21F?style=flat&logo=huggingface&logoColor=black)
![Ollama](https://img.shields.io/badge/Ollama-Local_LLM-000000?style=flat)
![RAG](https://img.shields.io/badge/RAG-pgvector_%2B_Ollama-4169E1?style=flat&logo=postgresql&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-121212?style=flat)

Prompt engineering · NER & information extraction · Multimodal reasoning · RAG pipelines · Structured LLM outputs

**ML / DL**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat)

Computer vision (VGG19, MediaPipe) · Transfer learning · Anomaly detection · Bayesian models · Causal inference

**Backend & Data**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat&logo=celery&logoColor=white)

FastAPI · Celery · Redis · PostgreSQL + pgvector · SQLAlchemy · Alembic

---

## Projects I'm proud of

<table>
<tr>
<td width="50%" valign="top">

### Local RAG System
*FastAPI · pgvector · Ollama · React*

Privacy-first document Q&A — upload PDFs, embed with `nomic-embed-text`, query with `llama3.1:8b` or `llama3.3:70b`. Clean layered architecture with abstract LLM/embedding interfaces so you can swap inference backends without touching the RAG pipeline.

[→ View repo](https://github.com/SriRammSS/rag-local-app)

</td>
<td width="50%" valign="top">

### 5G QoS Prediction
*XGBoost · LightGBM · Random Forest · PCA*

End-to-end ML pipeline on real O-RAN drive test data. Ensemble model (XGB + LGB + RF) achieves **R² = 0.96** predicting downlink throughput from radio signal metrics. Designed a 3GPP-compliant signal imputation algorithm to reconstruct 40% missing SCell measurements.

[→ View repo](https://github.com/SriRammSS/5GQoS-Analysis)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Komrade — Veteran Peer Support
*FastAPI · React · PostgreSQL · MongoDB · WebSockets*

Real-time SOS alert platform for veterans — geospatial buddy matching (haversine), dual AI provider (Gemini/Ollama), ElevenLabs STT, and hard-wired crisis interception routing to 988 Lifeline before any AI call is made.

[→ View repo](https://github.com/SriRammSS/komrade)

</td>
<td width="50%" valign="top">

### Snack Stalker
*React 19 · Express 5 · PostgreSQL · RTK Query*

Multi-university campus vending machine platform with Leaflet campus maps, QR payment simulation, and sustainability tracking. Full monorepo with admin dashboard, analytics, and real-time inventory management.

[→ View repo](https://github.com/SriRammSS/snack-stalker)

</td>
</tr>
</table>

---

## IEEE Publication

> **Cross-Organ Bridge Transfer Learning for Lung Cancer Detection**
> *IEEE R10-HTC 2023 · DOI: [10.1109/R10-HTC57504.2023.10461796](https://doi.org/10.1109/R10-HTC57504.2023.10461796)*

Proposed **modality-bridge transfer learning** — training VGG19 on kidney CT scans as an intermediate domain, then transferring to lung cancer classification. The same-CT-modality bridge improved accuracy from 90% → **93%** while cross-modality bridging (USG → CT) degraded to 75%, validating that modality alignment is the key factor.

[→ View repo](https://github.com/SriRammSS/tumor-classification)

---

## GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=SriRammSS&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SriRammSS&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />

</div>

---

## Background

```
2025 – Now MS Applied Machine Learning · University of Maryland, College Park
2024 – 2025 Member of Technical Staff-I · Mavenir Systems (5G O-RAN, ML on telco data)
2023 – 2024 Graduate Engineer · Mavenir Systems (5G SA system testing, Dish Wireless)
Jan–Jun 2023 Graduate Engineer Intern · Mavenir Systems
2023 IEEE Publication · Cross-Organ Bridge Transfer Learning
2023 Hackathon Winner — Best Startup Idea (CV-based postpartum recovery app)
2019 – 2023 B.Tech ECE · Amrita School of Engineering, Coimbatore
```

---

<div align="center">

*Always up for a conversation about LLMs, applied AI, or why 5G networks are actually fascinating.*

[![LinkedIn](https://img.shields.io/badge/Let's_connect-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sri-ramm-sekar-sasirekha-1b52aa1a2/)

</div>

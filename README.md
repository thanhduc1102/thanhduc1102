<!-- Banner: auto dark/light -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img alt="Do Thanh Duc — AI Engineer · NLP & LLM Researcher" src="assets/banner-light.svg">
</picture>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&random=false&width=720&lines=AI+Engineer+%40+MobiFone+(Core+NLP+Team);Multi-Agent+Systems+%7C+Enterprise+RAG+%7C+LangGraph;Speech+%2F+ASR+%40+Samsung+R%26D+Vietnam;Financial+Numerical+QA+%7C+VLSP+2026+%7C+CLEF+2026" alt="Typing SVG"/>
</p>

<p align="center">
  <a href="mailto:do.thanh.duc.2002@gmail.com">
    <img src="https://img.shields.io/badge/Email-do.thanh.duc.2002%40gmail.com-informational?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="mailto:duc.dt242095m@sis.hust.edu.vn">
    <img src="https://img.shields.io/badge/HUST-duc.dt242095m-B71C1C?style=for-the-badge&logo=academia&logoColor=white" alt="HUST email"/>
  </a>
  <a href="https://github.com/thanhduc1102">
    <img src="https://img.shields.io/badge/GitHub-thanhduc1102-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Hanoi-Viet%20Nam-orange?style=flat-square&logo=google-maps&logoColor=white" alt="Location"/>
  <img src="https://komarev.com/ghpvc/?username=thanhduc1102&label=Profile%20views&style=flat-square" alt="Visitors"/>
</p>

---

## 🧑‍💻 About me

> AI Engineer & MSc student — I build **production LLM systems** (agents, RAG, speech) and do research on **trustworthy, retrieval-grounded reasoning** over documents.

- 🏢 **AI Engineer @ MobiFone IT Center** (Core NLP Team) — multi-agent systems & enterprise RAG chatbots
- 🎙️ Previously **AI Engineer @ Samsung R&D Vietnam** (ASR Team) — Whisper / Wav2Vec2 / NeMo for on-device voice AI
- 🎓 **MSc, Computer Science** @ HUST (Oct 2024 – Present) · BSc, Very Good, **CPA 3.59/4.0**
- 🔬 Research: financial numerical QA, fact-level retrieval & selective answering, neurosymbolic QA, Vietnamese NLP
- 🏁 Shared tasks: **VLSP 2026** (ViNumQA / ViTNumChart) · **CLEF 2026 FinMMEval** · **IJCNN 2025** Neurosymbolic AI challenge

---

## 💼 Experience

### <img src="https://img.shields.io/badge/Current-00c853?style=flat-square" alt="Current"/> MobiFone IT Center — AI Engineer (Core Team) · Aug 2025 – Present

<details>
<summary>🤖 <b>1POS AI Agent</b> — Multi-agent AI system for F&B / Retail (Jan 2026 – Mar 2026)</summary>
<br/>

- Architected a **multi-agent** system that turns natural-language business questions into tool executions
- **LangGraph** orchestration + **Tool Registry Pattern** (auto-registration, schema validation, modular tools)
- Deep integration with **1POS / 1ERP** APIs: revenue, inventory, promotions, business reports
- **FastAPI** service layer, deployed with **Docker + NGINX** reverse proxy
</details>

<details>
<summary>💬 <b>Personal Assistance Chatbot</b> — Enterprise RAG with LangGraph (Sep 2025 – Jan 2026)</summary>
<br/>

| Component | Details |
|-----------|---------|
| **Core** | RAG + LangGraph workflows for Q&A over internal documents; recursive summarization, key-insight extraction, secure APIs |
| **Query rewrite** | GPT-OSS-20B rewriter → **+12.5% NDCG@5** on natural user queries |
| **Evaluation** | LLM-as-a-Judge on 482 questions: **Answer Relevancy 0.85**, **Completeness 0.84** (on par with GPT-4o) |
| **Infra** | H100 cluster · async FastAPI · PostgreSQL/pgvector · Redis · MinIO |
</details>

### <img src="https://img.shields.io/badge/2024--2025-1e88e5?style=flat-square" alt="2024-2025"/> Samsung R&D Vietnam — AI Engineer (ASR Team) · Apr 2024 – Jul 2025

<details>
<summary>🗣️ <b>Thai ASR Model Training & Evaluation</b> (Dec 2024 – May 2025)</summary>
<br/>

- Trained & evaluated **Whisper, Wav2Vec2** and **NeMo 2.0 / RNN-T** pipelines for mobile speech recognition
- Data prep → fine-tuning → evaluation on **4× A100 40GB** with **Kubeflow (AWS)**, reproducible containerized jobs
- Data cleaning & checkpoint management for **~2M audio samples** (4–25 s each)
- Content accuracy **~86% → ~96%** on a private dataset after fine-tuning; contributed to the Bixby / mobile assistant ASR pipeline
</details>

<details>
<summary>🎛️ <b>Audio Data Augmentation Tool</b> for Speech / ASR (Aug 2024 – Apr 2025)</summary>
<br/>

- Configurable augmentation: noise injection, speed/volume perturbation, **RIR simulation**
- Transcript normalization (regex, character normalization, annotation-noise filtering) to align audio–text
- Voice filtering & speaker verification to raise dataset quality and robustness across acoustic conditions
</details>

### <img src="https://img.shields.io/badge/Research-8e24aa?style=flat-square" alt="Research"/> BK.AI Lab, SoICT – HUST — Research Assistant · Sep 2023 – Sep 2024

- NLP research with **Assoc. Prof. Le Thanh Huong**: text summarization, information extraction, information retrieval
- LLMs, reinforcement learning, model training and knowledge graphs

### <img src="https://img.shields.io/badge/Intern-ff9800?style=flat-square" alt="Intern"/> Aimesoft — NLP Intern · Mar 2023 – Sep 2023

- ML/DL for classification and POS tagging; web data extraction, dataset building and cleaning

---

## 🔬 Research & Projects

| Project | Area | Highlights |
|---------|------|-----------|
| **LEDGER** — Disentangled Fact-Level Retrieval for Financial Documents | KG-RAG · Financial QA | Fact-level retrieval & selective answering for numerical QA over financial reports *(paper in progress)* |
| **VLSP 2026 ViNumQA / ViTNumChart** | Program generation · Multimodal QA | Program-of-thought generation for Vietnamese financial QA over text, tables and charts |
| **CLEF 2026 FinMMEval** | Financial multimodal evaluation | Unified pipeline for financial multimodal / multilingual QA tasks |
| **Gemma 4 Developer Agent** (Kaggle) | AI Agents | Research lab and Gemma-first agent bundles |
| [**Adaptive Information Retrieval**](https://github.com/thanhduc1102/adaptive-information-retrieval) | IR | Adaptive retrieval experiments |
| **Explainable AI for Educational QA** (Neurosymbolic) | NL→FOL · Theorem proving | RAG (FAISS) + T5 verifier → 60–70% valid FOL; Prover9 step-by-step proofs; **50% on FOLIO**, top-7 at IJCNN 2025 challenge |
| **Vietnamese Legal RAG QA** | RAG · Legal | 1.2M+ provisions, 2,000 questions, **Recall/MAP ≈ 0.88**; Streamlit + Firestore + Qdrant |
| **Vietnamese Multi-Document Summarization** (BSc thesis) | LLM fine-tuning | Vistral-7B / VinaLLaMA + LexRank / MMR; Abmusu **ROUGE-1 69.52 / ROUGE-2 37.94 / ROUGE-L 37.30** |
| [**Knowledge Distillation for ViQA**](https://github.com/thanhduc1102/Knowledge_distill_VIQA) | Vietnamese QA | Knowledge distillation for Vietnamese question answering |
| [**Emotion Recognition**](https://github.com/thanhduc1102/emotionRecogApp) · [**Physiological**](https://github.com/thanhduc1102/emotionPhysiological) | CV · Signals | Emotion recognition from faces and physiological signals |
| [**HPC**](https://github.com/thanhduc1102/hpc) | CUDA · Parallel computing | High-performance computing coursework (CUDA reductions, parallel algorithms) |

---

## 🛠️ Tech Stack

**AI / NLP / Speech**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain%20%2F%20LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![NVIDIA NeMo](https://img.shields.io/badge/NVIDIA%20NeMo-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Whisper](https://img.shields.io/badge/Whisper%20%7C%20Wav2Vec2-412991?style=flat-square&logo=openai&logoColor=white)
![LLMs](https://img.shields.io/badge/Llama%20%7C%20Qwen%20%7C%20Gemma%20%7C%20Vistral-6E56CF?style=flat-square)

**Retrieval / Data**

![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL%20%2B%20pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=flat-square&logo=minio&logoColor=white)
![Firebase](https://img.shields.io/badge/Firestore-FFCA28?style=flat-square&logo=firebase&logoColor=black)

**Backend / MLOps**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![NGINX](https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=nginx&logoColor=white)
![Kubeflow](https://img.shields.io/badge/Kubeflow%20(AWS)-326CE5?style=flat-square&logo=kubeflow&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

---

## 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=thanhduc1102&show_icons=true&count_private=true&include_all_commits=true&hide_border=true&theme=tokyonight" alt="GitHub stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=thanhduc1102&layout=compact&hide_border=true&theme=tokyonight" alt="Top languages"/>
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=thanhduc1102&hide_border=true&theme=tokyonight" alt="GitHub streak"/>
</p>

---

## 🎓 Education

| Degree | Institution | Period |
|--------|-------------|--------|
| **MSc, Computer Science** | Hanoi University of Science and Technology (HUST) | Oct 2024 – Present |
| **BSc, Computer Science** — Very Good, CPA 3.59/4.0 | Hanoi University of Science and Technology (HUST) | Oct 2020 – Sep 2024 |

---

<p align="center">
  <i>Open to research collaborations on LLMs, RAG, AI agents and document intelligence — feel free to reach out!</i>
</p>

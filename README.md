<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=6366F1&center=true&vCenter=true&width=700&lines=Hi%2C+I'm+Nozima+Abduazizova+%F0%9F%91%8B;Data+Scientist+%7C+CV+%26+ML+Engineer;Gait+Analysis+%7C+VLM+Evaluation;Building+AI+systems+that+work+in+production" alt="Typing SVG" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://kaggle.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AbduazizovaNozima)

</div>

---

## About Me

Data Scientist with strong hands-on experience in **Computer Vision**, **Deep Learning**, and **NLP/LLM systems**. I build production-oriented AI pipelines — from dataset collection and model benchmarking to deployment with Docker and FastAPI.

- **Strongest area:** Computer Vision — pose estimation, gait analysis, object detection, VLM evaluation
- **Also solid in:** Backend (FastAPI, Django, PostgreSQL, Redis, Docker), classical ML, RAG systems
- Based in **Uzbekistan** 🇺🇿 | Open to remote opportunities

---

## Tech Stack

**Machine Learning & Deep Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Scikit--learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)

**Computer Vision**

![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO_v8--v11-00FFFF?style=flat-square&logo=opencv&logoColor=black)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square&logo=google&logoColor=white)
![SAM2](https://img.shields.io/badge/SAM2-4A90D9?style=flat-square&logo=meta&logoColor=white)

**NLP / LLM / VLM**

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Whisper](https://img.shields.io/badge/Whisper_STT-412991?style=flat-square&logo=openai&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**Backend & MLOps**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

---

## Featured Projects

### 🦾 Gait Analysis — Human Movement Classification
> Walking video analysis pipeline for clinical gait assessment

**What it does:** Classifies human gait from video into `Healthy / Limping / Wheelchair / Amputee` using pose estimation and ensemble voting.

**Models benchmarked:** YOLOv11-Pose · MediaPipe · SMPLest-X · VideoMAE · MotionBERT · Qwen-VL · Llama Vision · Gemma Vision

| Metric | Result |
|--------|--------|
| Best ensemble accuracy | **70.31%** |
| Evaluation samples | 64 videos |
| Pose models tested | 4 |
| VLMs tested | 4+ |

`PyTorch` `YOLO Pose` `MediaPipe` `VLM` `Ensemble` `SMPL` `OpenCV`

---

### 🍽️ Table Cleanliness Detection
> Real-time CCTV-based restaurant table state classification

**Pipeline:** CCTV frame → YOLO detection → table tracking → rule engine → `Clean / Dirty / Occupied` → timer → CSV/JSON output

- Collected & audited 7,000+ images across 11 Roboflow datasets
- Reduced 29-class annotations to 9 production-relevant classes
- Built custom tracking + spatial association logic

| Metric | Result |
|--------|--------|
| Tables detected (30 test images) | 249 instances |
| Detection rate | 25/30 images |

`YOLOv11` `ByteTrack` `OpenCV` `Docker` `Qwen-VL` `Rule Engine`

[**→ View Repository**](https://github.com/AbduazizovaNozima/table-cleanliness-detection)

---

### ⚖️ LexAI — Uzbek Legal Assistant
> RAG system for answering legal questions from Uzbekistan law (Lex.uz)

- Semantic search over 25,000+ legal documents via **pgvector**
- Multi-turn conversation with session memory
- Telegram bot + REST API
- Automatic law scraper to keep data up to date

`FastAPI` `PostgreSQL + pgvector` `OpenAI` `RAG` `Aiogram` `Docker`

[**→ View Repository**](https://github.com/AbduazizovaNozima/lex_uz_project_with_agent)

---

### 👗 AI Stylist
> Multimodal fashion assistant with virtual try-on

- Outfit analysis from uploaded photos (Qwen2.5-VL)
- Smart suggestions using Polyvore fashion dataset embeddings
- Zara product search via ChromaDB (Lens feature)
- Full-stack: FastAPI backend + React/Vite frontend

`FastAPI` `React` `Qwen-VL` `ChromaDB` `Ollama` `Docker`

[**→ View Repository**](https://github.com/AbduazizovaNozima/ai-stylist)

---

### 📝 ExamAI — Automated Exam Grading
> OCR + LLM pipeline for bubble-sheet answer form grading

- Computer vision bubble detection from answer sheet photos
- LLM-assisted grading and analytics
- Speech-to-text for audio question input
- Next.js dashboard with per-exam statistics

`FastAPI` `OpenAI` `OCR` `Next.js` `Docker`

[**→ View Repository**](https://github.com/AbduazizovaNozima/ocr_model)

---

## ML From Scratch

I've implemented core ML algorithms from scratch (without sklearn) to deeply understand the math:

| Algorithm | Task |
|-----------|------|
| Linear Regression | Student grade prediction (MSE, gradient descent) |
| Logistic Regression | Credit approval (sigmoid, binary classification) |
| Naive Bayes | Spam classification (Laplace smoothing, tokenization) |
| K-Means | Customer segmentation (Euclidean distance) |
| Cosine Similarity | Document similarity |

---

## GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=AbduazizovaNozima&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AbduazizovaNozima&layout=compact&theme=tokyonight&hide_border=true" />

</div>

<div align="center">

![GitHub Streak](https://streak-stats.demolab.com?user=AbduazizovaNozima&theme=tokyonight&hide_border=true)

</div>

---

<div align="center">
<i>Open to Data Scientist / ML Engineer roles — especially in CV, NLP, and production AI systems</i>
</div>

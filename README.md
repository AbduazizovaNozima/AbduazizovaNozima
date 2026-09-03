<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1000&color=6366F1&center=true&vCenter=true&width=750&lines=Hi%2C+I'm+Nozima+Abduazizova+%F0%9F%91%8B;Data+Scientist+%7C+CV+%26+ML+Engineer;Gait+Analysis+%7C+VLM+Evaluation+%7C+RAG;Building+AI+systems+that+work+in+production" alt="Typing SVG" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nozima-abduazizova-2a451334b/)
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/abduaz1zova)

</div>

---

## About Me

Data Scientist with hands-on experience across the full ML pipeline — from data collection and EDA to model training, evaluation, and production deployment. My strongest area is **Computer Vision**: pose estimation, gait analysis, object detection, and multimodal model benchmarking.

Beyond modeling, I build the backend infrastructure around AI systems — REST APIs, containerized deployments, and async pipelines — so models actually run reliably in production.

- **Core focus:** Computer Vision · Deep Learning · NLP/LLM · RAG systems
- **Also solid in:** FastAPI · Django · PostgreSQL · Docker · Redis
- Based in **Uzbekistan** 🇺🇿

---

## Tech Stack

**Core Data Science**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Statistics](https://img.shields.io/badge/Statistics-EDA-8B5CF6?style=flat-square)

**Machine Learning**

![Regression](https://img.shields.io/badge/Regression-6366F1?style=flat-square)
![Classification](https://img.shields.io/badge/Classification-6366F1?style=flat-square)
![Clustering](https://img.shields.io/badge/Clustering-6366F1?style=flat-square)
![Feature Engineering](https://img.shields.io/badge/Feature_Engineering-6366F1?style=flat-square)
![Model Evaluation](https://img.shields.io/badge/Model_Evaluation-6366F1?style=flat-square)

**Deep Learning / Computer Vision**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![YOLO](https://img.shields.io/badge/YOLO_v8--v11-00FFFF?style=flat-square&logo=opencv&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square&logo=google&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)

**Backend / Production ML**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

---

## Featured Projects

### 🦾 Gait Analysis — Clinical Human Movement Classification

A production-oriented video analysis pipeline for classifying human gait patterns from walking footage. The system extracts skeletal keypoints, computes motion features, and classifies gait into clinically meaningful categories using an ensemble of pose and vision-language models.

Researched, benchmarked, and compared multiple model families — from lightweight pose estimators to large VLMs — selecting the best combination for accuracy and inference speed. Built rule-based validation on top of model outputs to reduce false positives in edge cases.

**Models benchmarked:** YOLOv11-Pose · MediaPipe · SMPLest-X · VideoMAE · MotionBERT · Qwen-VL · Llama Vision · Gemma Vision

`PyTorch` `YOLO Pose` `MediaPipe` `SMPL` `VLM Evaluation` `Ensemble` `OpenCV` `CUDA`

---

### 🍽️ Table Cleanliness Detection — Real-Time Restaurant Monitoring

End-to-end computer vision system for classifying restaurant table states (Clean / Dirty / Occupied) from CCTV footage. Covers the full pipeline from dataset research and collection to inference, tracking, and structured output.

Collected and audited a multi-source dataset from Roboflow, HuggingFace, and GitHub. Reduced a 29-class annotation schema to 9 production-relevant classes. Built custom object-table spatial association logic and a rule engine on top of YOLO detections, with a cleaning timer and CSV/JSON reporting.

**Models used:** YOLOv11 · Qwen-VL · ByteTrack

`YOLOv11` `ByteTrack` `Qwen-VL` `OpenCV` `Docker` `Rule Engine` `Dataset Engineering`

[**→ View Repository**](https://github.com/AbduazizovaNozima/table-cleanliness-detection)

---

### ⚖️ LexAI — Uzbek Legal Q&A System

RAG-based legal assistant that answers questions about Uzbekistan law using documents scraped directly from the official [Lex.uz](https://lex.uz) database. Combines semantic search via pgvector with a multi-turn conversational agent, exposed through both a REST API and a Telegram bot interface.

`FastAPI` `PostgreSQL + pgvector` `OpenAI` `RAG` `Aiogram` `Docker`

[**→ View Repository**](https://github.com/AbduazizovaNozima/lex_uz_project_with_agent)

---

### 👗 AI Stylist — Multimodal Fashion Assistant

Full-stack AI fashion advisor that analyzes outfit photos, generates style recommendations, and supports virtual try-on. Uses vision-language models for image understanding and ChromaDB embeddings for product similarity search across a Zara fashion dataset.

`FastAPI` `React` `Qwen-VL` `ChromaDB` `Ollama` `PostgreSQL` `Docker`

[**→ View Repository**](https://github.com/AbduazizovaNozima/ai-stylist)

---

### 📝 ExamAI — AI-Powered Exam Grading

Automated grading system for multiple-choice bubble-sheet answer forms. Combines OCR-based bubble detection with LLM-assisted scoring, speech-to-text question input, and a Next.js analytics dashboard for per-exam and per-student performance tracking.

`FastAPI` `OpenAI` `OCR` `Whisper` `Next.js` `Docker`

[**→ View Repository**](https://github.com/AbduazizovaNozima/ocr_model)

---

## ML From Scratch

Core ML algorithms implemented from scratch — no sklearn — to build a solid mathematical foundation:

| Algorithm | Application |
|-----------|-------------|
| Linear Regression | Grade prediction · gradient descent · MSE |
| Logistic Regression | Credit approval · sigmoid · binary classification |
| Naive Bayes | Spam detection · Laplace smoothing · tokenization |
| K-Means | Customer segmentation · Euclidean distance |
| Cosine Similarity | Document similarity · vector representation |

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
<i>Open to Data Scientist · ML Engineer · CV Engineer roles — remote or Uzbekistan-based</i>
</div>

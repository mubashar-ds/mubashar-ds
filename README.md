# Hi, I'm Mubashar Hussain 

**AI Engineer | M.S. Data Science | LLMs, RAG & Agentic AI | LangGraph, FastAPI & Vector Databases**

I build practical AI systems that combine **machine learning,
information retrieval, LLM applications, backend engineering, and data
infrastructure**.

My work sits at the intersection of **AI capabilities and reliable
engineering** — from retrieval and model evaluation to APIs,
databases, Docker, and cloud-connected systems.

<p align="left">
  <a href="https://www.linkedin.com/in/mubashar-ds">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:mubashar.itu@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

------------------------------------------------------------------------

## About Me

-   **M.S. in Data Science**, Information Technology University
    (ITU), Lahore
-   Focused on **LLM applications, RAG, agentic workflows,
    information retrieval, and AI systems**
-   Strong ML/DL background with **PyTorch, computer vision, NLP, and
    explainable AI**
-   Interested in how retrieval systems find evidence, how models use
    tools and context, and how AI applications become reliable software
    systems
-   Build backend services with **Python, FastAPI, SQL, PostgreSQL,
    vector databases, and Docker**
-   Experienced with retrieval and ML evaluation rather than relying
    only on qualitative demos
-   Hands-on cloud experience with **AWS S3**, with ongoing work in deployment and cloud architecture
-   M.S. thesis: **Towards Lightweight and Explainable Deepfake
    Speech Detection Systems**
-   **First-author research paper to IEEE Signal Processing Letters (IEEE SPL)** based on
    thesis work

------------------------------------------------------------------------

## What I Build

### LLMs, RAG & Agentic AI

I work on AI applications that connect language models with retrieval,
tools, structured outputs, and application logic.

**Focus areas:** - LLM Applications & LLM APIs - Retrieval-Augmented
Generation (RAG) - Dense & sparse retrieval - Embeddings & semantic
search - Prompt engineering - LangChain - LangGraph - Tool / function
calling - Structured outputs - Stateful workflows

### Information Retrieval

Retrieval is one of my strongest technical interests, including both
classical lexical search and modern semantic retrieval.

**Techniques:** - BM25 - TF-IDF - Dense embeddings - Sparse lexical
retrieval - Hybrid retrieval - Boolean & phrase queries - Metadata
filtering - Precision@K - Recall@K - MRR - nDCG

### Machine Learning & Deep Learning

-   PyTorch
-   scikit-learn
-   Hugging Face Transformers
-   Machine Learning
-   Deep Learning
-   NLP
-   Computer Vision
-   OpenCV
-   Explainable AI
-   Audio ML / speech deepfake detection
-   Model evaluation under domain shift and compression

### AI Engineering & Backend

-   Python
-   FastAPI
-   REST APIs
-   PostgreSQL
-   MongoDB
-   Cassandra
-   Qdrant
-   Pinecone
-   Docker / Docker Compose
-   Git / GitHub
-   Linux
-   ETL pipelines
-   Data modeling
-   Logging, health checks, exception handling, and configuration
    management

### Cloud & Data Systems

-   AWS S3
-   Apache Kafka
-   MongoDB
-   Cassandra
-   PostgreSQL
-   Docker

------------------------------------------------------------------------

## Featured Projects

### 1. Multilingual Quran Search with Hybrid Retrieval & Urdu LLM Explanations

**Python · FastAPI · Qdrant · PostgreSQL · Hugging Face · Docker**

Built a multilingual Quran search application combining **dense semantic
retrieval and sparse lexical retrieval**.

**Highlights:** - Returns Arabic, Urdu, and English verse text -
Generates Urdu LLM-based explanations - Separate dense and sparse Qdrant
collections - PostgreSQL used for canonical verse text and metadata -
FastAPI REST services with a modular service layer - Docker Compose for
local deployment - Health and integration checks - Centralized logging
and exception handling - Dense-search fallback for component failures

🔗 **Repository:**
[quran_hadith_multilingual_rag](https://github.com/mubashar-ds/quran_hadith_multilingual_rag)

------------------------------------------------------------------------

### 2. Robust Deepfake Detection under Compression & Domain Shift

**Python · PyTorch · Xception65 · ViT-B/16 · OpenCV · DCT**

Studied the robustness of deepfake detection models under **JPEG
compression and cross-dataset domain shift**.

**Highlights:** - Benchmarked Xception65 and ViT-B/16 - Evaluated on
FaceForensics++ and Celeb-DF v2 - Tested clean data and five JPEG
compression levels - Developed a DCT-aware Xception65 with a
frequency-domain branch - Developed a Compression-Aware Training
approach - Achieved **0.9657 ROC-AUC** on clean FaceForensics++ -
Improved Celeb-DF v2 AUC from **0.7872 to 0.8039** - Improved
FaceForensics++ Q10 ROC-AUC from **0.632 to 0.791** with the combined
DCT + compression-aware approach

🔗 **Repository:**
[robust-deepfake-detection](https://github.com/mubashar-ds/robust-deepfake-detection)

------------------------------------------------------------------------

### 3. DataLink: Scalable Big Data Platform

**Python · Apache Kafka · MongoDB · Cassandra · FastAPI · AWS S3 ·
Streamlit**

Built a simulated professional networking platform around **1M+
synthetic user profiles**.

**Highlights:** - 1M+ synthetic profiles - Nested education, skills, and
experience data - Real-time interaction ingestion through Apache Kafka -
Kafka producer / consumer workflows - FastAPI REST services - MongoDB
and Cassandra - AWS S3 for profile images, resumes, and other media -
Streamlit interface

🔗 **Repositories:**
[data-link-app](https://github.com/mubashar-ds/data-link-app)

------------------------------------------------------------------------

### 4. Hybrid BM25--TF-IDF Information Retrieval System

**Python · BM25 · TF-IDF · spaCy · scikit-learn**

Implemented an offline information retrieval pipeline combining
classical lexical ranking approaches.

**Highlights:** - Text cleaning and preprocessing - spaCy tokenization
and lemmatization - Duplicate removal - BM25 and TF-IDF indexes -
Boolean and phrase queries - Metadata filtering - Weighted hybrid
ranking - Evaluation across 50 queries - Precision@10: **0.940** -
Recall@10: **0.940** - MRR: **0.892** - nDCG@10: **0.904**

🔗 **Repositories:**
[hybrid_bm25_tfidf_retrieval_system](https://github.com/mubashar-ds/hybrid_bm25_tfidf_retrieval_system)

------------------------------------------------------------------------

## Selected Additional Work

### StyleSense --- Generative AI Fashion Design

A generative AI fashion design platform combining image scraping, BLIP
captioning, Stable Diffusion v1.5 image-to-image generation, Llama-based
prompting through Groq, image blending, and a Gradio interface.

### SimCLR --- Self-Supervised Representation Learning

Implemented SimCLR-style self-supervised pretraining on CIFAR-10 and
evaluated learned representations through linear probing and
fine-tuning.

### Image Retrieval with Deep Embeddings

Explored image retrieval using a pretrained ResNet-50 backbone,
embedding-based similarity, contrastive/triplet objectives,
hard-negative mining, and Recall@K evaluation.

### DDPM --- Diffusion Model

Implemented a diffusion-based image generation pipeline using a U-Net
architecture and a multi-step forward/reverse diffusion process.

------------------------------------------------------------------------

## Technical Stack

### Languages & Core

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

### AI / ML

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Hugging
Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

### LLM / RAG / Agentic AI

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square)
![LangGraph](https://img.shields.io/badge/LangGraph-111827?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-Retrieval%20Augmented%20Generation-0F766E?style=flat-square)

### Backend / Databases

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

### Retrieval / Data

![Qdrant](https://img.shields.io/badge/Qdrant-FF4F64?style=flat-square)
![Apache
Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)

------------------------------------------------------------------------

## Current Focus

I am currently deepening my work in:

-   Agentic AI system design
-   LangGraph orchestration
-   Tool and function calling
-   Structured outputs
-   Stateful workflows
-   RAG evaluation
-   Retrieval reliability
-   Guardrails and failure handling
-   Production-oriented AI APIs
-   AWS deployment and cloud architecture

The goal is not simply to build demos, but to understand how
**retrieval, models, tools, state, APIs, data, evaluation, and
deployment** fit together into dependable AI systems.

------------------------------------------------------------------------

## Professional Experience

**Software Engineering Intern – AI/ML**  
*Dev&Mark — Lahore, Pakistan* | *Feb 2026 – Apr 2026*

- Contributed across the software development lifecycle (SDLC), including implementation, debugging, testing, and iterative feature development.
- Contributed to Python-based application and data/AI development tasks in a collaborative software engineering environment.
- Applied Git-based version control, modular code organization, API integration, testing, and debugging practices.
- Maintained technical documentation and followed structured development practices to support code quality and maintainability.

------------------------------------------------------------------------

## Education 

<table> 
  <tr> 
    <td><strong>M.S. Data Science</strong> — Machine Learning & Artificial Intelligence</td> 
    <td align="right">Aug 2024 – Jul 2026</td> 
  </tr> 
  <tr> 
    <td colspan="2">Information Technology University (ITU), Lahore</td> 
  </tr> 
</table> 

Relevant areas: Machine Learning, Deep Learning, NLP, Information Retrieval & Text Mining, Big Data Analytics, System Security Engineering 

<table> 
  <tr> 
    <td><strong>B.S. Physics</strong> — Computational Physics & Scientific Computing</td> 
    <td align="right">Feb 2018 – Jan 2022</td> 
  </tr> 
  <tr> 
    <td colspan="2">COMSATS University Islamabad, Lahore Campus</td> 
  </tr> 
</table> 

Computational focus: Programming (C, MATLAB), Computational Physics, Scientific Computing, and numerical/statistical methods.

------------------------------------------------------------------------

## Research

### M.S. Thesis — Deepfake Speech Detection

**Towards Lightweight and Explainable Deepfake Speech Detection Systems**

My thesis research focuses on lightweight and explainable deepfake speech detection using audio representations and deep learning.

I have **submitted a first-author research paper to IEEE Signal Processing Letters (IEEE SPL)** based on this thesis work and am continuing additional experiments and analysis toward the final thesis version.

------------------------------------------------------------------------

## What I'm Looking For

Open to **AI Engineer**, **ML Engineer**, **Data Engineer**, and **LLM/GenAI roles**, with a focus on **RAG, Agentic AI, Information Retrieval, Computer Vision, Data Pipelines, and AI systems engineering**.

Interested in teams building reliable AI products across model development, retrieval, evaluation, backend engineering, and deployment.

------------------------------------------------------------------------

## Let's Connect

**Email:** <mubashar.itu@gmail.com>\
**LinkedIn:**
[linkedin.com/in/mubashar-ds](https://www.linkedin.com/in/mubashar-ds)\
**GitHub:** [github.com/mubashar-ds](https://github.com/mubashar-ds)\
**Lahore, Pakistan**

------------------------------------------------------------------------

> **Build useful AI. Measure it. Make it reliable.**

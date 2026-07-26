<div align="center">

# Hi, I'm Syed Muhammad Awais Raza 👋

### AI/ML Engineer · Computer Vision · NLP · RAG · MLOps

I build production-oriented AI systems, machine learning pipelines, computer vision applications, full-stack AI products, and experimental research prototypes.

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit%20Website-00F5D4?style=for-the-badge&logo=vercel&logoColor=black)](https://syed-awais-raza.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/syed-muhammad-awais-raza-905317278/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/awai1s)
[![Email](https://img.shields.io/badge/Email-Contact%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:awaisraza5424@gmail.com)

</div>

---

## About Me

I am a **B.S. Artificial Intelligence student at COMSATS University Islamabad, Attock Campus**, with practical experience in machine learning, deep learning, computer vision, NLP, RAG systems, FastAPI deployment, Docker, and full-stack AI development.

During my internship at **O2Geeks AI Program**, I worked on production-oriented CV and NLP systems involving OCR, augmented reality, semantic search, pgvector-based RAG, FastAPI, Streamlit, and Docker.

I have also built AI-powered applications, computer vision systems, data pipelines, multimodal research frameworks, and experimental model architectures.

- 🎓 B.S. Artificial Intelligence — expected graduation June 2027
- 📊 Current CGPA: **3.4/4.0**
- 🔬 Working on computer vision, multimodal AI, LLM optimization, and explainable AI research
- 👥 Founder of the **Hexagon AI/ML Society**, a community of 250+ learners
- 🧑‍🏫 Teaching Python, ML, deep learning, APIs, deployment, and MLOps
- 📍 Attock, Punjab, Pakistan

---

## Current Focus

- Explainable multimodal AI for brain stimulation-response analysis
- Transfer learning for small 3D neuroimaging datasets
- Weighted feature fusion for YOLO architectures
- KV-cache quantization and LLM inference optimization
- Production AI systems using FastAPI, Docker, PostgreSQL, and React/Next.js
- Retrieval-Augmented Generation and vector search systems

---

## Experience

### AI/ML Intern — O2Geeks AI Program

**ML Engineering Lead · July 25, 2025 – August 29, 2025**

- Completed an intensive AI internship focused on computer vision, NLP, OCR, augmented reality, semantic search, and RAG.
- Developed production-oriented ML pipelines using **FastAPI, Streamlit, Docker, and pgvector**.
- Worked under the guidance of the CEO and AI Research Lead.
- Built and deployed **three production ML services** using FastAPI and Docker.
- Contributed to system design, experimentation, backend integration, and deployment workflows.

---

## Featured Projects

### Campus Exchange — AI-Powered Campus Marketplace

A full-stack campus marketplace designed to reduce student scams and improve product discovery among verified users.

**Highlights**

- Built with Next.js, FastAPI, PostgreSQL, pgvector, and Redis.
- Developed personalized product recommendations using vector similarity.
- Added AI-assisted pricing functionality.
- Achieved approximately **15% improvement in pricing accuracy**.
- Designed features for verified users, expense sharing, and safer campus transactions.

**Technologies:** Next.js · FastAPI · PostgreSQL · pgvector · Redis · Python

---

### Cricket Ball and Bat Detection with Speed Measurement

A real-time computer vision system for detecting and tracking cricket balls and bats.

**Highlights**

- Trained YOLOv8 models for ball and bat detection.
- Used Ultralytics tracking for object association.
- Detected potential hit events using bounding-box overlap and motion conditions.
- Implemented trajectory-based speed estimation.
- Explored Tomasi–Kanade-based reconstruction for 3D motion analysis.

**Technologies:** YOLOv8 · OpenCV · Python · Object Tracking · Computer Vision

---

### Voice-ID and Neural Voice Cloning System

An integrated speaker identification and voice-cloning pipeline.

**Highlights**

- Used SpeechBrain ECAPA embeddings for speaker identification.
- Calibrated a cosine-similarity authentication threshold of **0.4814**.
- Supported enrolled-speaker verification against unknown audio samples.
- Integrated Coqui TTS for neural voice cloning.
- Developed an audio preprocessing pipeline supporting OGG, MP3, and WAV.
- Standardized audio to 16 kHz before inference.

**Technologies:** SpeechBrain · ECAPA · Coqui TTS · PyTorch · Audio Processing

---

### HexaQuote — AI Voice-to-Quote Application

A React Native and FastAPI application that converts spoken job descriptions into professional quotations.

**Workflow**

1. User records a job description.
2. Groq Whisper transcribes the recording.
3. Llama converts the transcript into structured quote data.
4. FastAPI validates and processes the result.
5. Supabase stores the quotation.
6. The application generates a professional PDF.

**Technologies:** React Native · Expo · FastAPI · Groq Whisper · Llama · Supabase · Uvicorn

---

### Bank Churn and Heart Disease Prediction

Machine learning classification projects using traditional ML and neural networks.

**Highlights**

- Developed reusable preprocessing and training pipelines.
- Compared boosting algorithms and classical classifiers.
- Implemented MLP and feed-forward neural network models.
- Evaluated models using classification metrics and confusion matrices.

**Technologies:** scikit-learn · TensorFlow · Pandas · NumPy · Matplotlib

---

### Cobot Visuomotor Dataset Pipeline

An automated pipeline for generating synchronized robot vision and joint-angle datasets.

**Highlights**

- Processed cobot joint-state logs.
- Detected inactive robot periods.
- Synchronized video frames with sensor timestamps.
- Extracted frames at a fixed sampling rate.
- Mapped images to six robot joint angles.
- Exported structured training data for future imitation-learning experiments.

**Technologies:** Python · OpenCV · Pandas · Robotics · Data Engineering

---

## Research Projects

### Weighted YOLO

A proposed object-detection architecture created by analyzing the evolution of multiple YOLO generations and combining selected modules into one experimental framework.

**Key components**

- Efficient convolutional stem
- CSP and C3k2 backbone blocks
- SPPF and C2PSA attention
- Large-kernel convolution
- Learnable weighted PAN-FPN fusion
- Anchor-free decoupled detection
- One-to-many training head
- One-to-one NMS-free inference head
- Training-only gradient and supervision modules

The project focuses on controlled experiments and ablation studies rather than treating the proposed architecture as an already established model.

---

### Explainable Multimodal Brain Stimulation-Response AI

An explainable multimodal research framework for predicting Low, Moderate, and High stimulation-response risk categories.

**Research workflow**

- Processed the OpenNeuro `ds002799` dataset.
- Generated stimulation-response fMRI maps.
- Processed stimulation, event, channel, and electrode metadata.
- Created pseudo-labels for three-class prediction.
- Pretrained a 3D residual autoencoder using BrainPedia statistical maps.
- Continued pretraining using HCP task-fMRI maps.
- Fine-tuned the encoder on epilepsy stimulation-response data.
- Evaluated the model using subject-wise LOSO.
- Added multimodal fusion, uncertainty estimation, explainability, VLM interpretation, and grounded LLM reporting.

**Technologies:** PyTorch · 3D CNN · fMRI · Transfer Learning · Multimodal Fusion · Grad-CAM · VLM · LLM

> This is a research decision-support framework using pseudo-labels, not a clinically validated diagnostic system.

---

### FG-KVQ — Factorized Gated KV Quantization

An experimental LLM quantization method designed to reduce the impact of Key-vector outliers before KV-cache storage.

**Core idea**

Instead of storing raw outlier-heavy Keys directly, the Key is factorized into:

- Low-bit normalized Key content
- A compact scaling gate

The method aims to preserve attention behavior while improving low-bit quantization compatibility.

**Evaluation areas**

- Key reconstruction error
- Attention-logit error
- Top-k attention overlap
- Outlier ratio
- KV-cache memory
- Perplexity
- Decode latency
- Long-context retrieval

**Technologies:** PyTorch · Hugging Face Transformers · LLM Quantization · KV Cache · RoPE

---

### Diffusion and Classical Texture Statistics Analysis

A research implementation comparing classical image-texture statistics with learned diffusion-model representations.

**Highlights**

- Implemented Heeger–Bergen-inspired texture statistics.
- Used steerable pyramids, wavelets, and multi-scale filter responses.
- Extracted intermediate U-Net features using model hooks.
- Compared original and generated image statistics.
- Used Wasserstein distance and frequency-response analysis.
- Studied how diffusion denoising progressively reconstructs texture properties.

**Technologies:** PyTorch · Diffusion Models · Wavelets · Steerable Pyramids · Image Processing

---

## Technical Skills

### Programming Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)

### Machine Learning and Deep Learning

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![DVC](https://img.shields.io/badge/DVC-945DD6?style=flat-square&logo=dvc&logoColor=white)

### Data and Visualization

![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)

### Backend and Databases

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)

### Web and Mobile Development

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React Native](https://img.shields.io/badge/React%20Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)

### MLOps, Deployment and Tools

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)

---

## Education

### COMSATS University Islamabad — Attock Campus

**B.S. Artificial Intelligence**

- Expected graduation: **June 2027**
- Current CGPA: **3.4/4.0**
- Relevant coursework:
  - Programming Fundamentals
  - Object-Oriented Programming
  - Data Structures and Algorithms
  - Linear Algebra
  - Calculus
  - Probability and Statistics
  - Machine Learning
  - Artificial Intelligence
  - Artificial Neural Networks and Deep Learning
  - Computer Vision
  - Natural Language Processing
  - Databases
  - Operating Systems
  - Software Engineering

---

## Leadership and Community

### Founder — Hexagon AI/ML Society

**July 2024 – Present**

- Built and managed an AI/ML learning community of more than **250 members**.
- Teach practical roadmaps covering Python, data analysis, machine learning, deep learning, APIs, deployment, and MLOps.
- Create educational blog posts combining Markdown explanations and executable code.
- Conduct live learning sessions and project guidance.
- Mentor learners and international clients on AI pipelines and FastAPI deployment.

### Microsoft Learn Student Ambassadors

**Technical Team Member · 2024–2025**

- Supported AI/ML workshops and technical activities.
- Contributed to campus-level Microsoft Learn events.
- Received a Certificate of Appreciation for contributions to the technical team.

---

## Certifications

- Certified Python Elementary Programmer — CPEP-11
- Anaconda Python for Data Science Professional Certificate
- Career Essentials in Generative AI — Microsoft and LinkedIn
- Career Essentials in Data Analysis — Microsoft and LinkedIn
- Career Essentials in GitHub Professional Certificate
- Develop with Python for AI and Machine Learning
- Python Data Analysis
- NumPy, SciPy, Matplotlib and Pandas A-Z
- Machine Learning and Self-Driving Cars
- Applications of AI
- Introduction to Artificial Intelligence
- SQL for Data Science
- Coding Arena Top Performer

View certificates and supporting evidence on my:

[![Portfolio](https://img.shields.io/badge/View%20Certificates-Portfolio-8B5CF6?style=for-the-badge&logo=vercel&logoColor=white)](https://syed-awais-raza.vercel.app/#credentials)

---

## GitHub Statistics

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=awai1s&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />

<img width="49%" src="https://streak-stats.demolab.com?user=awai1s&theme=tokyonight&hide_border=true" />

<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=awai1s&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />

</div>

---

## Let's Connect

I am open to:

- AI/ML engineering opportunities
- Computer vision and NLP projects
- Research collaborations
- Full-stack AI application development
- FastAPI and Docker deployment work
- Technical mentoring and educational collaborations

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-syed--awais--raza.vercel.app-00F5D4?style=for-the-badge&logo=vercel&logoColor=black)](https://syed-awais-raza.vercel.app/)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Syed%20Muhammad%20Awais%20Raza-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/syed-muhammad-awais-raza-905317278/)

[![Email](https://img.shields.io/badge/Email-awaisraza5424%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:awaisraza5424@gmail.com)

![Profile Views](https://komarev.com/ghpvc/?username=awai1s&color=00f5d4&style=for-the-badge&label=PROFILE+VIEWS)

</div>

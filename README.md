<h1 align="center">Hi, I'm Saydain 👋</h1>
<p align="center"><b>AI/ML Engineer</b> · M.S. Data Science @ Stevens ('25)</p>
<p align="center">
  <a href="mailto:sheikhsaydain@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/sheikhsk/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <img alt="Profile views" src="https://komarev.com/ghpvc/?username=saydainsk&style=for-the-badge"/>
</p>

---

### 🚀 What I do

* Build practical **GenAI + ML systems** end‑to‑end: agentic workflows, RAG, and model serving with a focus on **latency, evals, and reliability**.
* Ship using **Pinecone, PostgreSQL, Kubernetes, FastAPI/Streamlit**, and HF/OpenAI stacks.
* Interests: **personalization**, **computer‑use agents**, **applied CV/NLP**.

> If you'd like a quick demo of any project, ping me (email badge above) — happy to share!

---

### 📈 Live dashboards & analytics

<div align="center">

<a href="https://github.com/anuraghazra/github-readme-stats"><img alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=saydainsk&show_icons=true&rank_icon=github" height="150"></a> <a href="https://github.com/anuraghazra/github-readme-stats"><img alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=saydainsk&layout=compact&langs_count=8" height="150"></a> <br/> <a href="https://github.com/DenverCoder1/github-readme-streak-stats"><img alt="GitHub Streak" src="https://streak-stats.demolab.com?user=saydainsk" height="150"></a> <a href="https://github.com/ryo-ma/github-profile-trophy"><img alt="Trophies" src="https://github-profile-trophy.vercel.app/?username=saydainsk" height="150"></a> <br/> <a href="https://github.com/Ashutosh00710/github-readme-activity-graph"><img alt="Activity Graph" src="https://github-readme-activity-graph.vercel.app/graph?username=saydainsk" height="250"></a>

</div>

---

### 🏆 Featured Projects

| Project | Description |
|---|---|
| [ECG Heartbeat Classification](https://github.com/saydainsk/ECG-Heart-Beat-Classification) | Arrhythmia detection · XGBoost & NN · 99% precision / 97% recall |
| [Credit Card Fraud Detection](https://github.com/saydainsk/Credit-Card-Fraud-Predictive-System) | Imbalanced learning pipeline · cost-sensitive models · PR-AUC monitoring |
| [Twitter Sentiment Analysis](https://github.com/saydainsk/Twitter-Data-Sentimental-Analysis) | Custom tokenizer · +20% data quality · 85% accuracy |
| [Telecom Churn Prediction](https://github.com/saydainsk/Telecom-Churn-Prediction-with-PCA-and-Logistic-Regression) | PCA + logistic regression · stable AUC + clean diagnostics |
| [Agent‑S GUI Automation](https://github.com/saydainsk/Agent-S) | Multi-agent Android QA · Planner → Executor → Verifier loop |
| [USC Healthcare Hackathon](https://github.com/saydainsk/USC-Healthcare-Hackathon) | Reproducible health analytics · notebooks + datasets |

---

### 📚 Case studies (fast reads)

<details>
<summary><b>ECG Heartbeat Classification</b> — Arrhythmia detection with classic ML + NN</summary>

* **Problem:** Detect abnormal heartbeats from ECG segments (imbalanced classes).
* **Approach:** Feature engineering (RR intervals, morphology) → baseline models (LR, RF) → tuned XGBoost + simple NN → threshold tuning and cost‑sensitive evals.
* **Highlights:** 98% F1 on minority class; calibration for clinical interpretability; clean EDA and error analysis.
* **Stack:** Python, scikit‑learn, XGBoost, NumPy, Pandas, Matplotlib.

```mermaid
flowchart LR
  A[Raw ECG] --> B[Preprocess & Segment]
  B --> C[Feature Eng]
  C --> D{Model Family}
  D -->|XGBoost| E[Train]
  D -->|NN| E
  E --> F[Eval: F1/ROC/PR]
  F --> G[Threshold/Calibrate]
```

</details>

<details>
<summary><b>Credit Card Fraud Predictive System</b> — End‑to‑end imbalanced learning</summary>

* **Problem:** Real‑time fraud detection under severe class imbalance.
* **Approach:** Robust preprocessing → stratified CV → cost‑sensitive models (XGB/LightGBM) → threshold search for business cost.
* **Highlights:** Lift at top‑k, PR‑AUC gains vs baseline, clear notebook + slides.
* **Stack:** Python, scikit‑learn, XGBoost, imbalanced‑learn.

```mermaid
flowchart LR
  A[Transactions Stream] --> B[Feature Store]
  B --> C[Model Serve]
  C --> D[Decision: Flag/Hold]
  D --> E[Analyst Review]
```

</details>

<details>
<summary><b>Agent‑S Experiments</b> — Multi‑agent GUI automation for mobile QA</summary>

* **Problem:** Automate Android UI tasks (Wi‑Fi toggles, calendar events) with tool‑using agents.
* **Approach:** Planner → Executor → Verifier loop; structured logs; replayable tests; visual renderer.
* **Highlights:** Self‑check + recovery, modular tasks (`settings_wifi`, `calendar_create`).
* **Stack:** Python, asyncio, PIL, custom in‑memory AndroidEnv.

```mermaid
sequenceDiagram
  participant Planner
  participant Executor
  participant Env as AndroidEnv
  participant Verifier
  Planner->>Executor: Plan actions
  Executor->>Env: Tap/Type/Swipe
  Env-->>Executor: New UI state
  Executor->>Verifier: Trace + screenshot
  Verifier-->>Planner: Pass/Retry hint
```

</details>

---

### 🧰 Tech I use

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white"> 
  <img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white">
  <img alt="TensorFlow" src="https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white">
  <img alt="scikit-learn" src="https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white">
  <img alt="Transformers" src="https://img.shields.io/badge/HuggingFace-FFD21E?logo=huggingface&logoColor=black">
  <img alt="LangChain" src="https://img.shields.io/badge/LangChain-1C3C3C?logo=chainlink&logoColor=white">
  <img alt="Pinecone" src="https://img.shields.io/badge/Pinecone-0F9D58?logo=pinecone&logoColor=white">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white">
  <img alt="Kafka" src="https://img.shields.io/badge/Apache%20Kafka-231F20?logo=apachekafka&logoColor=white">
  <img alt="Redis" src="https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white">
  <img alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white">
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white">
  <img alt="Streamlit" src="https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white">
  <img alt="Airflow" src="https://img.shields.io/badge/Apache%20Airflow-017CEE?logo=apacheairflow&logoColor=white">
  <img alt="Pandas" src="https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white">
  <img alt="NumPy" src="https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white">
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white">
  <img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black">
</p>

---

### 🧪 How I build (signals of rigor)

* **Evals-first:** simple golden sets + regression tests for RAG/agents.
* **Latency budgets:** measure p95/p99 end‑to‑end; profile token/IO hotspots.
* **Ops:** containerized services, health probes, structured logs, small PRs.

---

### 📬 Get in touch

* Email: **[sheikhsaydain@gmail.com](mailto:sheikhsaydain@gmail.com)**
* LinkedIn: **[linkedin.com/in/sheikhsk](https://www.linkedin.com/in/sheikhsk/)**
* Open to: **AI/ML Engineer, Data Scientist** roles · Open to roles across the US (hybrid or remote)

---

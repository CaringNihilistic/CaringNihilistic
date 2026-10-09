<div align="center">

[![](https://img.shields.io/badge/🎓_HBTU_Kanpur_'27-0D1117?style=for-the-badge)](https://hbtu.ac.in)
[![](https://img.shields.io/badge/📍_India_·_Remote-0D1117?style=for-the-badge)](#)
[![](https://img.shields.io/badge/⚡_Agentic_AI_Engineer-00D9FF?style=for-the-badge&logoColor=black)](#)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=00D9FF)](https://www.linkedin.com/in/ayush-yadav-7ba731289)
[![Email](https://img.shields.io/badge/Email-0D1117?style=for-the-badge&logo=gmail&logoColor=00D9FF)](mailto:ayush710yadav@gmail.com)
[![dev.to](https://img.shields.io/badge/dev.to-0D1117?style=for-the-badge&logo=devdotto&logoColor=00D9FF)](https://dev.to/ayush_notsogreat_b673d5)

*I build AI agents that check their own work, and the tooling that shows when they don't.*

</div>

---

### ⚡ About Me

| | |
|:---:|:---|
| 🎓 | **Final year @ HBTU Kanpur** — B.Tech, Class of 2027 |
| 💼 | **Freelance ML Engineer** — live international client (AgTech, Colombia/Venezuela) |
| 🔧 | **Building** — agentic systems with LangGraph · RAG + evaluation · LLM observability |
| 🧩 | **Contributing to** — OpenLLMetry · RAGAS · LiteLLM · OpenLIT |
| 🎯 | **Rule** — an agent is done when the tests pass, not when it says it's done |

---

### 🌎 Experience

**AgroIA Ganadera** — Freelance ML Engineer *(AgTech · Colombia / Venezuela)*
- YOLOv8s aerial livestock detection on a 2,714-image dataset — **mAP@50 = 0.731**
- Deployed on HuggingFace Spaces + FastAPI REST API · ~1s per frame on CPU for 2K imagery

---

### 🚀 Flagship Projects

| | Project | What it does | Numbers |
|:---:|:---|:---|:---|
| 🧠 | **[Socra — AI Startup Interrogator](https://socra-production.up.railway.app)** | 5-agent LangGraph pipeline · Startup Tribunal mode · Postgres checkpointing · Clerk auth · falls back across 3 LLM providers | `$0.007/session` · `52s/run` |
| 🤖 | **Autonomous Coding Agent** | LangGraph plan → act → observe → retry loop that fixes bugs in a sandboxed copy of a repo · success is decided by pytest's exit code, never by the model's own claim | `fixes 2-bug repo in 2 tries` · `gives up honestly on a tight budget` |
| 📚 | **[RAG Teaching Assistant](https://huggingface.co/spaces/ayushthecaringnihilist/rag-ai-teaching)** | 241 lectures + 1,230 textbook pages · hybrid retrieval + HyDE + cross-encoder reranking · multi-turn memory | `Faithfulness 0.773` · `~200ms` |

### 🧪 More Work

| | Project | What it does | Numbers |
|:---:|:---|:---|:---|
| 🎾 | **Tennis Match Prediction** *(research)* | XGBoost + LightGBM ensemble with surface-specific Elo over 27,510 ATP matches · LLM-extracted news signals add +5.2pp | `72.4% acc.` vs `68.4%` closing odds |
| 🔩 | **[Bearing Fault Monitor](https://github.com/CaringNihilistic/bearing-fault-monitor)** | Random Forest on physics-based vibration features (CWRU dataset) · confidence + drift monitoring · 34 tests | `98.0% acc.` · `0.981 macro F1` |
| 🏭 | **[Steel Surface Defect Detection](https://github.com/CaringNihilistic/surface-defect-detection)** | YOLOv8n on NEU-DET (6 defect classes) · EigenCAM explainability | `mAP@50 0.708` |
| 🔬 | **[Skin Lesion Classifier](https://huggingface.co/spaces/ayushthecaringnihilist/skin-lesion-classifier)** | EfficientNetB2 · Grad-CAM · 10k+ dermoscopy images · 7 classes | `85.1% val acc.` |
| 💳 | **[Credit Risk Predictor](https://huggingface.co/spaces/ayushthecaringnihilist/credit-risk-prediction)** | 307k applicants · 57M+ rows · 157 engineered features · Optuna (100 trials) · MLflow | `ROC-AUC 0.782` |

---

### 🔧 Open Source *(all under review)*

| Repo | PR | What it does |
|:---|:---|:---|
| **traceloop/openllmetry** | [#4226](https://github.com/traceloop/openllmetry/pull/4226) | New DeepSeek instrumentation · captures R1 chain-of-thought as span attributes, including when streaming · 121 tests passing |
| **vibrantlabsai/ragas** | [#2776](https://github.com/vibrantlabsai/ragas/pull/2776) | Fixes `llm_factory` crash on native Mistral clients · handles sync + async paths · confirmed working by the issue reporter |
| **BerriAI/litellm** | [#32446](https://github.com/BerriAI/litellm/pull/32446) | Fixes a regression where `/responses` dropped reasoning items in multi-turn calls, breaking Azure · 17 new tests · 100% coverage on changed lines |
| **openlit/openlit** | [#1698](https://github.com/openlit/openlit/pull/1698) | Fixes OpenAI instrumentation crashing on `usage: null` (responses, chat, embeddings, streaming) · 8 regression tests |

---

### ✍️ Writing

- [How I built a 3-provider LLM fallback system in production (and what actually broke)](https://dev.to/ayush_notsogreat_b673d5/how-i-built-a-3-provider-llm-fallback-system-in-production-and-what-actually-broke-46jk)

---

### 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-0D1117?style=for-the-badge&logo=python&logoColor=00D9FF)
![LangGraph](https://img.shields.io/badge/LangGraph-0D1117?style=for-the-badge&logo=langchain&logoColor=00D9FF)
![LangChain](https://img.shields.io/badge/LangChain-0D1117?style=for-the-badge&logo=langchain&logoColor=00D9FF)
![PyTorch](https://img.shields.io/badge/PyTorch-0D1117?style=for-the-badge&logo=pytorch&logoColor=00D9FF)
![HuggingFace](https://img.shields.io/badge/HuggingFace-0D1117?style=for-the-badge&logo=huggingface&logoColor=00D9FF)
![FastAPI](https://img.shields.io/badge/FastAPI-0D1117?style=for-the-badge&logo=fastapi&logoColor=00D9FF)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0D1117?style=for-the-badge&logo=postgresql&logoColor=00D9FF)
![Docker](https://img.shields.io/badge/Docker-0D1117?style=for-the-badge&logo=docker&logoColor=00D9FF)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-0D1117?style=for-the-badge&logo=opentelemetry&logoColor=00D9FF)
![MLflow](https://img.shields.io/badge/MLflow-0D1117?style=for-the-badge&logo=mlflow&logoColor=00D9FF)
![XGBoost](https://img.shields.io/badge/XGBoost-0D1117?style=for-the-badge&logo=xgboost&logoColor=00D9FF)
![React](https://img.shields.io/badge/React-0D1117?style=for-the-badge&logo=react&logoColor=00D9FF)
![Git](https://img.shields.io/badge/Git-0D1117?style=for-the-badge&logo=git&logoColor=00D9FF)
![Linux](https://img.shields.io/badge/Linux-0D1117?style=for-the-badge&logo=linux&logoColor=00D9FF)

</div>

---

### 📊 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=CaringNihilistic&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D9FF&icon_color=00D9FF&text_color=C9D1D9&rank_icon=github" />
&nbsp;&nbsp;
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=CaringNihilistic&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D9FF&text_color=C9D1D9&langs_count=6" />

<br/><br/>

**Open to remote ML / AI engineering roles — internship or full-time (graduating 2027).**
[Get in touch →](mailto:ayush710yadav@gmail.com)

</div>

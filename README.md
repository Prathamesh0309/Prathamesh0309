# Hi, I'm Prathamesh Deshpande 👋

**Python Engineer · Applied ML · Agentic AI · MS Information Science (Machine Learning)**

I build end-to-end ML systems, agentic AI pipelines, and automation tools — from feature engineering and model training to multi-agent orchestration.  
3+ years of industry experience at TCS, currently deepening ML and AI foundations through research and hands-on projects.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/prathamesh-deshpande-7b8b691a6/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/Prathamesh0309)
[![Profile Views](https://komarev.com/ghpvc/?username=Prathamesh0309&style=flat&color=blue)](https://github.com/Prathamesh0309)

---

## 🔬 What I'm Working On

- **Personal Research Assistant Agent** — A multi-agent system that autonomously searches the web, reads articles, critiques its own findings, and produces structured reports with citations. Built on ReAct loops, tool use, and vector memory.
- **Suspicious URL Detection** — Classifying malicious URLs using lexical and statistical features. No external APIs, pure feature engineering with `scikit-learn`.
- **Surgical Suture Skill Analysis** *(Contributor)* — Data-driven evaluation of surgical technique using pose estimation and video understanding. Turning expert intuition into measurable signals using `YOLO · ByteTrack · MediaPipe · VideoMAE`.
- Strengthening ML fundamentals through hands-on projects and writing cleaner, well-documented Python.

---

## 🚀 Featured Projects

### 🗂️ Personal Research Assistant Agent
> An agent that takes a research topic, autonomously searches the web, reads articles, deduces sub-questions, and produces a structured report — with citations.

A fully agentic pipeline built on the **ReAct loop** pattern, with five specialized agents collaborating to go from raw query to polished report:

| Agent | Role |
|---|---|
| 🧠 **Planner** | Decomposes the query into 4–6 focused sub-questions using chain-of-thought prompting |
| 🔍 **Search Agent** | Calls Tavily API per sub-question, ranks URLs by relevance, selects links worth reading in full |
| 📄 **Reader Agent** | Fetches full page content, chunks and summarizes it, stores results in a vector store (FAISS/Chroma) to avoid re-reading |
| 🔁 **Critic Agent** | Reviews all gathered summaries, asks *"Is this enough?"* — if not, generates follow-up queries and loops back. This is the core ReAct cycle. |
| ✍️ **Writer Agent** | Pulls from vector store, synthesizes a structured report with sections, bullet points, and inline citations |

**Key concepts:** Multi-step planning · Tool use · Stateful memory · ReAct loop · Output formatting

`Python` `LangChain` `Tavily API` `FAISS` `Chroma` `OpenAI API` `ReAct` `Multi-Agent`

---

### 🔗 Suspicious URL Detection
> Detecting malicious URLs purely through lexical and statistical feature engineering — no external threat feeds or blacklists.

- Extracted URL-based features (length, entropy, special character ratios, subdomain depth, etc.)
- Trained and evaluated multiple classifiers using `scikit-learn`
- Focus on interpretability and low-latency inference

`Python` `scikit-learn` `pandas` `NumPy` `Feature Engineering`

---

### 🩺 Surgical Suture Skill Analysis *(Contributor)*
> Analyzing surgical suture skills using computer vision and video understanding to evaluate technique and performance objectively.

- Integrated object detection and multi-object tracking for instrument localization
- Applied pose estimation to capture fine-grained hand and tool movements
- Used video transformers (VideoMAE) for temporal action understanding

`Python` `YOLO` `ByteTrack` `MediaPipe` `VideoMAE` `OpenCV`

---

### ⚙️ Workflow Automation Suite — TCS
> Python-based automation scripts that reduced manual operational effort by ~X hours/week across [N] processes.

- Built robust Selenium-based workflows to automate repetitive system tasks
- Designed for reliability, easy handoff, and minimal maintenance overhead

`Python` `Selenium` `System Automation`

---

## 🛠️ Skills

| Category | Tools |
|---|---|
| **Languages** | Python, SQL |
| **Agentic AI** | LangChain, ReAct, Multi-Agent Orchestration, Tool Use |
| **ML & Data** | scikit-learn, TensorFlow (basic), pandas, NumPy |
| **Computer Vision** | OpenCV, YOLO, MediaPipe, ByteTrack |
| **Vector Stores** | FAISS, Chroma |
| **Automation** | Selenium |
| **Dev Tools** | Git, Linux |

---

## 📊 GitHub Stats

![Prathamesh's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Prathamesh0309&show_icons=true&hide_border=true&count_private=true&theme=default)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Prathamesh0309&layout=compact&hide_border=true&theme=default)

---

## 📌 Quick Facts

- 🎓 MS in Information Science (Machine Learning focus)
- 💼 3+ years at TCS building automation systems
- 🤖 Building agentic AI systems with multi-step reasoning and tool use
- 🔭 Currently contributing to applied ML research
- 🌱 Interests: Agentic AI, feature engineering, applied ML, end-to-end system design
- 📫 Reach me on [LinkedIn](https://www.linkedin.com/in/prathamesh-deshpande-7b8b691a6/)

---

*"Build things that work. Document things that last."*

# Hi, I'm Prathamesh Deshpande 👋

**Python & ML Engineer · Agentic AI · M.S. Information Science (Machine Learning), University of Arizona**

I build agentic AI systems and applied ML pipelines: RAG assistants, tool-using agents, and classifiers with evaluation built in. Before grad school I spent 3+ years at TCS building Python automation and backend systems on production client deployments.

I'm looking for full-time Agentic AI / ML Engineer roles in the US.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/prathamesh-deshpande-7b8b691a6/)

---

## Featured projects

### 🛠️ [IT Support Agent](https://github.com/Prathamesh0309/it-support-agent): RAG + MCP tool orchestration
> An IT helpdesk assistant that answers from a knowledge base and takes actions (tickets, Slack alerts) through an MCP server.

- Ingests support documents into a local ChromaDB vector store and answers questions grounded in retrieved context (Gemini for embeddings and generation)
- Plan → Act → Respond orchestrator that decides when to retrieve and when to call tools
- FastMCP server exposing `create_ticket`, `check_ticket_status` and `notify_slack` (mock backends, easy to swap for real APIs)
- Two-layer ticket filtering: deterministic rules first, LLM-as-judge for ambiguous cases
- Evaluation script that scores answers against ground-truth test cases

`Python` `Gemini` `ChromaDB` `FastMCP` `RAG`

---

### 🗂️ [Research Assistant Agent](https://github.com/Prathamesh0309/research_agent): LangGraph multi-agent pipeline
> Takes a research question, searches the web, critiques its own coverage, and writes a cited report.

- Four agents (Planner, Searcher, Critic, Writer) sharing one typed Pydantic state, orchestrated with LangGraph
- ReAct-style loop: the Critic scores coverage and, if there are gaps, sends the Searcher back with a targeted gap summary (max 3 iterations)
- Debugged unstable Critic scoring (0.70 → 0.47 across iterations) by windowing results and truncating content, trading some context for stable evaluation

`Python` `LangGraph` `Gemini` `Tavily` `Pydantic`

---

### 🔗 [Suspicious URL Detection Pipeline](https://github.com/Prathamesh0309/suspicious_url_predictor): hybrid ML + heuristics
> Scores URLs for phishing and malware risk, then groups them into campaigns by shared infrastructure.

- Hybrid risk score: FastText model (40%), heuristics such as typosquatting and suspicious TLDs (40%), infrastructure signals such as SSL and page title (20%)
- Campaign clustering links domains that share SSL certificate fingerprints or page-title hashes
- Streamlit dashboard, Docker setup, and data fetched from URLhaus and PhishStats plus Tranco as benign baseline

`Python` `FastText` `scikit-learn` `Streamlit` `Docker`

---

### 🩺 Surgical Suture Skill Analysis *(Contributor)*
<!-- Add the link to the professor's repo here -->
> Evaluating surgical technique with computer vision and video understanding.

- Integrated object detection and multi-object tracking for instrument localization
- Applied pose estimation to capture fine-grained hand and tool movements
- Used a video transformer (VideoMAE) for temporal action understanding

`Python` `YOLO` `ByteTrack` `MediaPipe` `VideoMAE` `OpenCV`

---

### Also built
- **[Events Portal](https://github.com/Prathamesh0309/events-portal)**: Streamlit + MySQL app with sign-up/login, admin and user flows, event registration, and simulated payments
- **Workflow automation at TCS**: Python and Selenium automation for repetitive operational tasks on production client deployments, built for reliability and easy handoff

---

## 🛠️ Skills

| Category | Tools |
| --- | --- |
| **Languages** | Python, SQL |
| **Agentic AI** | LangGraph, LangChain, ReAct, multi-agent orchestration, tool use, MCP (FastMCP) |
| **LLMs & RAG** | Gemini API, ChromaDB, embeddings, retrieval, LLM-as-judge evaluation |
| **ML & Data** | scikit-learn, FastText, pandas, NumPy, TensorFlow (basic) |
| **Computer Vision** | OpenCV, YOLO, ByteTrack, MediaPipe, VideoMAE |
| **Engineering** | Docker, Streamlit, MySQL, Pydantic, Selenium, Git, Linux |

---

## 📫 Contact
[LinkedIn](https://www.linkedin.com/in/prathamesh-deshpande-7b8b691a6/)

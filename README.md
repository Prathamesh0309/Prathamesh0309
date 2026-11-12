# Hi, I'm Prathamesh 👋

**Agentic AI / ML Engineer · M.S. Information Science (Machine Learning), University of Arizona · Tucson, AZ**

I build LLM agents and applied ML systems, and I care about the unglamorous part: evaluation, failure handling, and knowing when the model shouldn't answer. Before grad school I spent 3+ years at TCS writing Python automation and backend systems for production client deployments, so I tend to ask "what happens when this breaks?" early.

Looking for full-time Agentic AI / ML Engineer roles in the US.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/prathamesh-deshpande-7b8b691a6/)

---

## Featured projects

### 🛠️ [IT Support Agent](https://github.com/Prathamesh0309/it-support-agent)
RAG + MCP tool use for an IT helpdesk. Answers from a knowledge base, and opens tickets or pings Slack through a FastMCP server when a question needs action.

- Plan → Act → Respond orchestrator; routing decisions use schema-constrained JSON output instead of parsing free text
- Retrieval has a relevance floor: if nothing in the knowledge base is close enough, it skips the LLM and escalates to a ticket
- Evaluated retrieval (hit rate, MRR) separately from generation (LLM-as-judge on faithfulness and relevance, using a different model than the generator); 0.95–1.0 on the judged metrics
- Includes out-of-scope test cases where the correct behaviour is to refuse

`Python` `Gemini` `ChromaDB` `MCP` `RAG`

### 🗂️ [Research Assistant Agent](https://github.com/Prathamesh0309/research_agent)
A LangGraph pipeline that plans, searches, critiques its own coverage, and writes a cited report.

- Four nodes (Planner, Searcher, Critic, Writer) sharing one typed Pydantic state, with a conditional revision loop capped at 3 iterations
- Fixed unstable Critic scoring (0.70 → 0.47 across iterations) by windowing results and truncating content; the README documents the tradeoff
- Pipeline eval compares single-pass vs looped coverage across test queries

`Python` `LangGraph` `Gemini` `Tavily` `Pydantic`

### 🔗 [Suspicious URL Detection](https://github.com/Prathamesh0309/suspicious_url_predictor)
Hybrid phishing/malware URL scoring (FastText + heuristics + infrastructure signals) with campaign clustering by shared SSL fingerprint and page-title hash.

- Trained on 500K+ URLs; 0.932 precision/recall; presented at UA iShowcase
- Streamlit dashboard and Docker setup

`Python` `FastText` `scikit-learn` `Streamlit` `Docker`

### 🩺 Surgical Suture Skill Analysis *(contributor)*
<!-- Add the link to the professor's repo here -->
Computer vision pipeline for assessing suturing technique: YOLOv8 detection (0.98 mAP50 on ~1,560 annotated images), ByteTrack tracking, MediaPipe hand pose, and VideoMAE for temporal action understanding.

`Python` `YOLOv8` `ByteTrack` `MediaPipe` `VideoMAE`

### Also
- **[Events Portal](https://github.com/Prathamesh0309/data_warehouse_project)**: Streamlit + MySQL app with auth, admin and user flows, and simulated payments
- **Research assistant, CloudHubs lab (Prof. Tomas Cerny)**: volunteer work on the AridNova project

---

## Skills

| | |
| --- | --- |
| **Languages** | Python, SQL |
| **Agentic AI** | LangGraph, LangChain, MCP (FastMCP), tool use, multi-agent orchestration, structured outputs |
| **LLMs & RAG** | Gemini API, ChromaDB, embeddings, retrieval evaluation, LLM-as-judge |
| **ML & CV** | scikit-learn, FastText, YOLOv8, MediaPipe, ByteTrack, OpenCV, pandas, NumPy |
| **Engineering** | Docker, Streamlit, MySQL, Pydantic, Selenium, Git, Linux |

---

📫 [LinkedIn](https://www.linkedin.com/in/prathamesh-deshpande-7b8b691a6/)

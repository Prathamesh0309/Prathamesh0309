# Hi, I'm Prathamesh Deshpande 👋

#### Agentic AI / ML Engineer · MS Information Science (Machine Learning), University of Arizona · 3 years of Python backend and automation at TCS

I build LLM agents that do real work, including retrieval pipelines, tool calling over MCP, and multi-step orchestration. I also build the evaluation harnesses that show whether those agents actually work.

[LinkedIn](https://www.linkedin.com/in/prathamesh-deshpande-7b8b691a6/)

## 🔬 Currently
Research, CloudHubs Lab (Prof. Tomas Cerny, University of Arizona)
CIMET: multi-agent, multi-language change impact analysis for microservice systems. I'm scoping a shared intermediate representation across Java, Node.js, C#, Go and Python.
AridNova: secure LLM provider configuration (Ollama, local models, Azure OpenAI) across Python FastAPI microservices, with encrypted token storage in the Spring Boot / MongoDB backend.
Hardening the RAG, MCP and evaluation layers of it-support-agent.
## 🚀 Featured Projects
### 🛠️ IT Support Agent

An agentic helpdesk that answers IT questions from a knowledge base and creates and tracks tickets through an MCP tool server.

Orchestration: Plan → Act → Respond loop with Gemini and schema-constrained tool routing, with two-layer ticket filtering that starts with deterministic rules
RAG: ChromaDB with section-aware chunking, Gemini embeddings using separate document/query task types, query rewriting, and a relevance threshold that makes the agent refuse instead of guessing when context is weak
MCP: stdio MCP server for ticket creation and status checks, with tickets persisted across server processes
Evaluation: retrieval hit rate and MRR, refusal checks, and LLM-as-judge scoring with a separate judge model (0.95–1.0 on faithfulness and answer relevancy)

Python LangChain Gemini ChromaDB MCP RAG LLM Evaluation

### 🔎 Research Agent

Takes a research question and returns a structured, cited report.

LangGraph pipeline: Planner → Searcher → Writer → Critic
The Planner breaks the question into sub-questions, the Searcher gathers sources with Tavily, and the Writer drafts the report
The Critic reviews the draft and sends it back through a conditional revision loop until it meets the bar
Pydantic models keep every step's output structured and validated

Python LangGraph Gemini Tavily Pydantic

### 🔗 Suspicious URL Predictor

Zero-day malicious URL detection without relying on blocklists.

Hybrid FastText classifier combined with heuristic scoring, trained on 500K+ URLs
0.932 precision and recall
Presented at the University of Arizona iShowcase

Python FastText pandas NumPy

### 🩺 Surgical Suture Skill Analysis (contributor)

Computer vision pipeline for objectively evaluating surgical suturing technique.

Instrument detection and multi-object tracking with YOLOv8 and ByteTrack, plus hand pose estimation with MediaPipe
0.98 mAP50 on ~1,560 annotated images

Python YOLOv8 ByteTrack MediaPipe OpenCV

### 💼 Experience

Tata Consultancy Services, Pune · ~3 years Python automation and backend systems for production client deployments.

### 🛠️ Skills
Area	Tools
Languages	Python, SQL
Agentic AI	LangGraph, LangChain, MCP, tool calling, RAG, LLM-as-judge evaluation
LLMs	Gemini, Azure OpenAI, Ollama
Retrieval	ChromaDB, embeddings, chunking strategies
ML & CV	scikit-learn, FastText, YOLOv8, MediaPipe, ByteTrack, OpenCV, pandas, NumPy
Backend & Tools	FastAPI, Streamlit, Selenium, Git, Linux

📫 Open to Agentic AI / ML Engineer and Forward Deployed Engineer roles in the US. Reach me on [LinkedIn](https://www.linkedin.com/in/prathamesh-deshpande-7b8b691a6/).

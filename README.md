## Hi, I'm Lovely 👋

Senior Backend Engineer based in Dubai with 12+ years building production systems in Python. These days I build RAG pipelines and multi-agent AI systems, with a focus on the production side: evaluation, observability, guardrails and clean deployment.

Previously Senior Software Engineer at **Pelago** (a Singapore Airlines venture), where I worked on the Operations Portal, Provider Platform and third-party ingestion pipelines. Before that, Crossbridge Capital, Sapient and Cognizant.

---

### 🔨 Currently building

**Customer Support Agent Platform**

A multi-agent support system where a router classifies each request and hands it to specialized agents (billing, orders, knowledge, escalation). Each agent has its own tools and permissions. Refunds pause for human approval using a checkpointed LangGraph flow that survives restarts. RAG runs over real, messy product manuals parsed with Docling and stored in Qdrant, and it's measured against a hand-built golden set.
`LangGraph` `FastAPI` `PostgreSQL` `Qdrant` `Docling` `OpenTelemetry` `Docker`

---

### 📌 Featured projects

**[Dubai Explorer AI](https://github.com/lkum11/dubai-explorer-ai)**

A RAG backend that answers questions about Dubai from indexed content. It uses hybrid Elasticsearch search with KNN vectors and a LangGraph reflection loop that checks answers before returning them. JWT auth, 21 pytest tests, GitHub Actions CI and a 7-service Docker Compose setup.
`Flask` `GraphQL` `Elasticsearch` `PostgreSQL` `LangGraph` `OpenAI` `Docker`

**[Investment Research Assistant](https://github.com/lkum11/investment-research-assistant)**

A retriever, synthesizer and critic agent flow that answers questions from earnings reports and refuses rather than guesses when the data isn't there. I evaluated it against a 14-question golden set in Langfuse: 71% correctness and 100% faithfulness, meaning it never hallucinated. A controlled chunking experiment showed the real bottleneck was PDF table extraction, not the chunker.
`LangGraph` `FastAPI` `Chroma` `Langfuse` `OpenAI`

---

### 🧰 Tech I work with

**Backend:** Python, FastAPI, Flask, GraphQL, PostgreSQL, Redis, Celery

**AI / LLM:** LangGraph, RAG, OpenAI, Qdrant, Elasticsearch, Chroma, Langfuse, MCP

**Infra:** Docker, GitHub Actions, AWS, Azure

---

### 📫 Reach me

[LinkedIn](https://www.linkedin.com/in/lovely-kumari-1855ba4b) · joinlovely@gmail.com · Open to Senior Backend and AI Engineering roles in the UAE or remote

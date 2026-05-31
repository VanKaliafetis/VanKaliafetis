## Van Kaliafetis

AI engineer building production LLM systems — agents, RAG, evals, fine-tuning.

Final-year MEng Electrical & Electronic Engineering at the University of Bath. Currently shipping Python/ML tooling part-time at **Framatome UK**, applying ML and automation to nuclear engineering workflows.

**Open to remote AI/ML engineering contract work with US companies.**
Bath, UK (GMT/BST) — comfortable with US-overlap hours.

### What I'm working on

- **LLM agents with real tool use** — hand-written agent loops, no framework lock-in, multi-provider (Groq, Gemini, Ollama)
- **LLM evaluation & observability** — measuring what production AI systems actually do: accuracy, hallucination, cost, latency
- **Small-model fine-tuning** — LoRA/QLoRA on open models for narrow tasks where frontier APIs are overkill

### Featured projects

| Project | What it does | Stack |
|---|---|---|
| **[ai-data-analysis-agent](https://github.com/VanKaliafetis/ai-data-analysis-agent)** | Autonomous agent that analyses CSV/Excel data — schema inspection, sandboxed pandas execution, chart generation, multi-provider, full trace logging | Python, Groq, Gemini, Streamlit, pandas |
| **[ai-llm-platform-lab](https://github.com/VanKaliafetis/ai-llm-platform-lab)** | LLM infrastructure platform — inference benchmarking, RAG eval, groundedness scoring, SQLite observability, LoRA fine-tuning workflows | FastAPI, Streamlit, Ollama, Hugging Face (PEFT, TRL), SQLite |
| **[AI-Codebase-Assistant](https://github.com/VanKaliafetis/AI-Codebase-Assistant)** | Local-first developer tooling — repo Q&A, file explanations, refactor suggestions, patch previews via semantic retrieval | FastAPI, Streamlit, FAISS, sentence-transformers, multi-provider LLM |
| **[Local-RAG-Knowledge-Platform](https://github.com/VanKaliafetis/Local-RAG-Knowledge-Platform)** | Local-first RAG pipeline — document ingestion, ChromaDB vector store, grounded answers with citations, fully private | FastAPI, Ollama, ChromaDB, sentence-transformers, Docker |
| **[predictive-maintenance-rul-platform](https://github.com/VanKaliafetis/predictive-maintenance-rul-platform)** | Probabilistic RUL prediction on NASA CMAPSS turbofan data with uncertainty estimation and sensor anomaly detection | PyTorch (LSTM), Streamlit, FastAPI, scikit-learn |

### Stack I work in

**Languages:** Python, C, MATLAB, SQL, Bash

**ML/AI:** PyTorch, Hugging Face (transformers, peft, trl), sentence-transformers, scikit-learn

**LLM tooling:** Anthropic / OpenAI / Groq / Gemini APIs, Ollama, function calling, RAG, vector DBs (ChromaDB, FAISS)

**Backend:** FastAPI, Streamlit, Docker, SQLite, Pydantic, async Python

**Engineering:** Git, Linux, pytest, ruff, GitHub Actions

### How I think about AI engineering

- **Cost-aware by default.** Most of my projects run end-to-end on free-tier APIs or local models. Frontier APIs are a tool, not a crutch.
- **No framework lock-in.** I write agent loops, tool dispatchers, and provider abstractions by hand. LangChain hides the things you need to understand to debug production failures.
- **Measure or it didn't happen.** Every project I'm proud of has real eval numbers, not vibes.

### Contact

- 📧 [vkaliafetis@gmail.com](mailto:vkaliafetis@gmail.com)
- 💼 [LinkedIn](https://www.linkedin.com/in/van-kaliafetis-a5a570293/)
- 🌐 Bath, UK · open to remote

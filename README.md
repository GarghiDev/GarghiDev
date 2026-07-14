# Hi, I'm Garghi

**AI Engineer** — I build multi-agent systems, RAG pipelines, and LLM-powered tools that solve real business problems.

Currently freelancing as an AI consultant in Copenhagen, building and deploying production AI tools for industrial clients. My most recent delivery — an automated document pipeline — replaced a 12-hour manual process and is in daily production use.

MSc Engineering Acoustics, DTU. IBM RAG & Agentic AI Professional Certificate (9/9 courses completed).
## 🚀 Projects

### Microfit Agent-1 — Production Document Automation Pipeline
> *Deployed and in daily use by a manufacturing client*

Multi-agent system that automated a 12-hour PPAP document workflow. Ingests raw manufacturing documents, retrieves against a compliance knowledge base, and generates validated output end-to-end.

- **Multi-agent orchestration** with LangGraph: ingestion → RAG retrieval → structured generation → validation
- **Hybrid retrieval**: BM25 + FAISS semantic search over compliance knowledge base
- **Result**: 100+ hours saved, zero manual transcription errors, in production daily
- Stack: `LangGraph` · `Google Gemini 1.5 Pro` · `ChromaDB` · `BM25` · `HuggingFace Transformers` · `Docling` · `Streamlit`
- *Client project — code not public. Architecture and approach available on request.*

### [FinePrint](https://github.com/GarghiDev/fineprint) — Multi-Agent Privacy Policy Analyzer
> *"What data does TikTok actually collect on you?"*

A two-agent system that answers questions about the privacy policies of major platforms — with hallucination detection built in.

- **Research Agent** retrieves answers using **hybrid BM25 + FAISS semantic search** and cites every claim
- **Verification Agent** cross-checks all answers against source documents; triggers a self-correction loop if citations don't hold
- **Live demo:** [https://fineprint-nhxevvabzjbcnfwz2wifce.streamlit.app/]
- Stack: `LangGraph` · `Google Gemini 1.5 Pro` · `FAISS` · `BM25` · `HuggingFace Transformers` · `Docling` · `Streamlit`

---

### [Ask My Thesis](https://github.com/GarghiDev/ask-my-thesis) — RAG Chatbot over Academic Research
> *"Ask questions directly to a 120-page neurophysiology thesis."*

A deployed RAG chatbot that lets users query academic research in plain language.

- Full RAG pipeline: chunking, embedding, vector retrieval, LLM synthesis
- **Live demo:** [huggingface.co/spaces/Garghi/AskMyThesis](https://huggingface.co/spaces/Garghi/AskMyThesis)
- Stack: `LangChain` · `ChromaDB` · `Groq (Llama 3)` · `HuggingFace Embeddings` · `Gradio`

---

## 🛠️ Tech Stack

```
AI/ML       LangChain · LangGraph · HuggingFace · FAISS · ChromaDB · BM25
LLMs        Groq (Llama 3.3-70B) · Google Gemini 1.5 Pro
Frontend    Streamlit · Gradio
Languages   Python · MATLAB
Other       Git · Docling · Tavily API
```

---

## Background

MSc in Engineering Acoustics from DTU — a foundation in systems thinking, signal processing, and quantitative analysis. I spent 7 months at Eriksholm Research Centre (Demant) running multi-sensor experiments and building data pipelines in Python and MATLAB, before moving into AI engineering.

That background shapes how I build: I think about data quality, evaluation, and reliability before I think about model choice.

---

## 📬 Contact

- **LinkedIn:** [linkedin.com/in/garghi](https://www.linkedin.com/in/garghi/)
- **Email:** seegarghi@gmail.com
- **Location:** Copenhagen, Denmark 🇩🇰 

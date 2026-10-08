# Hi, I'm Oli Ahmed 👋

**AI Engineer building production LLM systems, end to end.**
Multi-agent architectures · RAG pipelines · Real-time voice AI · Fine-tuned open-source models

📍 Dhaka, Bangladesh &nbsp;|&nbsp; 🎓 B.Sc. in CSE, East West University (2025)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-oli--ahmed--ai-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/oli-ahmed-ai)
[![Email](https://img.shields.io/badge/Email-oli.niloy1971@gmail.com-D14836?logo=gmail&logoColor=white)](mailto:oli.niloy1971@gmail.com)

---

## About me

I ship LLM systems that people actually depend on, taking a model from notebook to a low-latency service. My work has served healthcare, financial decision-making, enterprise automation, and construction clients. I'm strongest in **Python, FastAPI, and vLLM**, and in the practical engineering that makes AI systems fast, reliable, and maintainable.

Currently an **AI/ML Engineer at Join Venture AI** (Dhaka), where I joined as a trainee in May 2025 and was promoted in July 2025.

---

## Featured projects

### 🎙️ Real-Time Meeting Co-Pilot & Multi-Agent Financial Decision Platform
`Claude` `Deepgram` `Qdrant` `FastAPI` `DuckDB` `WebSockets`

- Real-time co-pilot that listens to live trading calls and delivers structured decision cards on screen in **under 500ms end to end** (Deepgram Nova-2 Live + Claude 3.5 Sonnet).
- Multi-agent orchestrator routing intents across **5 specialized LLM agents** (entry, stop-loss, trade review, cognitive bias, call co-pilot) with structured JSON output and local fallbacks. The behavioral-finance agent flags FOMO, confirmation bias, and narrative reliance in real time.
- DuckDB backtesting engine over **58.8k daily OHLCV bars (8 years)**: 8 deterministic setup detectors, 13.1k signals, Wilson Score confidence intervals, and out-of-sample validation.
- FastAPI backend (8 REST endpoints + WebSockets) with hybrid Qdrant RAG over **341 strategy playbooks** and 4-tier regime-based position gating.

### 💬 Cosmaworks AI: Production Multi-Agent LLM Platform
`Qwen` `LoRA` `RAG` `FAISS` `FastAPI` `vLLM` `RunPod`

- Delivered two production systems: a **Business CS Bot** (Qwen2.5-7B-Instruct) and a **Friend Bot** (Qwen2.5-3B LoRA + RAG).
- Hybrid pipeline serving **5,050 personas** on a fine-tuned Qwen2.5-3B (LoRA r=32) against **30.3k FAISS vectors**.
- Multilingual customer support with 15 deterministic live-data handlers, a two-stage conversational state machine with referral gating, 48 intent-deflection rules, guardrails, and isolated SQLite memory.
- Deployed on a RunPod A6000 (48 GB) with health checks and zero-downtime reloads.

### 🏥 KyroAI: Multi-Modal Clinical Documentation Platform
`Claude` `GPT-4o` `Pinecone` `Vision APIs`

- LLM orchestration pipeline with dynamic prompt injection for specialty-specific clinical reasoning.
- Multi-modal RAG: Pinecone for document retrieval and vision APIs for diagnostic image analysis.
- Deterministic self-correction and fallback routing with **CPT/ICD-10 validation gates** to reduce coding hallucinations.

### More work
- **Citation-aware medical RAG agent** with automated journal citation extraction (Pinecone)
- **Construction material quantity takeoff** from PDFs (custom OCR + Google Vision + LLM reasoning)
- **Voice AI receptionist & booking SaaS** (ElevenLabs, Twilio, OpenAI) with clustering-based customer segmentation

---

## Highlights

- ⚡ Cut a fine-tuning cycle from **~73 hours to ~2 hours** using LoRA/QLoRA on Qwen models
- 🎯 Sub-**500ms** real-time voice-to-decision pipeline
- 🧠 **5,050-persona** conversational system on a fine-tuned open-source model
- 🚀 GPU-heavy inference APIs with health checks and zero-downtime reloads

---

## Tech stack

| Area | Tools |
|---|---|
| **Languages & Data** | Python, SQL, PostgreSQL, MySQL, SQLite, DuckDB |
| **LLMs & Gen AI** | Claude, OpenAI, Gemini, Qwen, Hugging Face Transformers, TRL, PEFT, LoRA/QLoRA |
| **RAG & Vector DBs** | FAISS, Pinecone, Qdrant, ChromaDB, Sentence-Transformers, FastEmbed, Hybrid Search |
| **Real-Time & Multi-Agent** | System Architecture, Multi-Agent Orchestration, Streaming AI |
| **Vision & Voice** | Google Vision API, Multimodal OCR, Deepgram, ElevenLabs, Twilio, Speech-to-Text |
| **ML Frameworks** | PyTorch, TensorFlow, Scikit-learn, Keras |
| **Serving & Infra** | FastAPI, Flask, Gradio, vLLM, WebSockets, RunPod, Redis, Git |

---

## Experience

**AI/ML Engineer**, Join Venture AI (May 2025 – Present)
Production AI systems for international healthcare, finance, enterprise automation, and construction intelligence clients.

**AI | Data Analysis | Product R&D**, Nexaus Cloud (Sep 2024 – Apr 2025)
AI product development, technical R&D, and data analysis using Python and SQL workflows.

---

## Let's connect

I'm open to conversations about LLM systems, RAG, voice AI, and agent architectures.
📫 [oli.niloy1971@gmail.com](mailto:oli.niloy1971@gmail.com) &nbsp;|&nbsp; 💼 [LinkedIn](https://linkedin.com/in/oli-ahmed-ai)

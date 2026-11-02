# Hi, I'm Kyaw Ko Ko San 👋

**AI Engineer building LLM systems for document-heavy workflows: structured extraction, rule-backed decisions, retrieval, and evaluation.**

I design and build the backend pipelines that turn messy documents into reliable, reviewable outputs. My focus is architecture, decision quality, and testing every change before it ships.

---

### 🛠️ What I build

- **Document AI pipelines.** Classification, OCR, and schema-validated extraction from PDFs and images.
- **Rule-backed decision systems.** Deterministic rules own the decisions. LLMs handle only the steps that need judgment, and people do the final review.
- **RAG systems.** Hybrid retrieval, reranking, and grounded answers with source citations.
- **Evaluation.** Regression suites, retrieval metrics, and LLM-as-judge scoring before release.

---

### 📌 Public projects

| Project | What it is | Highlights |
| --- | --- | --- |
| [**warranty-adjudicator**](https://github.com/KyawKoKoSan/warranty-adjudicator) | Staged adjudication lab: extract → YAML policy rules → human-reviewed decision, with reason codes | **12/12** fixture cases agree (mock extractor, deterministic CI) · FastAPI · Pydantic |
| [**bangkok_transit_guide**](https://github.com/KyawKoKoSan/bangkok_transit_guide) | BTS/MRT RAG assistant with transit-graph routing, Streamlit UI, and Postgres/Grafana monitoring | **Hit Rate 0.90 · MRR 0.853 · groundedness 0.97** (30-question eval) · Qdrant · BM25 hybrid + rerank |
| [**DistilBERT LoRA classifier**](https://huggingface.co/kkks05/distilbert-base-uncased-lora-text-classification) | LoRA fine-tune of DistilBERT for text classification | **89.4%** eval accuracy · PEFT |
| [**Text-to-SQL LoRA adapters**](https://huggingface.co/kkks05/Llama-3.1-8B_lora_spider) | Llama 3.x and Qwen2.5-Coder adapters fine-tuned on Spider | Unsloth · TRL · 4-bit QLoRA |
| [**TED-LIUM long-form**](https://huggingface.co/datasets/kkks05/tedlium-longform) | TED-LIUM speech regrouped into longer speaker segments for long-context speech recognition (ASR) | Public Hugging Face dataset |

---

### 🔒 Industry projects

| Project | What it does | Stack |
| --- | --- | --- |
| **Travel insurance claims decision pipeline** | Staged classification → extraction → benefit rules → payout → human review. ~200–300 claims/day; processing cut from 2–3 days to 3–4 minutes | Python · Litestar · SAQ · Gemini (incl. Vision) · LiteLLM · OpenTelemetry |
| **Multi-tenant enterprise RAG chatbot** | Per-client knowledge bases, hybrid retrieval + reranking, FAQ routing, source-cited answers, CMS integration | FastAPI · Qdrant · Voyage · Celery · Redis · WebSockets · Docker |
| **Purchase-order approval workflow (Odoo → LINE)** | LLM-drafted PO summaries sent to managers on LINE to confirm, edit, or cancel, with two-way sync and vendor PDF delivery | Python · Odoo · LINE API · PostgreSQL |
| **Ingredient-to-supplier mapping & recipe costing** | Maps master recipes to supplier purchase data for bill-of-materials and dish-cost analysis. ~84% mapping coverage | Python · pandas · Jupyter |
| **FAQ RAG service** | FAQ search and chat retrieval behind JWT-protected APIs | FastAPI · pgvector · PostgreSQL |
| **Insurance underwriting assistant** 🏆 | Broker-pack extraction, appetite scoring, and recommend/decline drafts. *Claims Category Winner, Agentic AI HyperChallenge 2025* | Multi-agent LLM workflow |

---

### 🧰 Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?logo=opentelemetry&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?logo=huggingface&logoColor=black)

**LLMs and tooling:** Gemini · Claude · GPT-4o · LiteLLM · AutoGen · Pydantic · Unsloth · TRL  
**Retrieval and documents:** Qdrant · pgvector · BM25 hybrid search · reranking · Tesseract · PyMuPDF  
**Services:** FastAPI · Litestar · Celery · SAQ · REST & WebSockets

---

### 🎓 Education & Certifications

- **MEng, Biomedical Engineering & AI**, Kasetsart University (TAIST–Science Tokyo) · NSTDA full scholarship
- **BSc (Hons) Computing, First Class Honours**, Edinburgh Napier University
- **LLM Zoomcamp certificate**, DataTalks.Club

---

### 🔗 Find me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kyawkokosan/)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-kkks05-FFD21E?logo=huggingface&logoColor=black)](https://huggingface.co/kkks05)

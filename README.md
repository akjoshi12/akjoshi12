# Atri Joshi

Data + AI engineer in Toronto. I build data pipelines and LLM applications, and I spend most of my effort on the part that usually gets skipped: checking whether they actually work.

[LinkedIn](https://linkedin.com/in/atrijoshi) · [Portfolio](https://atrijoshi.vercel.app/) · atrijoshi12@gmail.com

---

### Now

**AURA v2**: an emotional-support RAG chatbot. I'm rebuilding it around the data and the evaluation rather than the UI:
- a balanced ~60k-turn corpus merged from four emotional-support datasets (ESConv, AugESC, ExTES, nart-100k) under one schema, with no topic above 15%
- support-strategy labels from a two-model LLM labeler, with agreement reported as Cohen's κ against a hand-labelled gold set
- per-topic evaluation, including adversarial and messy inputs, so a weak topic can't hide behind an average

### Selected work

| Project | What it is | Stack |
|---|---|---|
| [AURA](https://github.com/akjoshi12/Aura---Emotional-Intelligence-RAG-based-Chatbot) | Local, privacy-first wellness chatbot (v1). Chose a quantized large model over a fine-tuned small one after fine-tuning degraded quality. | Python, ChromaDB, Ollama, Streamlit |
| [MinuteMinders](https://minuteminders.web.app) | Meeting transcription and summarization assistant. Led an 8-person team; 7.5% WER on transcription. | Whisper, Pyannote, Mistral, FastAPI, React |
| [resume-factory](https://github.com/akjoshi12/resume-factory) | Local-first resume and cover-letter generator. The model may select and rephrase my real experience but can't add facts. | Python, LangGraph, LaTeX |
| [PDF-to-Audiobook](https://github.com/akjoshi12/PDF-to-Audiobook-Streamlit) | Upload a PDF, pick a voice, get an MP3. | Python, Streamlit |

### Before this

- **Data engineering (2022–23):** Azure Data Factory and Databricks pipelines moving ~200 GB across 100+ tables daily, with bronze/silver/gold data-quality tiers.
- **Research intern (2021–22):** unified handwritten records, scanned PDFs, CSVs, legacy SQL and Excel into one analytics platform; built Flask dashboards for reporting.

### Tools

Python · SQL · PySpark · Databricks · Azure Data Factory · Snowflake · Power BI · LangChain / LangGraph · Ollama · Git

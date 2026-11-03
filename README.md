<p align="center">
  <a href="https://gev44.github.io"><img src="assets/banner.svg" alt="Gevorg Hovhannisyan: AI Engineer, LLM systems, RAG and automation" width="100%"></a>
</p>

<p align="center">
  <a href="https://gev44.github.io"><img src="https://img.shields.io/badge/Portfolio-gev44.github.io-111827?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio"></a>
  <a href="https://t.me/hovhannisyan77"><img src="https://img.shields.io/badge/Telegram-@hovhannisyan77-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="mailto:gev220705@gmail.com"><img src="https://img.shields.io/badge/Email-gev220705@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

### Hi, I'm Gevorg 👋

**AI engineer in Yerevan, Armenia (GMT+4).** I design and ship LLM systems that are grounded, measured and tested: retrieval-augmented assistants that cite their sources, evidence-tracing NLP pipelines, ML models with honest evaluation, and Telegram bots and automations that run 24/7.

I treat an AI feature like any other production system. It needs an evaluation set, a CI pipeline, failure modes that are written down, and a clear "I don't know" when the data doesn't support an answer.

## How I build AI systems

| Principle | Where you can see it |
|---|---|
| **Grounded answers, never invented ones.** Every answer carries the source chunks and scores it came from. | [doc-rag-api](https://github.com/GEV44/doc-rag-api) |
| **Evaluation in CI, not vibes.** Retrieval quality is measured on a fixed eval set on every push. | [doc-rag-api](https://github.com/GEV44/doc-rag-api) |
| **Traceability and documentation.** Each finding links back to a verified quote. The repo ships a model card, data card, evaluation protocol and threat model. | [silent-stakeholder](https://github.com/GEV44/silent-stakeholder) |
| **LLMs that improve wording but never add facts.** The rewrite step is constrained to keep every employer, date and number from the source. | [resume-constructor](https://github.com/GEV44/resume-constructor) |
| **Local-first and vendor-neutral.** Ollama, llama.cpp or any OpenAI-compatible endpoint, with no paid API required. | [doc-rag-api](https://github.com/GEV44/doc-rag-api) · [wardrobe-intelligence-lab](https://github.com/GEV44/wardrobe-intelligence-lab) |
| **Math from first principles when it matters.** Hand-derived gradients and geometry in pure NumPy. | [stereo-distance-calculator](https://github.com/GEV44/stereo-distance-calculator) |

## Featured work

| Project | What it does | Stack |
|---|---|---|
| [**doc-rag-api**](https://github.com/GEV44/doc-rag-api) | Document Q&A service. Upload PDF, TXT or MD, ask questions, and get answers with cited source chunks. BM25 retrieval works offline. Embeddings and an LLM answer step are optional through any OpenAI-compatible endpoint. Test suite plus a retrieval eval in CI. | Python · FastAPI · BM25 · RAG |
| [**resume-constructor**](https://github.com/GEV44/resume-constructor) · [live ↗](https://resume-constructor-gev44.vercel.app) | Full-stack AI resume builder. It scores a resume against a job, rewrites it without inventing facts, and exports ATS-readable PDF and Word. Auth, Postgres with row-level security, Edge Functions, unit and end-to-end tests. | React · TypeScript · Supabase · Vercel |
| [**silent-stakeholder**](https://github.com/GEV44/silent-stakeholder) · [demo ↗](https://gev44.github.io/silent-stakeholder-demo/) | Evidence-grounded LLM pipeline. It turns app reviews and a public roadmap into ranked product opportunities, and every finding is traced to a verified quote. | Python · NLP · Streamlit · pytest · mypy |
| [**wardrobe-intelligence-lab**](https://github.com/GEV44/wardrobe-intelligence-lab) · [live ↗](https://wardrobe-intelligence-lab.streamlit.app) | AI stylist MVP. A transparent scoring engine picks weather- and occasion-aware outfits and learns from feedback, with a local LLM chat (Qwen3 via llama.cpp) in English, Russian and Armenian. | Python · Streamlit · llama.cpp · recommender |
| [**batchcor-rna-embeds**](https://github.com/GEV44/batchcor-rna-embeds) | BostonGene program group project. scGPT embeddings, conditional-autoencoder batch correction and survival prediction on single-cell data. | PyTorch · LightGBM · single-cell |
| [**stereo-distance-calculator**](https://github.com/GEV44/stereo-distance-calculator) | Dual-camera depth estimation. A lens model, ZNCC epipolar matching and triangulation, written in pure NumPy. | NumPy · computer vision |
| [**think-weather-cli**](https://github.com/GEV44/think-weather-cli) | Terminal weather dashboard for any city or postal code, with an hourly chart, a 5-day forecast, JSON output and a cache. | Python · Rich · Open-Meteo |

**Private production systems** (details on the [portfolio](https://gev44.github.io)):

- **Sentinel** is a 24/7 crypto research and paper-trading engine. It has an independent risk engine with hard limits, pre-registered hypotheses judged on forward data, and about 460 tests including property, chaos and API-fuzz tests.
- **EdgeFinder** is a Telegram FX-signal bot with walk-forward testing. It answers "no trade" whenever an edge isn't statistically supported.

## Tech stack

**AI / ML:** RAG, embeddings, BM25 and hybrid retrieval, LLM APIs (OpenAI-compatible, Ollama, llama.cpp), evaluation sets, PyTorch, scikit-learn, LightGBM<br>
**Backend & infra:** Python, FastAPI, PostgreSQL, Supabase, SQLite, Docker, GitHub Actions<br>
**Bots & automation:** Telegram bots, n8n, Make, scrapers, scheduled jobs, Google Sheets and CRM integrations<br>
**Frontend:** React, TypeScript, Tailwind

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/LightGBM-2E7D32?style=flat-square" alt="LightGBM">
  <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" alt="Ollama">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit">
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Telegram_bots-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram bots">
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white" alt="n8n">
  <img src="https://img.shields.io/badge/Make-6D00CC?style=flat-square&logo=make&logoColor=white" alt="Make">
</p>

## Background

- 🧠 **ML Engineer intern** at Mathrix AI (2026)
- 🧬 **BostonGene program** in bioinformatics and data science in oncology (2025–26)
- 🎓 **B.Sc. Informatics & Applied Mathematics**, Yerevan State University (2023–2027)
- 🗣️ English · Russian · Armenian

**Open to AI engineering roles and freelance projects**, remote or in Yerevan. The fastest way to reach me is [Telegram](https://t.me/hovhannisyan77).

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/GEV44/GEV44/output/snake-dark.svg">
  <img alt="Contribution graph animation" src="https://raw.githubusercontent.com/GEV44/GEV44/output/snake.svg">
</picture>

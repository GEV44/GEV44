<p align="center">
  <a href="https://gev44.github.io"><img src="assets/banner.svg" alt="Gevorg Hovhannisyan: AI & Automation Engineer" width="100%"></a>
</p>

<p align="center">
  <a href="https://gev44.github.io"><img src="https://img.shields.io/badge/Portfolio-gev44.github.io-111827?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio"></a>
  <a href="https://t.me/hovhannisyan77"><img src="https://img.shields.io/badge/Telegram-@hovhannisyan77-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="mailto:gev220705@gmail.com"><img src="https://img.shields.io/badge/Email-gev220705@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

### Hi, I'm Gevorg 👋

I'm an **AI & automation engineer in Yerevan, Armenia (GMT+4)**. I build RAG chatbots that answer from your own documents, Telegram bots, LLM pipelines, scrapers and n8n/Make/Python automations, and I ship them with tests.

🎓 B.Sc. Informatics & Applied Mathematics, Yerevan State University (2023–2027) &nbsp;·&nbsp; 🧠 ML Engineer intern at Mathrix AI (2026) &nbsp;·&nbsp; 🧬 BostonGene program in bioinformatics & data science in oncology (2025–26) &nbsp;·&nbsp; 🗣️ English · Russian · Armenian

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/LightGBM-2E7D32?style=flat-square" alt="LightGBM">
  <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" alt="Ollama">
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit">
  <img src="https://img.shields.io/badge/Telegram_bots-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram bots">
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white" alt="n8n">
  <img src="https://img.shields.io/badge/Make-6D00CC?style=flat-square&logo=make&logoColor=white" alt="Make">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions">
</p>

---

## Selected projects

| Project | What it is | Stack |
|---|---|---|
| [**doc-rag-api**](https://github.com/GEV44/doc-rag-api) | Document Q&A API: upload PDF/TXT/MD, ask questions, get answers with cited source chunks. Works with no paid services; optional embeddings and LLM through any OpenAI-compatible endpoint (e.g. Ollama). 24 tests + retrieval eval in CI. | Python · FastAPI · BM25 · RAG |
| [**resume-constructor**](https://github.com/GEV44/resume-constructor) · [live](https://resume-constructor-gev44.vercel.app) | AI resume builder: scores a resume against a job, rewrites it without inventing facts, exports ATS-readable PDF and Word. Auth, Postgres with row-level security, Edge Functions, unit + e2e tests. | React · TypeScript · Supabase · Vercel |
| [**wardrobe-intelligence-lab**](https://github.com/GEV44/wardrobe-intelligence-lab) · [live](https://wardrobe-intelligence-lab.streamlit.app) | AI stylist MVP: weather- and occasion-aware outfits, learns from likes/dislikes, local LLM chat (Qwen3 via llama.cpp) in EN/RU/HY. | Python · Streamlit · llama.cpp · recommender |
| [**silent-stakeholder**](https://github.com/GEV44/silent-stakeholder) · [demo](https://gev44.github.io/silent-stakeholder-demo/) | Evidence-grounded LLM pipeline: turns app reviews and a public roadmap into ranked product opportunities, every finding traced to a verified quote. | Python · NLP · Streamlit · pytest/mypy |
| [**think-weather-cli**](https://github.com/GEV44/think-weather-cli) | Terminal weather dashboard for any city or postal code: hourly chart, 5-day forecast, JSON output, cache. | Python · Rich · Open-Meteo |
| [**batchcor-rna-embeds**](https://github.com/GEV44/batchcor-rna-embeds) | BostonGene program group project: scGPT embeddings, conditional autoencoder batch correction, survival prediction. | PyTorch · LightGBM · single-cell |
| [**stereo-distance-calculator**](https://github.com/GEV44/stereo-distance-calculator) | Dual-camera depth estimation: lens model, ZNCC epipolar matching, triangulation, written in pure NumPy. | NumPy · computer vision |

Private: **EdgeFinder** (Telegram FX-signal bot with walk-forward testing that says "no trade" when nothing is proven) and **Sentinel** (24/7 crypto research and paper-trading engine with a risk gate and ~460 tests). Details on the [portfolio](https://gev44.github.io).

## What I work with

**AI / ML:** RAG, embeddings, LLM APIs (OpenAI-compatible, Ollama, llama.cpp), evaluation sets, LightGBM, PyTorch, scikit-learn
**Backend & bots:** Python, FastAPI, Telegram bots, SQLite/Postgres, Supabase, Docker, GitHub Actions
**Automation & data:** n8n, Make, scrapers, scheduled jobs, Google Sheets/CRM integrations
**Frontend:** React, TypeScript, Tailwind, plain HTML/CSS

## How I work

- A working demo before you decide anything.
- Assistants answer only from approved content, show their sources and say "I don't know" when the documents don't cover a question.
- Tests and a short README with every delivery.

Open to freelance projects and junior/mid AI engineering roles (remote or Yerevan).

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/GEV44/GEV44/output/snake-dark.svg">
  <img alt="Contribution graph animation" src="https://raw.githubusercontent.com/GEV44/GEV44/output/snake.svg">
</picture>

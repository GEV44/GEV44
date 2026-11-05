# Gevorg Hovhannisyan

AI/ML engineer in Yerevan, Armenia. I build systems that run in production: LLM pipelines with a deterministic fallback, Telegram bots and web dashboards around them, retrieval with citations, and computer vision from first principles in NumPy.

**Currently**
- Running **[Gevstate](https://github.com/GEV44/gevstate)** for a Yerevan real-estate agency: a trilingual (Armenian · Russian · English) lead platform that turns every inquiry from Telegram, web, e-mail and RSS into one tracked lead, matches it to live homes and puts a card in the agents' Telegram within seconds. FastAPI + HTMX, aiogram, Claude with a rules fallback (the pipeline never blocks on AI), 1,144 tests, Windows + Linux CI.
- ML Engineer intern at Mathrix AI (2026) · B.Sc. Informatics & Applied Mathematics, Yerevan State University (2023–2027) · BostonGene bioinformatics & data-science-in-oncology program (2025–26).
- Open to mid-level AI/ML engineering roles, remote or Yerevan, and to agencies who want Gevstate under their own brand.

**Selected work**
| Project | What it proves | Stack |
|---|---|---|
| [gevstate](https://github.com/GEV44/gevstate) · [live demo](https://gevllm-gevstate.hf.space) | Production LLM system: extraction in 3 languages + translit, dedupe, scoring, matching, follow-ups, live dashboard by source, white-label config. | Python · FastAPI · HTMX · aiogram · SQLAlchemy · Claude |
| [stereo-distance-calculator](https://github.com/GEV44/stereo-distance-calculator) | Computer vision without libraries: analytic gradients, a 5×5 gamma-grid lens model, ZNCC epipolar matching, OLS triangulation; tested against a synthetic rig with published error curves. | NumPy · pytest |
| [doc-rag-api](https://github.com/GEV44/doc-rag-api) | RAG done honestly: BM25 first, optional embeddings and any OpenAI-compatible LLM, answers cite their chunks, retrieval eval in CI, 24 tests. | FastAPI · BM25 · Ollama |
| [silent-stakeholder](https://github.com/GEV44/silent-stakeholder) · [demo](https://gev44.github.io/silent-stakeholder-demo/) | Evidence-grounded LLM pipeline: app reviews + a public roadmap → ranked product opportunities, every claim traced to a verified quote. | Python · NLP · Streamlit |
| [resume-constructor](https://github.com/GEV44/resume-constructor) · [live](https://resume-constructor-gev44.vercel.app) | AI resume builder that scores against a job and rewrites without inventing facts; auth, Postgres with row-level security, unit + e2e tests. | React · TypeScript · Supabase |
| [wardrobe-intelligence-lab](https://github.com/GEV44/wardrobe-intelligence-lab) · [live](https://wardrobe-intelligence-lab.streamlit.app) | Recommender MVP that learns from feedback, local LLM chat (Qwen3 via llama.cpp) in EN/RU/HY. | Python · Streamlit · llama.cpp |

Private: **EdgeFinder** (FX-signal Telegram bot with walk-forward testing that says "no trade" when nothing is proven) and **Sentinel** (24/7 crypto research and paper-trading engine with a risk gate, ~460 tests).

**How I work**
- A working demo before any decision; tests and a short README with every delivery.
- AI is never the database: deterministic rules and filters first, the model enriches, every answer shows its source or says "I don't know".
- Compliance by design: no scraping where it is forbidden, minimal personal data, humans send outreach.

**Stack** Python 3.12, FastAPI, SQLAlchemy, aiogram, Telethon, HTMX, pytest, GitHub Actions · PyTorch, scikit-learn, LightGBM, NumPy · Claude API, OpenAI-compatible APIs, Ollama, llama.cpp · React, TypeScript, Supabase, Docker · n8n, Make

[gev44.github.io](https://gev44.github.io) · Telegram [@hovhannisyan77](https://t.me/hovhannisyan77) · gev220705@gmail.com

<div align="center">

# Gevorg Hovhannisyan
### AI & Machine Learning Systems Engineer · Yerevan, Armenia

[![Portfolio](https://img.shields.io/badge/Portfolio-gev44.github.io-8B5CF6?style=for-the-badge&logo=safari&logoColor=white)](https://gev44.github.io)
[![Telegram](https://img.shields.io/badge/Telegram-@hovhannisyan77-2BA8E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/hovhannisyan77)
[![Email](https://img.shields.io/badge/Email-gev220705@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gev220705@gmail.com)

<p align="center">
  <b>B.Sc. Informatics & Applied Mathematics</b>, Yerevan State University (2023–2027)<br>
  <b>ML Engineer Intern</b>, Mathrix AI (2026) · <b>Bioinformatics Engineer</b>, BostonGene program (2025–26)
</p>

---

</div>

### 🚀 Production Flagship: [YourRealty](https://github.com/GEV44/gevstate)
> **Autonomous 24/7 Real-Estate AI Radar & Lead Matching Engine**  
> Running in production for Yerevan agencies · [Open Agent Workspace](https://yourrealty.vercel.app/app) · [Interactive Home Finder](https://yourrealty.vercel.app/app/find) · [Client Request Form](https://yourrealty.vercel.app/request)

<p align="center">
  <a href="https://yourrealty.vercel.app/app">
    <img src="https://raw.githubusercontent.com/GEV44/gevstate/main/docs/img/social-preview.png" alt="YourRealty Preview" width="100%">
  </a>
</p>

- **24/7 Autonomous Cloud Ingest:** Continuously scrapes and parses listings across 12 public Telegram channels, public groups, web requests, and forwarded screenshots without requiring a local PC.
- **Dual-Stage Probability Calibration:** Integrates **TypeSafe Jev AI** to mathematically separate real housing seekers ($P \ge 0.90$) from agency advertisements and noise, with deterministic SQL fallback that never blocks on rate limits.
- **Instant Match Cards:** Ranks 8,983+ indexed Yerevan properties across Kentron, Arabkir, Davtashen, and 9 other districts; delivers ready lead cards with contact buttons into agents' Telegram within 2.4 seconds.
- **Security & Access Control:** Public cloud demo allows read-only exploration of live search, listings, and multilingual switching. Administrative actions and lead modifications are secured by a protected login panel (`/app/login`) with host-generated credentials.
- **Engineering Discipline:** 1,144 pytest unit & integration tests, SQLite WAL mode, async queue architecture, trilingual support (**Armenian · Russian · English** + Latin transliteration).

---

### 🛠️ Featured Systems & Technical Proofs

| Project | System Architecture & Proof | Tech Stack | Status |
|---|---|---|---|
| **[YourRealty](https://github.com/GEV44/gevstate)** · [Demo](https://yourrealty.vercel.app/app) | Real-estate radar & AI lead matcher; 35k posts/wk, 1,144 tests, 24/7 serverless runtime | Python 3.12 · FastAPI · HTMX · TypeSafe Jev AI · SQLite WAL | ![Live](https://img.shields.io/badge/Running-24%2F7-22C55E?style=flat-square) |
| **[stereo-distance-calculator](https://github.com/GEV44/stereo-distance-calculator)** · [Math PDF](https://github.com/GEV44/stereo-distance-calculator/blob/main/docs/MATHEMATICAL_FOUNDATION.pdf) | Computer vision from first principles: analytic gradients, 5×5 gamma lens model, ZNCC epipolar matching, 6.0% median error on 27 calibrated points | NumPy · SciPy · pytest | ![Research](https://img.shields.io/badge/CV-Research-60A5FA?style=flat-square) |
| **[wardrobe-intelligence-lab](https://github.com/GEV44/wardrobe-intelligence-lab)** · [Demo](https://wardrobe-intelligence.streamlit.app) | Context-aware AI stylist MVP: FashionSigLIP zero-shot tagging, outfit scoring, local Qwen3 chat via llama.cpp | Python · Streamlit · PyTorch · FastAPI | ![Live](https://img.shields.io/badge/Streamlit-Live-FF4B4B?style=flat-square) |
| **[Sentinel](https://gev44.github.io)** | Crypto research & paper-trading engine on Solana, Base & BSC; automated honeypot/mint gates, 10 pre-registered hypotheses tracked for 30d | Python · TimescaleDB · Playwright · Risk Engine | ![Live](https://img.shields.io/badge/Running-24%2F7-22C55E?style=flat-square) |
| **[resume-constructor](https://github.com/GEV44/resume-constructor)** · [Live App](https://resume-constructor-gev44.vercel.app) | AI resume builder: parses PDF/DOCX, scores against 36 job roles, suggests grounded rewrites; auth, Postgres RLS, Edge Functions | React · TypeScript · Supabase · Gemini | ![Live](https://img.shields.io/badge/Live-Production-F59E0B?style=flat-square) |
| **[doc-rag-api](https://github.com/GEV44/doc-rag-api)** | Grounded document Q&A over HTTP; answers cite source chunks and similarity scores, refuses unknown questions; 24 CI tests | Python · FastAPI · BM25 · Ollama / OpenAI | ![Open Source](https://img.shields.io/badge/Open-Source-22C55E?style=flat-square) |
| **[silent-stakeholder](https://github.com/GEV44/silent-stakeholder)** · [Demo](https://gev44.github.io/silent-stakeholder-demo/) | Evidence-grounded review analysis: 6-stage NLP pipeline turning app reviews into ranked opportunities; 26/26 verified spans | Python · NLP · Streamlit · pytest | ![Demo](https://img.shields.io/badge/Live-Demo-A855F7?style=flat-square) |
| **[EdgeFinder](https://gev44.github.io)** | Honest FX signal bot: 11 pairs × 4 expiries, LightGBM classifier with walk-forward testing; says NO TRADE when unproven | Python · LightGBM · Dukascopy · Telegram | ![Tested](https://img.shields.io/badge/Walk--Forward-Validated-EAB308?style=flat-square) |
| **[think-weather-cli](https://github.com/GEV44/think-weather-cli)** | Fast terminal weather dashboard with hourly charts, 5-day forecasts, caching & metric/imperial units | Python · Rich CLI · REST API | ![CLI](https://img.shields.io/badge/Open-Source-EAB308?style=flat-square) |

---

### 💻 Core Stack & Competencies

```
Languages:     Python 3.12 (Expert), SQL, TypeScript, JavaScript, Bash
AI & ML:       Claude API, OpenAI API, TypeSafe Jev AI, PyTorch, LightGBM, scikit-learn, NumPy, RAG, Ollama
Backend:       FastAPI, SQLAlchemy, SQLite (WAL mode), PostgreSQL, TimescaleDB, Docker, Linux/systemd
Frontend & UI: HTMX, Tailwind CSS, React, Streamlit, Jinja2
Automation:    aiogram 3.x, Telethon, Playwright, n8n, Make, Web Scraping (httpx, BeautifulSoup)
Testing & CI:  pytest, GitHub Actions CI/CD, mypy, Ruff
Languages:     Armenian (Native), Russian (Fluent), English (Professional)
```

---

### 🤝 How I Work
- **Working Demo First:** You see the working system on your real data before paying.
- **Deterministic Guardrails:** AI enriches and classifies, but deterministic SQL rules enforce hard constraints. Zero silent hallucinations.
- **Production Hardened:** Full automated test suites (pytest), graceful error handling with DB-backed queues, zero-downtime cloud deployments.

📬 **Reach out:** [Telegram @hovhannisyan77](https://t.me/hovhannisyan77) · [Email: gev220705@gmail.com](mailto:gev220705@gmail.com) · [Portfolio: gev44.github.io](https://gev44.github.io)

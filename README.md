# Hi, I'm Varun 👋

**Full-stack engineer in Chicago, IL** — six years shipping production software across healthcare, fleet management, and education, plus personal projects in payroll, trading, and agent tooling.

I work end-to-end: backend → APIs → frontend → deploy → infra. I bias toward correctness — tested engines, deterministic scoring, and a human in the loop whenever software pays people or publishes on their behalf.

🌐 **[www.terminatrx.com](https://www.terminatrx.com)** — portfolio, where each project below is written up at depth.

---

## 🚀 Projects

### ⭐ [PayrollTracker](https://github.com/TerminatrX/PayrollTracker)
Real Illinois payroll, on the desktop. Tauri 2 + React shell over a tested .NET 8 tax engine (IRS Pub 15-T / IL-700-T withholding) running as a JSON-RPC sidecar. Throws rather than guess a tax year it has not verified against primary sources.
`Rust` `.NET 8` `React` `SQLite`

### ⭐ [agentic-trader](https://github.com/TerminatrX/agenticTrader)
Agent-driven equity trading for Robinhood, built on the Robinhood MCP server. Claude fetches data and argues against the trade; a deterministic Python core makes every decision. Nothing in `src/` can reach the broker, and the critic may shrink a position but never enlarge one. Shadow mode — no live trades.
`Python` `MCP` `SQLite` `pytest`

### [ResuLens](#)
AI career copilot — tailors your resume to a job posting (LaTeX-typeset PDFs), scores ATS match *before* you apply, tracks every application, and turns outcomes into insight. The reviewer pass removes claims the base resume doesn't support.
`Next.js 15` `Prisma` `Postgres` `OpenAI` `Stripe`

### [ML Trading Bot](#)
Production futures bot (ES/NQ/GC) — rule-based strategies with an optional PPO RL filter that can veto or shrink an entry but never create one, realistic backtesting, prop-firm risk controls, and a dashboard that shows empty states rather than fabricated P&L.
`Python` `PyTorch` `Postgres`

### [Authorized Clipper](#)
Agentic, human-approved video-clipping pipeline. FastAPI media worker (download → transcribe → LLM editorial scoring → vertical render) feeding a Next.js review/approval dashboard. Nothing publishes without human approval.
`FastAPI` `Next.js` `Whisper` `FFmpeg`

### ⭐ [Life Dashboard OS](https://github.com/TerminatrX/Life-Dashboard-OS)
A personal *"what should I focus on today?"* OS — recommendations over dashboards. Local-first by design.
`Next.js` `FastAPI` `pgvector` `Redis` `LangGraph`

<sub>⭐ = public repo. Public is not the same as open source — PayrollTracker and agentic-trader are all rights reserved.</sub>

---

## 🛠 Tech I reach for

| | |
|---|---|
| **Languages** | C# · TypeScript · Java · Python · Rust |
| **Frontend** | React · Next.js (App Router) · Angular · React Native · Tauri |
| **Backend** | .NET Core · ASP.NET Core · Spring Boot · FastAPI · Node |
| **Data & search** | SQL Server · PostgreSQL (+pgvector) · Elasticsearch · Redis · SQLite |
| **Cloud & CI/CD** | AWS · Docker · OpenShift · Jenkins · UrbanCode Deploy |
| **AI** | OpenAI · LangGraph agents · MCP · reinforcement learning (PPO) |

---

## 🧭 How I work

- **Correctness first** — verified tax tables, deterministic scoring, tests around anything with a right answer
- **Human-in-the-loop** for anything that moves money or publishes on someone's behalf
- **Local-first & privacy-conscious** by default
- **Unknown is refused, never assumed benign** — a control that cannot fail is worse than a missing one

---

📍 Chicago, IL · 📚 Currently going deeper on distributed systems & agent tooling

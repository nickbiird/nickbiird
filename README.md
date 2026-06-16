# Hi, I'm Nicholas Bird 👋

**I find the real problem, build the AI system, measure it, and own the outcome.**

I'm a final-year ESADE student (BBA + AI for Business, Barcelona) who works as an **operator-translator** — the person who sits between a business problem and the engineering, picks the right architecture (agents, MCP, retrieval, access control, cloud), ships it, and can still explain the ROI to a CFO. Not a pure engineer, not a slide-deck strategist. I build things that work in production, and I put an honest number on each one.

The project that taught me the most isn't open-source: I designed and shipped a **live, multi-tenant B2B SaaS, solo** — FastAPI, PostgreSQL row-level security, Next.js, multi-agent LLM orchestration, 800+ tests. The repos below are how I show that craft in the open — each is a real system with its evals, its cost-per-task, and its honest limits documented.

## What I'm building in the open

**Enterprise AI — done safely, and measured**

- 🔐 **[zero-trust-mcp-gateway](https://github.com/nickbiird/zero-trust-mcp-gateway)** — an MCP server built as an **OAuth 2.1 resource server**: PKCE + on-behalf-of tokens → **Cerbos** attribute-based access control → **Postgres row-level security** as a second, independent layer. An AI agent can only ever read what the *invoking user* is allowed to see — it solves the "confused-deputy" problem most agent demos ignore. Proven by a trust report that regenerates itself in CI: **100% deny across 698 live adversarial requests, 0% false-positive, sub-millisecond authorization overhead.** *My flagship.*
- 🪜 **[authority-ladder](https://github.com/nickbiird/authority-ladder)** — drop in a backlog of candidate AI use cases, get back a defended, priced transformation roadmap: an AI-or-not verdict, a place on the autonomy ladder, a defended architecture, an EU-AI-Act risk tier, and a **cost-per-task** — each one adversarially reviewed and held behind a durable human approval gate before anything commits.
- ⚖️ **[ai-act-triage](https://github.com/nickbiird/ai-act-triage)** — describe an AI use case in plain language and get a **cited EU AI Act risk-tier** classification that has survived an adversarial critic and a human gate — for cents, with the eval scorecard published. Triage, not legal advice — and that distinction is the point.

**Retrieval, ML & cloud**

- 🎯 **[ICP Radar](https://icp-radar.vercel.app)** — semantic target-account discovery over **~3,800 European startups**, browser-side vector search, **$0 to host**, plus a Challenger-style outreach drafter. Raw data → an actionable target market. *Live.* *([code](https://github.com/nickbiird/icp-radar))*
- 🤖 **[mcp-ai-workspace](https://github.com/nickbiird/mcp-ai-workspace)** — a from-scratch **MCP server** + vector-RAG pipeline + a retrieval **evals harness** (hit@k / MRR). Proof I can wire up *and measure* agentic retrieval, no framework magic.
- 🛰️ **[Tambopata Mining Monitor](https://github.com/nickbiird/Tambopata-Mining-Monitor)** — satellite ML that flags *illegal* gold mining in the Peruvian Amazon for enforcement, validated honestly on a leakage-free holdout (86% recall). *Group capstone, grounded in real SERNANP stakeholder interviews.*
- ☁️ **[TravelHelp](https://github.com/nickbiird/TravelHelp)** & **[self-hosted-llm-aws-deploy](https://github.com/nickbiird/self-hosted-llm-aws-deploy)** — a fully serverless AWS recommender (Terraform IaC, Lambda, Cognito) and an AWS deployment of a self-hosted LLM + MCP + RAG stack with real TLS on EC2. *Team / coursework projects — honestly credited.*

## Now

🎓 Finishing ESADE (BBA + AI for Business) · 📊 **Gartner** Sales Academy, summer 2026 — learning how C-suites actually buy · 🇨🇳 **Tsinghua** SEM exchange, Beijing, Fall 2026 · 🌍 Heading toward a role at the intersection of **AI, enterprise GTM, and transformation** — Barcelona, Madrid, or London (British–Spanish dual national, no sponsorship needed in the EU or UK) — with a **West↔China** chapter ahead.

## Beyond the code

14 years of basketball, classical piano, and long Mediterranean runs — and a stubborn belief that the best technology is the kind someone actually uses. I build to give real problems a useful answer, and to earn the freedom to keep building.

## Reach me

[LinkedIn](https://www.linkedin.com/in/nicholasbirdsanahuja) · Barcelona

<sub>Languages: English · Spanish · Catalan (native) · German (basic) · Mandarin (learning, survival level)</sub>

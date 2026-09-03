# Matvei Evgenyevich Vasetsov

**Systems & Business Analyst · Vibe-Coder · PhD in Mathematics**

[![Yahoo](https://img.shields.io/badge/Yahoo-6001D2?style=flat&logo=yahoo&logoColor=white)](mailto:matvey_v@yahoo.com) matvey_v@yahoo.com &nbsp;·&nbsp; 📱 +7 921 900-86-18 &nbsp;·&nbsp; [![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=flat&logo=telegram&logoColor=white)](https://t.me/matveivasetsov) [@matveivasetsov](https://t.me/matveivasetsov) &nbsp;·&nbsp; [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/MatveiV) [MatveiV](https://github.com/MatveiV) &nbsp;·&nbsp; [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/matvei-vasetsov-777b66a)

🇷🇺 [Русская версия](README.md)

---

> *A trading platform, a settlement system, or an AI agent for your process: 20 years in FinTech + Python + AI/LLM tooling → MVP.*

---

## About Me

Systems/business analyst with 20 years of FinTech experience. I specialize in translating business requirements into architectural solutions and MVPs, and in designing high-load systems — trading platforms and settlement systems. Since 2024, an active AI/LLM builder (vibe-coding): I design multi-provider AI architectures, RAG pipelines, MCP servers and AI agents, and take them to production. Focused on measurable business outcomes through deep analysis and effective communication between business and development.

Registered as a Sole Proprietor (IE) in Russia since April 2023; since 07.2024 — full focus on own AI/LLM products and independent systems-analysis consulting.

I bridge business and development: gathering requirements, designing architecture, and automating routine work in Python — saving you iterations and money.

---

## Projects

### AI / LLM 

- **[Analyst-Architect-AI](https://github.com/MatveiV/Analyst-Architect-AI)** — an AI assistant for systems analysts: spec review with honest `needs_review`/`confidence` labels, batch processing of up to 50 specs, URS/SRS/ADR generation per GOST 34.602-2020, 8 diagram types (C4/UML/ERD) rendered locally via Kroki, economic evaluation (CAPEX/OPEX/ROI), a RAG knowledge base with auto-indexing, full LLM-call auditing (including local Ollama/Qwen in air-gapped mode). **Stack:** FastAPI + SQLAlchemy (async) + SQLite/PostgreSQL, React 18 + Vite + TypeScript + Tailwind, 5 LLM providers, JWT + RBAC, 146 pytest tests.
- **[Agent-SystemAnalyst_MemoryFrameworks](https://github.com/MatveiV/Agent-SystemAnalyst_MemoryFrameworks)** — an interactive agent on **LangChain + LangGraph** supporting 7 AI frameworks (LlamaIndex, Haystack, Semantic Kernel, CrewAI, AutoGen, DSPy), each changing the working mode and toolset. Generates SRS/URS and ADR documents with architecture and API recommendations.
- **[RAG-Agent](https://github.com/MatveiV/RAG-Agent)** — an intelligent assistant on **LangChain + Pinecone**: a full RAG cycle, semantic search, automatic web-page indexing, user-activity analytics.
- **[FinAnalyst-Haystack-Docling-Agent](https://github.com/MatveiV/FinAnalyst-Haystack-Docling-Agent)** — a modular financial Telegram bot on **Haystack 2 + Docling + Pinecone**: local OCR/layout via PyTorch, a RAG pipeline, automatic document summarization, Alpha Vantage, Finviz Vision and SerperDev tools.
- **[AI Client PDF Generator](https://github.com/MatveiV/AI_Client_PDF_Generator)** — automated PDF report generation from client-call transcripts: LLM → structured JSON → Jinja2 → WeasyPrint.
- **[LangChain Pipeline Generator](https://github.com/MatveiV/LangChain_Pipeline_Generator)** — auto-generates Telegram bots and documentation (SRS, URS) from a text description via LLM chains.
- **[Prompter](https://github.com/MatveiV/Prompter)** — a CLI for A/B-testing prompting techniques (zero-shot, few-shot, CoT, role-based) with ranking and Markdown/DOCX report generation.

### ML / Finance

- **[TradingRobotMarketplace](https://github.com/MatveiV/TradingRobotMarketplace)** — a Copy Trading platform for MT4/MT5 trading robots. **Backend:** FastAPI + SQLAlchemy + Pydantic v2 (25+ endpoints). **Frontend:** React 19 + TypeScript + Vite + shadcn/ui. A three-tier fee system, a deploy pipeline, SRS v4.0 (BPMN, Sequence, C4, State).
- **[ML_Fin_Notebooks](https://github.com/MatveiV/ML_Fin_Notebooks)** — ML in finance: strategy backtesting, feature engineering (EMA, RSI, MACD), classification, time-series forecasting (LSTM, TFT).

### Infrastructure & Backend

- **[Orders CRM](https://github.com/MatveiV/OrdersCRM)** — a premium CRM system for lead management with intelligent scoring. **Production:** orderscrm.ru. **Stack:** FastAPI + PostgreSQL 16 (asyncpg) + Nginx + Docker Compose + Watchtower. JWT auth, lead scoring (8 criteria), behavioral metrics, production security (rate limiting, security headers).
- **[MiniCRM](https://github.com/MatveiV/MiniCRM)** — a CRM with two interfaces: a Tkinter desktop GUI and a FastAPI REST API. SQLite, report export to Google Sheets, Docker containerization.
- **[Refactoring_MV](https://github.com/MatveiV/Refactoring_mv)** — refactored Python code (eliminating SQL injections, connection leaks, race conditions) with a parallel REST API implementation in Go. Two Docker images on Docker Hub.
- **[Loki-Grafana](https://github.com/MatveiV/Loki_Grafana)** — a centralized logging stack (Loki + Grafana) with Docker Compose and bash auto-install scripts.
- **[CoinParser](https://github.com/MatveiV/CoinParser)** — a Telegram channel parser with crypto-symbol filtering, Google Sheets API integration and XLSX export.

### Bots (most relevant for target roles)

- **[MultiTools AI Agent Bot](https://github.com/MatveiV/MultiTools_AI_Agent_Bot)** — a Telegram bot with 5 AI providers, 8 roles, image/video generation, dialogue memory and RUB cost tracking.
- **[Product MCP Bot](https://github.com/MatveiV/Product_MCP_Bot)** — an MCP server (FastAPI) + Telegram bot with LLM tool calling. 10 tools: product catalog, calculator, CoinGecko, RAWG.
- **[Team Assistant Telegram Bot](https://github.com/MatveiV/Team-Assistant-Telegram-Bot)** — a smart team Telegram bot on **Haystack 2.x + Pinecone + OpenAI**: text, voice messages and documents, RAG answers over chat context.

---

## Work Experience

### 07.2024 — Present · Sole Proprietor (IE) · Systems/Business Analyst, AI/LLM Developer, Quantitative Researcher

*Registered as a Sole Proprietor (IE) in Russia since April 2023, during the Tastyworks engagement at Raccoonsoft/Devexperts; since 2024 — full focus on AI/LLM development.*

Multi-provider AI architecture design, FSM configurator development, RAG pipeline implementation, Python code refactoring, Go REST API implementation, multi-stage Docker image builds.

**Key achievements:**

- A unified OpenAI-compatible architecture for 5 different providers with no bot code changes.
- An AI agent with 11 tools and an MCP server: two independent UIs (CLI and Telegram) on one core.
- A full port of a Flask service to Go: 20x more concurrent requests with a 10 MB image vs. 150 MB.
- Analyst-Architect-AI — a full-fledged AI-analyst platform (146 automated tests, a full E2E run, 2 critical bugs found and fixed).
- Orders CRM and TradingRobotMarketplace — taken to production / SRS v4.0.
- A set of ML strategies for financial time series with confirmed results on historical data.

### 04.2025 — 11.2025 · Techcoredev.ru (JSC "Innovative Technologies") · Systems Analyst

**Project:** insurance product management system. Full-cycle specification development, architecture design (BPMN, ERD, UML, C4), legacy system reverse engineering using AI.

**Achievement:** accelerated the design phase by introducing AI for generating standard documentation fragments and analyzing legacy code.

*Node.js, DBeaver, MS SQL Server, Confluence, Cursor, Windsurf, Draw.io, PlantUML, Figma.*

### 04.2021 — 03.2024 · Raccoonsoft.ru & Devexperts.com · Lead Analyst

**Project:** the Tastyworks iPad mobile trading platform for stocks, derivatives, bonds, FX and crypto (tastytrade.com). Elicited and modeled requirements in user stories and system specifications. Reverse-engineered the mobile app and the platform's thick and thin clients.

**Achievement:** successful product launch; reduced development-phase iterations through detailed requirements maintained in Jira.

*JIRA, GitHub, Figma, Java, MindManager, Slack.*

### 12.2013 — 04.2025 · LLC "LANIT-TERCOM" · Lead Analyst

- **Housing/utility services for VTsKP-EIRTs** (Saint Petersburg) and **GIS ZHKH**. Requirements elicitation, legacy reverse engineering (DFD/IDEF0/BPMN/EPC/ARIS/C4). *Oracle, PostgreSQL, 1C, PowerDesigner, ARIS, Bizagi, JIRA, Confluence, Enterprise Architect.*
- **MESH for the Moscow IT Department** (school-olympiad management). BFT analysis, functional/technical specs, UML sequence diagrams. *PostgreSQL, Java, Kafka, JIRA, Confluence, Grafana, Postman.*
- **VEGA FEM and "Digital Twin of Seismic Exploration"** for Gazprom Neft. *ARIS, MSSQL Server, 1C.*
- **Cancer Registry** within EMIAS for the Moscow IT Department.
- **Toyota** (Toyota Motor Russia) — Vision and technical specs for the warehouse and quality-control subsystems.
- **AREA9** for Area9 Lyceum — adaptation of an adaptive-learning SaaS platform, UI and content localization.
- **Presale estimates:** ETWeb Enterprise, GIS TEK SPb, systems for Rosatom, "Traffic Management" for YOTA, "Inventory" for Rosnedra, and others.

### 05.2013 — 12.2013 · Deutsche Telekom IT Solutions · Senior Business Analyst

**Project:** De-mail — a notarized e-mail service. Analyzed functional requirements, produced business-process descriptions, specifications and diagrams (DFD, ERM, BPMN, UML).

*Polarion, JIRA, Confluence, Enterprise Architect, MindManager.*

### 05.2012 — 03.2013 · TKB BNP Paribas Investment Partners · Senior Business Process Analyst

**Projects:** asset portfolio management models, structured products, Value-at-Risk, CAPM, ATP, MTS-ATS-Robot, data quality, data mining.

*Excel, yEd, QUIK, MetaTrader 4/5 (+MQL), 1C, MS SQL.*

### 08.2007 — 05.2012 · Devexperts.com · Business/Systems/Financial Analyst

**Projects:** algorithmic trading strategies, FX and binary options, technical analysis, dealing, mobile clients, FIX integration, risk management, back-office. Platforms: ThinkOrSwim, GFT Dealbook 360, DXtrade.

*DOORS, Polarion, JIRA, Confluence, Enterprise Architect, FIX protocol.*

### 02.2006 — 08.2007 · Visual Trading Systems LLC · Business Analyst

**Project:** ATS and Backtesting Engine modules for the VT Trader platform (Capital Market Services FX).

*VT Trader, MetaTrader (+MQL), MetaStock, Tradestation, Wealth-Lab.*

---

## Technologies

| Category            | Stack |
| ------------------- | ----- |
| Languages            | Python 3.10+, Go 1.22, TypeScript, SQL, Java, Bash, MQL, TeX |
| AI / LLM             | OpenAI API, Claude, Gemini, DeepSeek, GLM, Llama, Qwen, Kimi; function/tool calling; MCP; prompt engineering; RAG; FAISS, sentence-transformers |
| Frameworks / UI      | FastAPI, Flask, React 18/19, Vite, Tailwind CSS, aiogram 3, LangChain, Haystack 2, openai SDK, ChromaDB, Pinecone, SQLAlchemy (async), Alembic, pytest, Nginx |
| Data / API           | SQLite, PostgreSQL, Oracle, MS SQL Server, 1C, pandas, Google Sheets API, Google Drive API |
| ML                   | scikit-learn, LightGBM, PyTorch, PyTorch Lightning, optuna, backtesting |
| Infrastructure       | Docker, Docker Compose, Grafana Loki, GitHub Actions |
| BA / SA tools        | Confluence, JIRA, Redmine, Polarion, DOORS, ARIS, Bizagi, Enterprise Architect, PlantUML, Draw.io, Miro, Figma, Visio, PowerDesigner, DBeaver, Postman, Mermaid (C4, BPMN, UML), Kroki |
| Trading platforms    | Tastytrade, MetaTrader 4/5, DealBook 360, ThinkOrSwim, VT Trader, QUIK, Tradingview |
| Standards            | PMBoK, BABOK, GOST 34, IEEE 830, ISO/IEC/IEEE 29148 |

---

## Education

| Years     | Institution | Degree / Field |
| --------- | ----------- | ---------------- |
| 1995–1998 | Saint Petersburg State University, postgraduate study, Faculty of Applied Mathematics and Control Processes | Candidate of Physics & Mathematics Sciences, Mathematical Cybernetics. Thesis: "Quasi-perfect optimality principles in classical cooperative games" |
| 1990–1995 | Saint Petersburg State University, Faculty of Applied Mathematics and Control Processes | Mathematician, Applied Mathematics. Thesis: "Game theory: decision-making models in economics" |
| 1999–2002 | Saint Petersburg State University (Faculty of Economics) and International Banking Institute (IBI) | Economist, Finance & Credit. Thesis: "Applying the real options method to the valuation of long-term investment projects" |

---

## Certificates & Training

- 2026 — "Vibe-Coding Profession" course (Zerocoder University)
- 2026 — "Prompt Engineering Intensive" course (Zerocoder University)
- 2025 — "AI-Assistant Chatbot Development" course (Zerocoder University)
- 2025 — Frontend: Start (itlogia.ru)
- 2025 — ML in Financial Analysis (OTUS.ru)
- 2020 — ARIS Modeling (Luxoft Training)
- 2009 — Options School (Eltra Investment Company)
- 2005 — Finance and International Business course, Aarhus School of Business, Denmark (incl. TOEFL)
- 1995 — Annual programme in macro/microeconomics and finance, European University at St. Petersburg & EMIN

---

## Publications & Conference Papers

- **2025** — Paper at the conference "Differential Games, Control Theory and Optimisation" ([math.csu.ru](https://math.csu.ru/new_files/vestnik/DGCTO-2025.pdf))
- **2024** — Paper at the international conference "System Analysis: Modelling and Control" ([syst2024.cs.msu.ru](https://syst2024.cs.msu.ru/SYST2024-Abstracts.pdf))
- **2020** — Article "A System of Models for Building a Progressive Income Tax Scale". Vestnik SPbSU, Series 10, vol. 16, issue 1, pp. 4–18 ([dspace.spbu.ru](https://dspace.spbu.ru/bitstream/11701/17783/1/4-18.pdf))
- **2017** — Paper "On Some Properties of Superposition of Optimality Principles on the Space of TU-Games" at the international conference "Constructive Nonsmooth Analysis and Related Topics" ([ieeexplore.ieee.org](https://ieeexplore.ieee.org/document/7973949))

---

## Languages

- Russian — native
- English — Upper Intermediate (B2)


# Матвей Евгеньевич Васецов

**Системный и бизнес-аналитик · Vibe-кодер · Кандидат физико-математических наук**

[![Yahoo](https://img.shields.io/badge/Yahoo-6001D2?style=flat&logo=yahoo&logoColor=white)](mailto:matvey_v@yahoo.com) matvey_v@yahoo.com &nbsp;·&nbsp; 📱 +7 921 900-86-18 &nbsp;·&nbsp; [![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=flat&logo=telegram&logoColor=white)](https://t.me/matveivasetsov) [@matveivasetsov](https://t.me/matveivasetsov) &nbsp;·&nbsp; [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/MatveiV) [MatveiV](https://github.com/MatveiV) &nbsp;·&nbsp; [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/matvei-vasetsov-777b66a)

🇬🇧 [English version](README_EN.md)

---

> *Торговая платформа, расчётная система или AI-агент под ваш процесс: 20 лет в FinTech + Python + AI/LLM-инструменты → MVP.*

---

## Кто я

Системный/бизнес-аналитик с 20-летним опытом в FinTech. Специализируюсь на трансляции бизнес-требований в архитектурные решения и MVP, проектировании высоконагруженных систем — торговых платформ и расчётных систем. С 2024 года — практикующий AI/LLM-разработчик (vibe-coding): проектирую мультипровайдерные AI-архитектуры, RAG-пайплайны, MCP-серверы и AI-агентов, довожу их до production. Нацелен на измеримый бизнес-результат через глубокий анализ и эффективную коммуникацию между бизнесом и разработкой.

ИП зарегистрировано с апреля 2023 года; с 07.2024 — фокус на собственных AI/LLM-продуктах и проектной системной аналитике.

Закрываю связку бизнес↔разработка: собираю требования, проектирую архитектуру и автоматизирую рутину на Python — вы экономите итерации и деньги.

---

## Проекты

### AI / LLM

- **[Analyst-Architect-AI](https://github.com/MatveiV/Analyst-Architect-AI)** — AI-ассистент системного аналитика: рецензирование ТЗ с честными метками `needs_review`/`confidence`, пакетная обработка до 50 ТЗ, генерация URS/SRS/ADR по ГОСТ 34.602-2020, 8 типов диаграмм (C4/UML/ERD) с локальным рендером через Kroki, экономическая оценка (CAPEX/OPEX/ROI), RAG-база знаний с автоиндексацией, полный аудит LLM-вызовов (включая локальные Ollama/Qwen в air-gapped-режиме). **Стек:** FastAPI + SQLAlchemy (async) + SQLite/PostgreSQL, React 18 + Vite + TypeScript + Tailwind, 5 LLM-провайдеров, JWT + RBAC, 146 pytest.
- **[Agent-SystemAnalyst_MemoryFrameworks](https://github.com/MatveiV/Agent-SystemAnalyst_MemoryFrameworks)** — интерактивный агент на **LangChain + LangGraph** с поддержкой 7 AI-фреймворков (LlamaIndex, Haystack, Semantic Kernel, CrewAI, AutoGen, DSPy), каждый меняет режим работы и набор инструментов. Генерирует SRS/URS и ADR документы с рекомендациями по архитектуре и API.
- **[RAG-Agent](https://github.com/MatveiV/RAG-Agent)** — интеллектуальный помощник на **LangChain + Pinecone**: полный RAG-цикл, семантический поиск, автоматическая индексация веб-страниц, аналитика активности пользователя.
- **[FinAnalyst-Haystack-Docling-Agent](https://github.com/MatveiV/FinAnalyst-Haystack-Docling-Agent)** — модульный финансовый Telegram-бот на **Haystack 2 + Docling + Pinecone**: локальный OCR/layout через PyTorch, RAG-пайплайн, автоматическое резюме документа, инструменты Alpha Vantage, Finviz Vision, SerperDev.
- **[AI Client PDF Generator](https://github.com/MatveiV/AI_Client_PDF_Generator)** — автогенерация PDF-отчётов по транскрибациям диалогов с клиентами: LLM → структурированный JSON → Jinja2 → WeasyPrint.
- **[LangChain Pipeline Generator](https://github.com/MatveiV/LangChain_Pipeline_Generator)** — автогенерация Telegram-ботов и документации (SRS, URS) по текстовому описанию через LLM-цепочки.
- **[Prompter](https://github.com/MatveiV/Prompter)** — CLI для A/B-тестирования техник промптинга (zero-shot, few-shot, CoT, role-based) с ранжированием и генерацией Markdown/DOCX-отчётов.

### ML / Финансы

- **[TradingRobotMarketplace](https://github.com/MatveiV/TradingRobotMarketplace)** — платформа Copy Trading для торговых роботов MT4/MT5. **Бэкенд:** FastAPI + SQLAlchemy + Pydantic v2 (25+ endpoints). **Фронтенд:** React 19 + TypeScript + Vite + shadcn/ui. Трёхуровневая система комиссий, deploy pipeline, SRS v4.0 (BPMN, Sequence, C4, State).
- **[ML_Fin_Notebooks](https://github.com/MatveiV/ML_Fin_Notebooks)** — ML в финансах: бэктестинг стратегий, генерация признаков (EMA, RSI, MACD), классификация, прогнозирование временных рядов (LSTM, TFT).

### Инфраструктура и бэкенд

- **[Orders CRM](https://github.com/MatveiV/OrdersCRM)** — премиальная CRM-система для управления заявками с интеллектуальным скорингом. **Production:** orderscrm.ru. **Стек:** FastAPI + PostgreSQL 16 (asyncpg) + Nginx + Docker Compose + Watchtower. JWT-авторизация, скоринг заявок (8 критериев), поведенческие метрики, production-безопасность (rate-limit, security headers).
- **[MiniCRM](https://github.com/MatveiV/MiniCRM)** — CRM-система с двумя интерфейсами: Tkinter Desktop GUI и FastAPI REST API. SQLite, экспорт отчётов в Google Sheets, Docker-контейнеризация.
- **[Refactoring_MV](https://github.com/MatveiV/Refactoring_mv)** — рефакторинг Python-кода (устранение SQL-инъекций, утечек соединений, гонок потоков) с параллельной реализацией того же REST API на Go. Два Docker-образа на Docker Hub.
- **[Loki-Grafana](https://github.com/MatveiV/Loki_Grafana)** — стек централизованного логирования (Loki + Grafana) с Docker Compose и bash-скриптами автоустановки.
- **[CoinParser](https://github.com/MatveiV/CoinParser)** — парсер Telegram-канала с фильтрацией крипто-символов, интеграцией Google Sheets API и экспортом в XLSX.

### Боты (актуальные для целевых вакансий)

- **[MultiTools AI Agent Bot](https://github.com/MatveiV/MultiTools_AI_Agent_Bot)** — Telegram-бот с 5 AI-провайдерами, 8 ролями, генерацией изображений/видео, памятью диалога и подсчётом стоимости в рублях.
- **[Product MCP Bot](https://github.com/MatveiV/Product_MCP_Bot)** — MCP-сервер (FastAPI) + Telegram-бот с LLM tool calling. 10 инструментов: каталог товаров, калькулятор, CoinGecko, RAWG.
- **[Team Assistant Telegram Bot](https://github.com/MatveiV/Team-Assistant-Telegram-Bot)** — умный командный Telegram-бот на **Haystack 2.x + Pinecone + OpenAI**: текст, голосовые сообщения и документы, RAG-ответы по контексту переписки.

---

## Опыт работы

### 07.2024 — н.в. · ИП · Системный/бизнес-аналитик, AI/LLM-разработчик, quantitative researcher

*ИП зарегистрировано с апреля 2023 года; с 2024 года — фокус на AI/LLM-разработке.*

Проектирование мультипровайдерной AI-архитектуры, разработка FSM-конфигураторов, реализация RAG-пайплайнов, рефакторинг Python-кода, реализация REST API на Go, сборка multi-stage Docker-образов.

**Ключевые достижения:**

- Единая OpenAI-совместимая архитектура для 5 разнородных провайдеров без изменения кода бота.
- AI-агент с 11 инструментами и MCP-сервером: два независимых UI (CLI и Telegram) на едином ядре.
- Полный порт Flask-сервиса на Go: в 20 раз больше одновременных запросов при образе 10 МБ против 150 МБ.
- Analyst-Architect-AI — полноценная платформа AI-аналитика (146 автотестов, полный E2E-прогон, найдены и исправлены 2 критических бага).
- Orders CRM и TradingRobotMarketplace — доведены до production/SRS v4.0.
- Набор ML-стратегий для финансовых временных рядов с подтверждённым результатом на исторических данных.

### 04.2025 — 11.2025 · Techcoredev.ru (АО «Инновационные технологии») · Системный аналитик

**Проект:** Система управления страховыми продуктами. Полный цикл создания спецификаций, проектирование архитектурных решений (BPMN, ERD, UML, C4), реверс-инжиниринг legacy-системы с применением ИИ.

**Достижение:** ускорил этап проектирования за счёт внедрения ИИ для генерации типовых фрагментов документации и анализа legacy-кода.

*Node.js, DBeaver, MS SQL Server, Confluence, Cursor, Windsurf, Draw.io, PlantUML, Figma.*

### 04.2021 — 03.2024 · Raccoonsoft.ru & Devexperts.com · Ведущий аналитик

**Проект:** мобильная платформа Tastyworks iPad для торговли акциями, деривативами, облигациями, форекс и криптовалютами (tastytrade.com). Выявление и моделирование требований в user stories и системных спецификациях. Реверс-инжиниринг мобильного, толстого и тонкого клиентов.

**Достижение:** успешный вывод продукта на рынок; сократил количество итераций на этапе разработки благодаря детальным требованиям в Jira.

*JIRA, GitHub, Figma, Java, MindManager, Slack.*

### 12.2013 — 04.2025 · ООО «ЛАНИТ-ТЕРКОМ» · Ведущий аналитик

- **Услуги ЖКХ для ВЦКП-ЕИРЦ** (Санкт-Петербург) и **ГИС ЖКХ**. Выявление требований, реверс-инжиниринг legacy (DFD/IDEF0/BPMN/EPC/ARIS/C4). *Oracle, PostgreSQL, 1C, PowerDesigner, ARIS, Bizagi, JIRA, Confluence, Enterprise Architect.*
- **МЭШ для ДИТ г. Москвы** (управление олимпиадами школьников). Анализ БФТ, ТЗ/ЧТЗ/ППИ, UML Sequence-диаграммы. *PostgreSQL, Java, Kafka, JIRA, Confluence, Grafana, Postman.*
- **ВЕГА ФЭМ и «Цифровой двойник сейсморазведки»** для ПАО «Газпром нефть». *ARIS, MSSQL Server, 1С.*
- **Раковый регистр** в ЕМИАС для ДИТ г. Москвы.
- **Toyota** (ООО «Тойота Мотор Россия») — Vision и ТЗ для складской подсистемы и подсистемы контроля качества.
- **AREA9** для Area9 Lyceum — адаптация SaaS-платформы адаптивного обучения, локализация UI и контента.
- **Presale-оценки:** ETWeb Enterprise, ГИС ТЭК СПб, ИС для Росатом, ИС «Управление трафиком» (YOTA), ИС «Запасы» (Роснедра) и др.

### 05.2013 — 12.2013 · Deutsche Telekom IT Solutions · Старший бизнес-аналитик

**Проект:** De-mail — нотариальный E-mail. Анализ функциональных требований, описания бизнес-процессов, спецификаций и диаграмм (DFD, ERM, BPMN, UML).

*Polarion, JIRA, Confluence, Enterprise Architect, MindManager.*

### 05.2012 — 03.2013 · TKB BNP Paribas Investment Partners · Старший аналитик бизнес-процессов

**Проекты:** Model portfolio, структурированные продукты, Value-at-risk, CAPM, ATP, МТС-ATS-Robot, Data Quality, Data mining.

*Excel, yEd, QUIK, MetaTrader 4/5 (+MQL), 1C, MS SQL.*

### 08.2007 — 05.2012 · Devexperts.com · Бизнес/системный/финансовый аналитик

**Проекты:** АТС, FX и бинарные опционы, технический анализ, дилинг, мобильные клиенты, интеграция по FIX, риск-менеджмент, бэк-офис. Платформы: ThinkOrSwim, GFT Dealbook 360, DXtrade.

*DOORS, Polarion, JIRA, Confluence, Enterprise Architect, FIX протокол.*

### 02.2006 — 08.2007 · Visual Trading Systems LLC · Бизнес-аналитик

**Проект:** модули АТС и Backtesting Engine для торговой платформы VT Trader (Capital Market Services FX).

*VT Trader, MetaTrader (+MQL), MetaStock, Tradestation, Wealth-Lab.*

---

## Технологии

| Категория           | Стек |
| ------------------- | ---- |
| Языки               | Python 3.10+, Go 1.22, TypeScript, SQL, Java, Bash, MQL, TeX |
| AI / LLM            | OpenAI API, Claude, Gemini, DeepSeek, GLM, Llama, Qwen, Kimi; function/tool calling; MCP; промпт-инжиниринг; RAG; FAISS, sentence-transformers |
| Фреймворки / UI     | FastAPI, Flask, React 18/19, Vite, Tailwind CSS, aiogram 3, LangChain, Haystack 2, openai SDK, ChromaDB, Pinecone, SQLAlchemy (async), Alembic, pytest, Nginx |
| Данные / API        | SQLite, PostgreSQL, Oracle, MS SQL Server, 1С, pandas, Google Sheets API, Google Drive API |
| ML                  | scikit-learn, LightGBM, PyTorch, PyTorch Lightning, optuna, backtesting |
| Инфраструктура      | Docker, Docker Compose, Grafana Loki, GitHub Actions |
| BA / SA инструменты | Confluence, JIRA, Redmine, Polarion, DOORS, ARIS, Bizagi, Enterprise Architect, PlantUML, Draw.io, Miro, Figma, Visio, PowerDesigner, DBeaver, Postman, Mermaid (C4, BPMN, UML), Kroki |
| Торговые платформы  | Tastytrade, MetaTrader 4/5, DealBook 360, ThinkOrSwim, VT Trader, QUIK, Tradingview |
| Стандарты           | PMBoK, BABOK, ГОСТ 34, IEEE 830, ISO/IEC/IEEE 29148 |

---

## Образование

| Годы      | Учебное заведение | Степень / специальность |
| --------- | ------------------ | ------------------------ |
| 1995–1998 | СПбГУ, аспирантура, факультет прикладной математики и процессов управления | К.ф.-м.н., Математическая кибернетика. Тема: «Квазисовершенные принципы оптимальности в классических кооперативных играх» |
| 1990–1995 | СПбГУ, факультет прикладной математики и процессов управления | Математик, Прикладная математика. Тема: «Теории игр: модели принятия решений в экономике» |
| 1999–2002 | СПбГУ (экономический факультет) и Международный банковский институт (IBI) | Экономист, Финансы и кредит. Тема: «Применение метода реальных опционов для оценки долгосрочных инвестиционных проектов» |

---

## Сертификаты и обучение

- 2026 — Курс «Профессия вайб-кодер» (Университет Зерокодер)
- 2026 — Курс «Интенсив по промпт-инжинирингу» (Университет Зерокодер)
- 2025 — Курс «Разработка чат-бота с AI-ассистентом» (Университет Зерокодер)
- 2025 — Frontend: Start (itlogia.ru)
- 2025 — ML в финансовом анализе (OTUS.ru)
- 2020 — Моделирование в ARIS (Luxoft-training)
- 2009 — Школа опционов (инвестиционная компания Eltra)
- 2005 — Курс финансов и международного бизнеса, Aarhus School of Business, Дания (включая TOEFL)
- 1995 — Годичная программа по макро- и микроэкономике и финансам, Европейский университет в СПб и ЭМИАН

---

## Научные публикации и доклады

- **2025** — Доклад на конференции «Дифференциальные игры, теория управления и оптимизация» ([math.csu.ru](https://math.csu.ru/new_files/vestnik/DGCTO-2025.pdf))
- **2024** — Доклад на международной конференции «Системный анализ: моделирование и управление» ([syst2024.cs.msu.ru](https://syst2024.cs.msu.ru/SYST2024-Abstracts.pdf))
- **2020** — Статья «Система моделей построения прогрессивной шкалы подоходного налога». Вестник СПбГУ, серия 10, т. 16, вып. 1, стр. 4–18 ([dspace.spbu.ru](https://dspace.spbu.ru/bitstream/11701/17783/1/4-18.pdf))
- **2017** — Доклад «On Some Properties of Superposition of Optimality Principles on the Space of TU-Games» на конференции «Конструктивный негладкий анализ и смежные вопросы» ([ieeexplore.ieee.org](https://ieeexplore.ieee.org/document/7973949))

---

## Языки

- Русский — родной
- Английский — Upper Intermediate (B2)


# Hi there, I'm Martin! 👋

## 🚀 About Me

I build backend systems, ML pipelines, and AI workflows with Python and Django — and I bring 20 years of real business context to every line of code.

After completing the Fullstack Developer Bootcamp at Developer Akademie (January 2025 – March 2026), I've been focused on production-grade systems: GlobalMarketMood processes tens of thousands of news articles daily across 28 global regions using NLP and sentiment analysis. StockPredict V2 is an LSTM + XGBoost ensemble achieving 66% hit rate on 12 US bank stocks — live since early 2026. And a multi-layer SAP Fraud Detection Pipeline built with n8n, Isolation Forest, and Claude AI.

My background in business administration and entrepreneurship means I don't just build features — I understand why they matter.

**🎯 Open to:** Junior Backend / ML / AI Workflow roles · Python focus · Munich or remote Germany

**📍 Location:** Rosenheim/Munich, Bavaria, Germany

---

## 🛠️ Tech Stack

### Core — täglich im Einsatz

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)

### Machine Learning

![LSTM](https://img.shields.io/badge/LSTM-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=for-the-badge&logo=xgboost&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![NLP](https://img.shields.io/badge/NLP%20%2F%20VADER-4B8BBE?style=for-the-badge&logo=python&logoColor=white)
![Isolation Forest](https://img.shields.io/badge/Isolation_Forest-FF6F00?style=for-the-badge&logo=scikit-learn&logoColor=white)

### AI / LLM Integration

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-F6C915?style=for-the-badge&logo=databricks&logoColor=black)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![RAG](https://img.shields.io/badge/RAG_Pipelines-7C3AED?style=for-the-badge&logo=openai&logoColor=white)
![Claude AI](https://img.shields.io/badge/Claude_AI-D97706?style=for-the-badge&logo=anthropic&logoColor=white)

### Workflow Automation

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![SAP OData](https://img.shields.io/badge/SAP_OData-0FAAFF?style=for-the-badge&logo=sap&logoColor=white)
![APScheduler](https://img.shields.io/badge/APScheduler-4B8BBE?style=for-the-badge&logo=python&logoColor=white)

### Frontend — solide Grundlagen

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![HTMX](https://img.shields.io/badge/HTMX-3366CC?style=for-the-badge&logo=htmx&logoColor=white)

### Deployment & Tools

![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![UptimeRobot](https://img.shields.io/badge/UptimeRobot-3BD671?style=for-the-badge&logo=uptimerobot&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

---

## 🎯 Featured Projects

### 🔍 [SAP × n8n × AI — Fraud Detection Pipeline](https://github.com/Martin-Frei/sap_n8n_demo)
**Two automated AI pipelines** | SAP OData · n8n · Isolation Forest · Claude AI
`n8n` `Python` `Flask` `Isolation Forest` `Claude AI` `SAP OData API` `Supabase` `SMTP`

No demos — production-grade architecture with real SAP Sandbox data.

**Pipeline 1 — Sales Order Anomaly Detection:**
- 12.000 SAP Sales Orders loaded via manual pagination ($top=500/$skip)
- Isolation Forest (scikit-learn) as ML pre-filter: contamination=5%, 100 trees, joblib-persisted model
- Flask Prediction Server (/health, /predict, /retrain) — n8n calls via HTTP Request
- Claude AI explains every anomaly in plain language — 1 API call for all outliers → 95% cost reduction vs. N individual calls
- Automated HTML email digest with risk distribution (KRITISCH/VERDÄCHTIG/PRÜFEN) and Top-5 anomaly days from Supabase history

**Pipeline 2 — Email Verification (5-Layer Defense in Depth):**
- Layer 1: DNS MX Check
- Layer 2: SMTP Handshake
- Layer 3: Entropy Check (mathematics, no training needed)
- Layer 4: Isolation Forest (trained on 1.000 synthetic emails, 18 cultural backgrounds)
- Layer 5: Claude AI (context + explanation for borderline cases)
- **88% accuracy** — no single layer is perfect; together they mirror real AML detection systems

**🚀 [GitHub Repo](https://github.com/Martin-Frei/sap_n8n_demo)**

---

### 🌍 [GlobalMarketMood — NLP News Intelligence](https://www.houseofstocks.dev)
**Production NLP Pipeline** | Sentiment analysis across 28 global regions
`Python` `Django` `VADER` `NLP` `DeepSeek` `Supabase` `Railway` `APScheduler` `REST API`

Processing tens of thousands of news articles daily from 160+ RSS feeds across 28 global regions — built in a single weekend (Feb 2026), running in production ever since. Sentiment scoring and topic classification (6 categories) power a live market mood dashboard updated every 3 hours.

**🔒 Private Repository (Request Access)** | **🚀 [Live Demo](https://www.houseofstocks.dev)** | **Key Features:**
- Automated NLP pipeline processing 160+ RSS feeds
- VADER sentiment analysis + DeepSeek topic classification
- 28 global regions, 6 topic categories
- APScheduler-driven, runs every 3 hours on Railway
- Live dashboard with global mood scoring

---

### 📈 [StockPredict V2 — ML Trading Signal System](https://www.martin-freimuth.dev)
**LSTM + XGBoost Ensemble** | 12 US bank stocks · Live since 2026
`Python` `LSTM` `XGBoost` `scikit-learn` `Supabase` `Railway` `Pandas` `NumPy`

Ensemble ML system predicting daily price direction for 12 US bank stocks. Trained on 20 years of historical data — proprietary HG Indicator applied as Layer 2 signal filter, lifting hit rate to 66% across 1,551 backtested trades. Automated via daily Railway cronjob (Mon–Fri, 00:00 UTC). Paper trading live at CapTrader since March 9, 2026.

**🔒 Private Repository (Request Access)** | **🚀 [Live Dashboard](https://www.martin-freimuth.dev)** | **Key Features:**
- LSTM + XGBoost ensemble with proprietary HG Indicator
- Trained on 20 years of historical data
- 1,551 backtested trades, 66% hit rate, €72,543 simulated PnL
- Daily automated cronjob on Railway
- Paper trading validation via CapTrader since March 9, 2026
- Performance dashboard live on portfolio site

---

### 🤖 SUSI — Personal AI Assistant *(Active Development)*
**Local RAG System** | LangChain · Ollama · ChromaDB · Django
`Python` `Django` `LangChain` `ChromaDB` `Ollama` `RAG` `nomic-embed-text` `qwen2.5-coder:7b`

A fully local AI assistant built from scratch — no external API costs, no data leaving the machine. Currently running on a Ryzen 9 5900X + RTX 4070. Actively benchmarking chunk sizes, embedding models, and local LLMs for optimal RAG performance. Long-term goal: replace DeepSeek API costs for GlobalMarketMood topic classification entirely.

**🔒 Private Repository (Active Development)** | **Key Features:**
- Local RAG pipeline — LangChain + ChromaDB + nomic-embed-text embeddings
- 214+ chunks across 41 markdown files (SUSIpedia knowledge base)
- Ollama-powered inference (qwen2.5-coder:7b), fully offline
- Django backend with TOPIC_KEYWORDS routing
- Active benchmarking: chunk sizes, embedding models, local LLMs

**🗺️ Roadmap:**
- Fine-tuning on domain-specific manuals and project documentation
- Hardware upgrade to RTX 3090 for larger model support (32B–70B)
- Replace DeepSeek API for GMM topic classification — 24/7 local inference

---

### 🌐 [martin-freimuth.dev — Production Django Platform](https://www.martin-freimuth.dev)
**Multi-App Django Platform** | 7 Apps · Custom Security · Multi-Tier Auth · Full Deployment Stack
`Python` `Django 5.1` `PostgreSQL` `HTMX` `Tailwind CSS` `Cloudinary` `Whitenoise` `Resend API` `Google Gemini` `Gunicorn` `Railway`

This is not a portfolio page — it's a production-grade Django platform built from scratch with 2,500+ lines of code across 7 integrated apps. Every architectural decision was made deliberately: no Google reCAPTCHA (privacy), no SMTP (reliability), no SDK bloat (performance).

**The centerpiece is a custom Icon-Challenge bot protection system** — a privacy-first reCAPTCHA alternative built entirely in-house. A 3×3 grid of randomly selected icons (40-icon pool) presents a count-challenge that rotates on every failed attempt, preventing pattern learning. The same engine serves three distinct use-cases (Guest login, Contact form, Signup) with context-specific rate limiting — a single DRY implementation driving completely different security behaviors.

**Authentication runs on three tiers:** Guests get 2-minute access after passing the Icon-Challenge — auto-logout is handled by a Django Context Processor that runs on every request, requiring no cronjob, no Celery, no polling. Registered users get full 24-hour sessions with email verification via Django-Allauth and a custom Resend API email backend (~300ms delivery vs. 800ms+ SMTP). Admins have unrestricted access with full login logging and 90-day auto-cleanup for DSGVO compliance.

**Bot defense runs four layers deep:** Honeypot fields catch simple bots instantly. The Icon-Challenge creates a 20% per-attempt success ceiling for anything automated. Progressive rate limiting escalates from 30s to 60s lockouts with a silent reset that resets to 1 (not 0) for UX reasons. Email verification blocks fake account creation entirely.

**The deployment stack was built the hard way** — solving Railway's ephemeral filesystem problem with Cloudinary for media storage, Whitenoise for static files without Nginx, and dj-database-url for seamless SQLite→PostgreSQL switching between local and production. HTTPS via Let's Encrypt auto-cert, Cloudflare CDN, UptimeRobot monitoring to prevent cold starts.

**Integrated apps running in production:**
- `bmi_app` — Gemini AI health coach via direct REST calls (no SDK, lightweight)
- `rps_app` — Rock Paper Scissors in Django (session-based scoring) alongside the React version — a deliberate framework comparison
- `projects` — Dual-mode portfolio CMS (Public vs. Secret Lab with invited-user access)
- `icon_challenge` — Reusable bot protection engine
- `accounts` — Custom auth with Guest system, LoginLog, and management commands
- `core` — Landing page, contact form (Resend API), About pages
- `legal` — Impressum + Datenschutz (DDG/MStV compliant)

**🚀 [Live](https://www.martin-freimuth.dev)** | **[GitHub](https://github.com/Martin-Frei/portfolio_site)**

---

### 🏥 [Diabetes Prediction — ML Classification](https://github.com/Martin-Frei/diabetes-prediction)
**XGBoost + SMOTE** | Handling imbalanced medical data
`Python` `XGBoost` `SMOTE` `scikit-learn` `Pandas` `Seaborn`

Classification model for diabetes prediction using XGBoost with SMOTE to handle heavily imbalanced medical data. Focus on medical-grade metrics — sensitivity over raw accuracy, with threshold optimization pushing from default 0.5 to 0.272.

**📊 [View Notebook](https://github.com/Martin-Frei/diabetes-prediction/blob/master/XGBoost_SMOTE_Diabeties.ipynb)** | **Key Features:**
- 83.3% ROC-AUC score
- SMOTE for class imbalance handling
- Threshold optimization (0.272 vs. 0.5 default)
- Medical-focused metrics — Sensitivity & Specificity
- Feature importance analysis

---

### 🤖 [Gemini BMI Coach — AI Health Assistant](https://www.martin-freimuth.dev)
**Fullstack AI Application** | Django · HTMX · Google Gemini API
`Python` `Django` `Google Gemini 1.5 Flash` `HTMX` `Tailwind CSS` `Railway`

A health assistant that goes beyond a simple BMI calculator — integrating Google Gemini 1.5 Flash to deliver personalized, AI-generated nutrition and exercise recommendations based on user data. Seamless UX via HTMX without page reloads.

**🚀 [Live Demo](https://www.martin-freimuth.dev)** | **Key Features:**
- Google Gemini 1.5 Flash API integration with prompt engineering
- Dynamic UI via HTMX — no page reloads
- Secure API key management via environment variables
- Django authentication + Railway deployment

---

### 🧩 [Join — Collaborative Kanban Board](https://martin-frei.github.io/join/)
**Team Project** | JavaScript · Firebase · Responsive Design
`JavaScript` `HTML5` `CSS3` `Firebase` `Responsive Design`

Kanban-style project management tool built as a team project — drag & drop, real-time Firebase sync, and full contact management. I developed the complete Contacts Module including Firebase integration, form validation, and all UI components.

**🚀 [Live Demo](https://martin-frei.github.io/join/)** | **Key Features:**
- Drag & drop task organization
- Firebase real-time sync
- Contact management system (my module)
- Responsive mobile-first design

---

### 🎮 Further Projects — Frontend & JavaScript
`JavaScript` `React` `HTML5` `CSS3` `REST API` `Tailwind CSS`

A collection of frontend projects built during the bootcamp demonstrating JavaScript fundamentals, React Hooks, and API integration.

- **[Pokédex](https://martin-frei.github.io/pokedex/)** — PokeAPI integration, search & filter, type-based color schemes
- **[React Pexels Gallery](https://martin-frei.github.io/react-pexels-gallery)** — Image search via Pexels API, React Hooks, Tailwind CSS
- **[Training Timer PWA](https://martin-frei.github.io/training-timer/)** — Offline-capable Progressive Web App, customizable intervals
- **[Rock Paper Scissors — React](https://martin-frei.github.io/React-RSPGame)** — Best-of-5 game logic, state management, React Hooks
- **Rock Paper Scissors — Django** — Same logic, server-side rendering, deliberate framework comparison *(live, not publicly linked)*

---

## 🎓 Education & Background

**Developer Akademie** — Fullstack Web Development Bootcamp
*January 2025 – March 2026*
Python · Django · JavaScript · React · Angular · Machine Learning

**Preply — Intensive 1-on-1 Tech Training**
*April 2024 – present*
Up to 20 hours per week of individual tutoring with up to 7 international instructors simultaneously — a self-directed, self-funded curriculum progressing from web fundamentals (HTML, JavaScript, TypeScript, React) through backend development (Python, Django) into machine learning and AI. Deliberately dropped Java after 3 months to stay focused on the Python/ML path.

**Betriebswirt VWA** — Business Administration
*VWA University of Cooperative Education*
Foundation in controlling, finance, and business strategy — applied across 20+ years of entrepreneurship.

---

## 💼 Career Background

**Holnburger GmbH** — Metzgermeister & Procurement
*April 2018 – April 2026*
Responsible for procurement with an annual purchasing volume of €6–9M using CSB ERP. Deep exposure to supply chain, inventory management, and operational business cases — the kind of domain knowledge that makes ML applications in logistics and FinTech immediately tangible.

**Eigenes Unternehmen — Taxi & Patiententransporte**
*2004 – 2018*
Built and operated a transport company from scratch — starting with standard taxi operations, then pivoting to wheelchair and recumbent patient transport (Liegendtransporte) for nearly a decade. Managed operations, logistics, and staff independently.

**German Navy — Marineinfanterie & Minentaucher**
*1993 – 1997*
Specialized training in precision work, high-pressure decision-making, and systematic problem-solving under stress. Skills that transfer directly to debugging production systems at 2am. 😄

---

## 💡 Why This Combination Works

Most developers bring technical skills. Most business people bring domain knowledge. Very few bring both — and even fewer have built and operated real businesses before writing their first line of code.

My path wasn't a career change out of frustration. It was a deliberate pivot after 20+ years of watching businesses struggle with data they couldn't read, processes they couldn't automate, and decisions they made on gut feeling instead of numbers. I decided to become the person who builds the tools that fix that.

The combination is unusual by design:

A former mine diver who learned to make high-stakes decisions under pressure. An entrepreneur who built a patient transport company from scratch and scaled it over 14 years. A Metzgermeister who managed €6–9M in annual procurement, ran ERP systems, and understood supply chains from the inside. And now a developer who builds ML pipelines that process tens of thousands of news articles daily and predict stock movements with 66% accuracy.

I don't just write code — I understand what the code is supposed to solve. That perspective is rare at junior level, and it's not something that comes from a bootcamp. It comes from years of making real decisions with real consequences.

**The businesses I understand best:** FinTech · Logistics · Supply Chain · Healthcare

---

## 🌱 Currently Learning — Going Deeper

The bootcamp gave me the foundation. What I'm building now is the depth.

**Machine Learning Mathematics**
Working through the underlying math of ML systematically — linear algebra with 3Blue1Brown's Essence of Linear Algebra series, building structured notes for long-term retention. The goal isn't just to use ML libraries — it's to understand why they work and when they break.

**LLMs & SUSI Development**
Weekly 1-on-1 sessions with a specialized tutor focused on LLM architecture, RAG optimization, and local model deployment. SUSI is the live sandbox — every concept gets tested in production immediately.

**JavaScript & React — Going Deeper**
Revisiting JS and React beyond bootcamp level — closures, event loop, React internals, custom hooks. The kind of depth that shows up when things go wrong in production.

**MySQL**
Structured deep-dive into relational database design, complex JOINs, query optimization, and indexing strategies — complementing the PostgreSQL work already in production across GMM and SPV2.

---

## 📫 Let's Connect!

- 💼 **LinkedIn:** [martin-freimuth](https://www.linkedin.com/in/martin-freimuth-089249359/)
- 📧 **Email:** martin@houseofstocks.dev
- 📍 **Location:** Rosenheim/Munich Region, Germany
- 🌐 **Portfolio:** [martin-freimuth.dev](https://www.martin-freimuth.dev)
- ☕ **Coffee?** Always up for a technical conversation!

---

## 💡 Fun Facts

- 💃 Dancer with an ever-growing dance harem — 16 different styles including Standard/Latin, DiscoFox, Kizomba, Bachata, and Salsa. Yes, the harem is real.
- 🎧 DJ with a DiscoFox focus — because someone has to keep the floor moving
- 🖥️ Currently assembling a dedicated ML workstation (RTX 3090, custom water-cooling) — autumn 2026 brings the full AM5 rebuild with a second GPU. Both water-cooled, obviously.
- ⚓ Former German Navy mine diver — precision work under pressure, transferable skills guaranteed
- 🥩 Metzgermeister turned ML Developer — probably the only one in Bavaria
- ☕ Always up for a technical conversation — over coffee, on a dance floor, or in a Zoom call

---

<div align="center">

**⭐ Open to collaboration on interesting projects! ⭐**

*"From mine diver to Metzgermeister to ML Developer — combining 20 years of real-world experience with modern machine learning."*

</div>

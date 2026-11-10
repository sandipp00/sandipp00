<h1 align="center">Hi, I'm Sandip Pradhan 👋</h1>

<p align="center">
  <b>AI/ML Engineer</b> · Generative AI · Agentic Systems · Python<br>
  📍 Bengaluru, India
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/sandippradhan0/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://leetcode.com/u/sandippradhan870/"><img src="https://img.shields.io/badge/LeetCode-Profile-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"></a>
  <a href="https://github.com/sandipp00?tab=repositories"><img src="https://img.shields.io/badge/GitHub-Repositories-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
</p>

I build practical machine learning systems and LLM-powered applications: research agents that plan and call tools, document pipelines that extract and cite, and analytics products with real APIs and tests behind them.

- 🤖 **Agents & GenAI:** LangGraph, RAG, multi-agent orchestration, function calling, streaming UIs
- 🧪 **Engineering:** FastAPI backends, evaluation harnesses, pytest, CI, Docker
- 📊 **Data:** SQL, Pandas, Scikit-learn, Power BI, Streamlit

---

## 🚀 Featured Projects

### 🔭 Lumen — Autonomous Deep Research Agent
`Python` `LangGraph` `Deep Agents` `FastAPI` `React` `PostgreSQL` `Redis`

An autonomous research agent that plans, calls tools, cross-checks sources, and streams back cited answers as rich UI blocks (markdown, tables, maps, insight cards).

- ReAct loop on LangGraph with 8 tools: web search, page reader, Wikipedia, nearby places, news, stocks, forex, crypto
- Redis tool caching, SSRF-safe page fetching, request limits, and per-request observability metrics
- Benchmarked on 28 live queries: 28/28 answered, 8.6 s p50 latency, ~$0.0007 per query, correct tool chosen 25/25 times

**[→ deep-research-platform](https://github.com/sandipp00/deep-research-platform)**

### 📈 AI Data Analyst Agent
`Python` `LangGraph` `PostgreSQL` `sqlglot` `Plotly` `Streamlit` `Gemini`

Ask a question in plain English and get the SQL, a Plotly chart, and a written explanation.

- Graph pipeline: load schema → generate SQL → validate → execute → explain, with automatic repair of failed queries
- Layered safety: sqlglot validator (SELECT-only, no DML/DDL), read-only transaction, statement timeout, read-only Postgres role
- Model fallback across Gemini models on quota or overload errors, with cooldowns for failing models

**[→ ai-data-analyst-agent](https://github.com/sandipp00/ai-data-analyst-agent)**

### ✈️ Multi-Agent Travel Planner
`Python` `Groq` `Function Calling` `Multi-Agent Systems` `Public APIs`

A trip-planning assistant where an orchestrator delegates to five specialist agents and synthesizes a full itinerary and budget.

- Specialists for flights, hotels, activities, destination info, and budget analysis, run in parallel
- Grounded in real data: OpenStreetMap, Open-Meteo, Wikidata, Wikivoyage, and live exchange rates
- Budget checks use exact arithmetic instead of LLM estimates; the agent loop is capped so it cannot run forever

**[→ multi-agent-travel-planner](https://github.com/sandipp00/multi-agent-travel-planner)**

### 📄 DocIntel — Document Intelligence with OCR
`Python` `FastAPI` `Tesseract` `spaCy` `FAISS` `Scikit-learn` `Gemini/Groq`

Upload invoices, resumes, contracts, or reports; DocIntel classifies them, extracts key fields, summarizes, and answers questions with citations.

- OCR fallback for scanned PDFs and images; TF-IDF + logistic regression document classifier
- Rule-based and LLM field extraction compared field by field; refuses answers not supported by the cited text
- Prompt-injection filtering, per-session isolation, no uploads kept on disk; works without an LLM key

**[→ docintel](https://github.com/sandipp00/docintel)**

### 🔍 AI Document Intelligence (RAG)
`Python` `FastAPI` `RAG` `OpenAI API` `Qdrant` `Streamlit` `Docker`

A document question-answering system that retrieves relevant passages and generates evidence-grounded answers with source citations.

- PDF, DOCX, TXT, and Markdown ingestion with chunking, embeddings, and vector retrieval
- Source-aware answers and explicit insufficient-evidence handling
- Automated tests and GitHub Actions CI

**[→ ai-document-intelligence](https://github.com/sandipp00/ai-document-intelligence)**

### 🎬 AI-Powered Recommendation System
`Python` `Scikit-learn` `Sentence Transformers` `FastAPI` `Hugging Face`

A movie recommender combining lexical retrieval, semantic similarity, hybrid ranking, and LLM-generated explanations.

- Blends TF-IDF and semantic embedding signals with configurable hybrid ranking
- Explanations are grounded in the retrieved candidates, not free-form
- Automated tests and CI

**[→ ai-recommendation-system](https://github.com/sandipp00/ai-recommendation-system)**

### 💳 Credit Card Fraud Detection
`Python` `Scikit-learn` `FastAPI` `pytest`

An ML pipeline for flagging fraudulent transactions in a heavily imbalanced dataset.

- Compares Logistic Regression and Random Forest; selects on PR-AUC
- Evaluated with PR-AUC, ROC-AUC, and full classification metrics
- Predictions served through a FastAPI endpoint

**[→ credit-card-fraud-detection](https://github.com/sandipp00/credit-card-fraud-detection)**

### 🏃 Kinetiq — AI Fitness Platform
`Python` `FastAPI` `Flutter` `RAG` `PostgreSQL`

A mobile-first fitness platform: Flutter app plus FastAPI backend, at release-candidate stage for Android.

- Health Connect / HealthKit sync, recovery and sleep scores, trend analytics
- Adaptive workout planning, RAG-grounded AI coaching, ML personalization
- Secure auth with refresh tokens, account export and deletion, CI that builds a release APK

**[→ fitness-ai-platform](https://github.com/sandipp00/fitness-ai-platform)**

### 💹 FinPulse — Financial Analytics Platform
`Python` `Pandas` `NumPy` `FastAPI` `React` `SQLite` `Recharts`

Explore stock and crypto market data and evaluate historical performance and risk.

- Ingests historical data for equities, Bitcoin, Ethereum, and NIFTY 50
- Returns, cumulative growth, annualized volatility, Sharpe ratio, and maximum drawdown
- Python analytics layer, FastAPI backend, React interface, automated tests

**[→ FinPulse](https://github.com/sandipp00/FinPulse)**

Also in progress: **[btc-algo-platform](https://github.com/sandipp00/btc-algo-platform)**, a BTC/USDT algorithmic trading platform with backtesting, risk management, and paper trading.

---

## 📊 Data Analytics Projects

| Project | Stack | Focus |
|---|---|---|
| [Banking Credit Risk Analytics](https://github.com/sandipp00/banking-credit-risk-analytics) | Python · PostgreSQL · SQL · Power BI | Default and delinquency rates, credit-risk exposure |
| [Walmart Retail Sales Analytics](https://github.com/sandipp00/Walmart-Retail-Sales-Analytics) | Python · SQL · Power BI · ML | Store sales analysis and demand forecasting |
| [Online Advertising Optimization](https://github.com/sandipp00/online-advertising-performance-optimization) | Python · ML | Ad spend and sales optimization |
| [Netflix Content Analytics](https://github.com/sandipp00/netflix-content-analytics) | Python · SQLite · Streamlit | Catalog EDA and interactive dashboard |
| [HR Analytics Dashboard](https://github.com/sandipp00/hr-analytics-dashboard) | SQL · Python · Power BI | Employee attrition analysis |
| [Superstore Sales Dashboard](https://github.com/sandipp00/Superstore_Sales_Dashboard) | Power BI · DAX | Sales, profit, and regional performance |
| [Social Media Campaign Tracker](https://github.com/sandipp00/Social_Media_Campaign_Performance_Tracker) | Power BI | Ad spend vs. campaign performance across platforms |
| [Student Feedback Analysis](https://github.com/sandipp00/Student_Feedback_Analysis) | Python · NLP · TextBlob/VADER | Sentiment and satisfaction analysis of event feedback |

---

## 🛠️ Technical Skills

| Area | Tools |
|---|---|
| **Languages & Data** | Python, SQL, Pandas, NumPy |
| **Machine Learning** | Scikit-learn, classification, feature engineering, model evaluation, recommendation systems, time-series forecasting |
| **Generative AI & Agents** | LangChain, LangGraph, Deep Agents, RAG, embeddings, semantic retrieval, function calling, multi-agent orchestration |
| **Document AI & NLP** | Tesseract, PyMuPDF, spaCy, FAISS, Sentence Transformers |
| **Backend & Storage** | FastAPI, REST, SSE streaming, PostgreSQL, SQLite, Redis, Qdrant |
| **Frontend & Mobile** | React, Flutter, Streamlit |
| **Analytics & BI** | Power BI, Tableau, Excel, Plotly |
| **Engineering** | Git, GitHub Actions, pytest, Docker, Jupyter |

## 📚 Currently Exploring

- RAG and agent evaluation: retrieval quality, tool-choice accuracy, cost and latency benchmarks
- Long-running agent workflows: planning, memory, and recovery from failed steps
- MLOps and production deployment practices

---

## 📈 GitHub Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sandipp00&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats" height="165">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sandipp00&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="165">
</p>

---

<p align="center"><i>Building practical AI systems through data, machine learning, and software engineering.</i> 🚀</p>

# Hi, I'm Sandip Pradhan 👋

### Aspiring AI/ML Engineer | Machine Learning | Generative AI | Agentic AI | Python

I'm focused on building practical machine learning systems, LLM-powered applications, AI agents, and data-driven solutions.

- 🔭 Building end-to-end AI/ML projects and intelligent applications
- 🤖 Exploring RAG, LLMs, multi-agent systems, semantic search, and recommendation systems
- 🧪 Interested in model evaluation, API development, testing, and deployment
- 📍 Bengaluru, India

## 🛠️ Technical Skills

**Programming & Data:** Python, SQL, Pandas, NumPy

**Machine Learning:** Scikit-learn, classification, feature engineering, model evaluation, recommendation systems, time-series forecasting

**Document AI & NLP:** OCR (Tesseract, PyMuPDF), spaCy, FAISS, Sentence Transformers

**Generative AI & Agents:** LLM applications, RAG, embeddings, semantic retrieval, LangChain, LangGraph, Deep Agents, multi-agent orchestration, function calling

**Backend & Data Storage:** FastAPI, REST APIs, SSE streaming, PostgreSQL, SQLite, Redis, Qdrant, React

**Analytics & Visualization:** Power BI, Tableau, Excel, Plotly, Streamlit

**Tools & Engineering:** Git, GitHub Actions, pytest, Docker, Jupyter Notebook

## 🚀 Featured Projects

### 1. Lumen — Autonomous Deep Research Agent
**Python · LangGraph · Deep Agents · FastAPI · React · PostgreSQL · Redis**

An autonomous research agent that plans, calls tools, cross-checks sources, and streams back cited answers as rich UI blocks (markdown, tables, maps, insight cards).

- ReAct agent loop on LangGraph with 8 tools: web search, page reader, Wikipedia, nearby places, news, stocks, forex, and crypto
- Redis tool caching, SSRF-safe page fetching, request limits, and per-request observability metrics
- Benchmarked on 28 live queries: 28/28 answered, 8.6 s p50 latency, ~$0.0007 per query, and the right tool chosen 25/25 times

[View Repository](https://github.com/sandipp00/deep-research-platform)

### 2. Multi-Agent Travel Planner
**Python · Groq · Function Calling · Multi-Agent Systems · Free Public APIs**

A trip-planning assistant where an orchestrator agent delegates to five specialist agents and synthesizes a full itinerary and budget.

- Specialists for flights (Google Flights), hotels, activities, destination info, and budget analysis, run in parallel
- Grounds destination info in real data: OpenStreetMap, Open-Meteo, Wikidata, Wikivoyage, and live exchange rates
- Budget checks use exact arithmetic instead of LLM estimates, and the agent loop is capped so it can't run forever

[View Repository](https://github.com/sandipp00/multi-agent-travel-planner)

### 3. DocIntel — Document Intelligence with OCR
**Python · FastAPI · Tesseract OCR · spaCy · FAISS · Scikit-learn · Gemini/Groq**

Upload invoices, resumes, contracts, or reports, and DocIntel classifies them, extracts key fields, summarizes them, and answers questions with citations.

- OCR fallback for scanned PDFs and images; TF-IDF + logistic regression document classifier
- Rule-based + LLM field extraction compared field by field; refuses answers not supported by the cited text
- Prompt-injection filtering, per-session isolation, and no uploads kept on disk; works without an LLM key

[View Repository](https://github.com/sandipp00/docintel)

### 4. AI Document Intelligence
**Python · FastAPI · RAG · OpenAI API · Qdrant · Streamlit · Docker**

A document question-answering system that retrieves relevant document passages and generates evidence-grounded answers with source citations.

- Supports PDF, DOCX, TXT, and Markdown ingestion
- Implements document chunking, embeddings, and vector retrieval
- Provides source-aware answers and insufficient-evidence handling
- Includes automated tests and GitHub Actions CI

[View Repository](https://github.com/sandipp00/ai-document-intelligence)

### 5. AI-Powered Recommendation System
**Python · Scikit-learn · Sentence Transformers · FastAPI · Hugging Face**

A personalized movie recommendation system combining lexical retrieval, semantic similarity, hybrid ranking, and LLM-generated explanations.

- Combines TF-IDF and semantic embedding signals
- Uses configurable hybrid ranking
- Grounds generated explanations in retrieved movie candidates
- Includes automated tests and CI

[View Repository](https://github.com/sandipp00/ai-recommendation-system)

### 6. Credit Card Fraud Detection
**Python · Scikit-learn · FastAPI · pytest**

A machine learning pipeline for identifying potentially fraudulent transactions in an imbalanced dataset.

- Compares Logistic Regression and Random Forest
- Evaluates models using PR-AUC, ROC-AUC, and classification metrics
- Selects the candidate model based on PR-AUC
- Exposes predictions through a FastAPI endpoint

[View Repository](https://github.com/sandipp00/credit-card-fraud-detection)

### 7. FinPulse — Financial Analytics Platform
**Python · Pandas · NumPy · FastAPI · React · SQLite · Recharts**

A financial analytics application for exploring stock and cryptocurrency market data and evaluating historical performance and risk.

- Ingests historical data for equities, Bitcoin, Ethereum, and NIFTY 50
- Calculates returns, cumulative growth, annualized volatility, Sharpe ratio, and maximum drawdown
- Combines a Python analytics layer with a FastAPI backend and React interface
- Includes automated tests

[View Repository](https://github.com/sandipp00/FinPulse)

### 8. Fitness AI Platform
**Python · FastAPI · Flutter · AI**

A mobile-first fitness platform combining health-data synchronization, activity analytics, workout planning, and AI-assisted coaching.

[View Repository](https://github.com/sandipp00/fitness-ai-platform)

## 📈 Data Analytics Projects

| Project | Stack | Focus |
|---|---|---|
| [Banking Credit Risk Analytics](https://github.com/sandipp00/banking-credit-risk-analytics) | Python · PostgreSQL · SQL · Power BI | Default and delinquency rates, credit-risk exposure |
| [Walmart Retail Sales Analytics](https://github.com/sandipp00/Walmart-Retail-Sales-Analytics) | Python · SQL · Power BI · ML | Store sales analysis and demand forecasting |
| [Online Advertising Optimization](https://github.com/sandipp00/online-advertising-performance-optimization) | Python · ML | Ad spend and sales optimization |
| [Netflix Content Analytics](https://github.com/sandipp00/netflix-content-analytics) | Python · SQLite · Streamlit | Catalog EDA and interactive dashboard |
| [HR Analytics Dashboard](https://github.com/sandipp00/hr-analytics-dashboard) | SQL · Python · Power BI | Employee attrition analysis |
| [Superstore Sales Dashboard](https://github.com/sandipp00/Superstore_Sales_Dashboard) | Power BI · DAX | Sales, profit, and regional performance |

## 📚 Currently Learning

- Advanced machine learning and model evaluation
- RAG evaluation and retrieval optimization
- Agentic AI and multi-step workflows
- MLOps, Docker, and deployment practices

## 📊 GitHub Activity

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=sandipp00&show_icons=true&theme=tokyonight&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=sandipp00&layout=compact&theme=tokyonight&hide_border=true)

## 🤝 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sandippradhan0/)

[![LeetCode](https://img.shields.io/badge/LeetCode-Profile-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/sandippradhan870/)

[![GitHub](https://img.shields.io/badge/GitHub-sandipp00-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sandipp00)

---

*Building practical AI solutions through data, machine learning, and software engineering.* 🚀

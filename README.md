# Luong Duc Thang
**Data Science student focused on AI Engineering, NLP, and Data Analytics.**<br>
I build AI and data systems with measured evaluation — agentic RAG, Text-to-SQL, data-analysis agents, daily data pipelines — and analytics projects that end in business recommendations.

<p align="left">
  <a href="https://github.com/luongducthangDS?tab=repositories">
    <img alt="Repositories" src="https://img.shields.io/badge/Portfolio-39%20public%20repos-24292f?style=for-the-badge&logo=github">
  </a>
  <a href="https://github.com/luongducthangDS/DocuMindAI">
    <img alt="RAG" src="https://img.shields.io/badge/Legal%20RAG-answer%20accuracy%200.935-2E8B57?style=for-the-badge">
  </a>
  <a href="https://github.com/luongducthangDS/viet-data-sql-assistant">
    <img alt="Text-to-SQL" src="https://img.shields.io/badge/Text--to--SQL-94%25%20accuracy-0A66C2?style=for-the-badge">
  </a>
</p>

## What I Work On

- **AI Engineering:** Agentic RAG, Text-to-SQL, safe tool-calling agents, LLM failover chains, evaluation harnesses, and deployment with Docker.
- **NLP:** Vietnamese NLP, bilingual text similarity, neural machine translation, and academic document search.
- **Data Engineering:** Scheduled pipelines with dbt + DuckDB, immutable raw storage, data quality gates, and GitHub Actions.
- **Data Analytics & ML:** Demand forecasting (LightGBM), promotion analysis, customer segmentation and cohort retention, Power BI dashboards.

## Featured AI Engineering

| Project | What it does | Stack |
| --- | --- | --- |
| [DocuMind AI](https://github.com/luongducthangDS/DocuMindAI) | Agentic RAG and compliance checking for Vietnamese labor and social-insurance law — hybrid BM25 + dense retrieval with RRF and a legal-validity (`as_of_date`) filter. On a 199-question gold set: answer accuracy **0.763 → 0.935**, expired-law context **21.6% → 0%**. 284 tests, MLflow-tracked eval | Python, LangGraph, FastAPI, MLflow, React, Docker |
| [Viet Data SQL Assistant](https://github.com/luongducthangDS/viet-data-sql-assistant) | Vietnamese Text-to-SQL chatbot — schema-grounded generation over a 14-table PostgreSQL DB, safety validator, self-repair retry loop. **94% accuracy (47/50)** on a 3-tier benchmark, 100% safety refusals | Python, FastAPI, PostgreSQL, LLMs |
| [Data Analysis AI Agent](https://github.com/luongducthangDS/data_analysis_ai_agent) | Upload CSV/XLSX, ask in Vietnamese → LLM writes a JSON plan, validated against the real schema and run by pandas (no `eval`/`exec`/SQL). Rejects answers whose numbers don't match results. **86/100** on a 100-question eval, p95 3.2s; blocks **18/18** adversarial attacks in CI | Python, LangGraph, FastAPI, React, Docker |

## Data & Analytics

| Project | Key result | Stack |
| --- | --- | --- |
| [FMCG Demand Forecasting — Walmart](https://github.com/luongducthangDS/fmcg-demand-forecasting-walmart) | Store × department LightGBM cuts 12-week-ahead error by **32.9%** vs the best baseline (WMAE 37,329 vs 55,644); promotion analysis that separates correlation from causal claims | Python, LightGBM, pandas |
| [Vietnam Air Quality Pipeline](https://github.com/luongducthangDS/vn-air-quality-pipeline) | Daily pipeline: hourly PM2.5/PM10/NO₂/O₃ for 5 cities → immutable raw → dbt + DuckDB → data quality gate → report. Hanoi exceeds the national PM2.5 standard on **33.8%** of days | Python, dbt, DuckDB, GitHub Actions |
| [Rossmann Store Performance](https://github.com/luongducthangDS/rossmann-store-performance-analysis) | Promotions lift sales **+38.8%**, decaying from +57% on Monday to +22% on Friday; the lift comes mostly from more customers, not bigger baskets | Python, pandas |
| [E-commerce Customer Segmentation (RFM)](https://github.com/luongducthangDS/ecommerce-customer-segmentation-rfm) | RFM + cohort retention on 96k Olist orders: repeat rate only **3.0%**, month-1 retention 5.45% → acquisition matters more than loyalty programs | Python, SQL |
| [Online Retail Dashboard Power BI](https://github.com/luongducthangDS/ONLINE-RETAIL-DASHBOARD-POWER-BI) | Business dashboard for retail analytics | Power BI |

## Research & NLP

| Project | What it does | Stack |
| --- | --- | --- |
| [LLM Evaluation for Vietnamese NLP](https://github.com/luongducthangDS/LLM-Evaluation-for-Vietnamese-NLP) | Student research (2025–2026) evaluating LLMs on Vietnamese NLP tasks | Python |
| [Bilingual Text Similarity with LLMs](https://github.com/luongducthangDS/APPLICATION-OF-LARGE-LANGUAGE-MODELS-MEASURING-SIMILARITY-OF-BILINGUAL-TEXT) | Student research (2024–2025) measuring Vi/En text similarity with LLMs | Jupyter Notebook, NLP |
| [RAG for Academic Document Search](https://github.com/luongducthangDS/RAG-for-Academic-Document-Search) | Retrieval workflow for searching and understanding academic documents | RAG, NLP |
| [Neural Machine Translation En-Vi](https://github.com/luongducthangDS/Neural-Machine-Translation-En-Vi-) | Deep learning En→Vi translation | Jupyter Notebook |
| [Movie Recommendation System](https://github.com/luongducthangDS/movie_recommendation_system) | Recommendation system for movie discovery | Python, ML |

## In Progress

Built, but benchmarks not run yet — results will be published only after they're measured:
- [SLM Fine-Tuning & Serving](https://github.com/luongducthangDS/slm-finetune-serving-pipeline) — QLoRA fine-tuning + vLLM serving with semantic caching.
- [Multimodal IDP & Visual RAG](https://github.com/luongducthangDS/multimodal-idp-vlm) — VAT invoice extraction with Qwen2-VL, per-field F1 evaluation.
- [Enterprise Multi-Agent Ops](https://github.com/luongducthangDS/enterprise-multi-agent-ops) — LangGraph incident-resolution agents with a human-in-the-loop approval gate.

## Tech Stack

**Languages & Data**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=111111)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

**AI & LLM Engineering**
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![LangSmith](https://img.shields.io/badge/LangSmith-F05032?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-2E8B57?style=flat-square)
![NLP](https://img.shields.io/badge/NLP-0A66C2?style=flat-square)
![LLMs](https://img.shields.io/badge/LLMs-6F42C1?style=flat-square)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)

**ML & Data Engineering**
![LightGBM](https://img.shields.io/badge/LightGBM-2E7D32?style=flat-square)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logoColor=111111)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=111111)

**Backend & Deploy**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=111111)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

## Current Direction

- Finishing benchmarks for the in-progress projects above, and publishing numbers only after they're measured.
- Next project: credit risk modelling, to add a finance domain alongside retail, legal, and environmental data.
- Keeping every project reproducible: fixed eval sets, logged runs, CI checks.

## Connect

- GitHub: [github.com/luongducthangDS](https://github.com/luongducthangDS)
- Location: Hanoi, Vietnam

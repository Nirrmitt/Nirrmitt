<h1 align="center">Nirrmit R. Tickoo</h1>
<p align="center"><strong>AI/ML Engineer · Generative AI · NLP · Data Products</strong></p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=500&size=17&pause=1200&color=315F4D&center=true&vCenter=true&width=650&lines=Applied+Machine+Learning+%26+NLP;GenAI+Applications+with+OpenRouter+%26+OpenAI;Data+Pipelines%2C+APIs+%26+Analytics+Products" alt="Applied machine learning, GenAI, data pipelines, and analytics products" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/n-r-t/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="Connect on LinkedIn" /></a>
  <a href="https://nirrmitt.github.io/NRT-Terminal/"><img src="https://img.shields.io/badge/Portfolio-Visit-315F4D?style=flat&logo=githubpages&logoColor=white" alt="Visit portfolio" /></a>
  <a href="mailto:nirrmit.rtickoo@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-BB4A3A?style=flat&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/Nirrmitt"><img src="https://img.shields.io/badge/GitHub-Projects-24292F?style=flat&logo=github&logoColor=white" alt="GitHub projects" /></a>
</p>

<p align="center">
  <a href="#selected-projects">Projects</a> ·
  <a href="#technical-toolkit">Toolkit</a> ·
  <a href="#more-projects">More work</a> ·
  <a href="#contact">Contact</a>
</p>

---

## About

I build practical AI and data applications that turn unstructured documents, text, and operational data into useful decisions. My work spans semantic matching and NLP, model-backed APIs, data pipelines, and interactive analytics-from ingestion and validation through to a usable interface.

I’m especially interested in **applied machine learning, GenAI product engineering, NLP, and reliable Python systems**. I focus on explaining what a system actually does, how it is evaluated, and where its limitations are.

## Selected projects

### 1. [AI Resume Analyzer + EDA](https://github.com/Nirrmitt/AI-Resume-Analyzer-plus-EDA)
**Applied ML · NLP · Streamlit**

Compares a resume with a job description using SentenceTransformer semantic similarity, spaCy/rule-based information extraction, and weighted skill and experience signals. Supports PDF, DOCX, and TXT input, and returns a match breakdown, missing skills, and feedback. Includes a CLI, Streamlit interface, and analysis notebook.

`SentenceTransformers` `spaCy` `scikit-learn` `Streamlit`

### 2. [RetailIQ -Ask Your Data](https://github.com/Nirrmitt/Sense-your-data)
**GenAI · OpenRouter/OpenAI · FastAPI**

A natural-language-to-SQL prototype for retail questions. It asks an OpenRouter or OpenAI-compatible model for a PostgreSQL `SELECT` statement, applies lightweight output checks, and presents a query preview in Streamlit.

**Scope note:** generated SQL is not executed; document retrieval (RAG) is not implemented. The SQL checks are a guardrail, not a SQL parser or authorization system.

`OpenRouter` `OpenAI SDK` `FastAPI` `PostgreSQL` `Streamlit`

### 3. [Automated KPI Extraction & Analytics Dashboard](https://github.com/Nirrmitt/Automated-KPI-Extraction--Analytics-Dashboard)
**Document processing · Data engineering · Analytics**

Ingests PDF and text reports, extracts revenue, churn, and NPS with deterministic regular-expression rules, validates records with Pydantic, and stores them idempotently with SQLAlchemy and SQLite. A Streamlit/Plotly dashboard adds date filtering, KPI trends, and CSV export.

This pipeline is deliberately rule-based; the repository does not currently use an LLM for KPI extraction.

`Python` `Pydantic` `SQLAlchemy` `SQLite` `Plotly`

### 4. [Retail Analytics Platform](https://github.com/Nirrmitt/Retail-Analytics-Platform)
**Backend engineering · APIs · Analytics**

A retail transaction-ingestion and KPI system with a FastAPI service, async PostgreSQL access, validated ingestion, and a Streamlit/Plotly dashboard. A transaction simulator exercises the ingestion and sales-analysis flow.

`FastAPI` `asyncpg` `PostgreSQL` `Streamlit` `Plotly`

### 5. [Automated Retail Analytics Reporter](https://github.com/Nirrmitt/Automated-Retail-Platform)
**ETL · Reporting automation · Delivery**

An end-to-end reporting workflow that ingests retail data, calculates business KPIs, creates charts and PDF reports, and automates delivery and scheduling. The repository documents email-based reporting and GitHub Actions scheduling.

`Python` `Pandas` `Plotly` `PDF reporting` `GitHub Actions`

## Technical toolkit

<p>
  <strong>Languages</strong><br />
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python" /></a>
  <a href="https://www.postgresql.org/"><img src="https://img.shields.io/badge/SQL-4169E1?style=flat&logo=postgresql&logoColor=white" alt="SQL" /></a>
</p>
<p>
  <strong>AI, ML & NLP</strong><br />
  <a href="https://scikit-learn.org/"><img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white" alt="scikit-learn" /></a>
  <a href="https://www.sbert.net/"><img src="https://img.shields.io/badge/SentenceTransformers-Embedding%20Models-6B4FBB?style=flat" alt="SentenceTransformers" /></a>
  <a href="https://spacy.io/"><img src="https://img.shields.io/badge/spaCy-NLP-09A3D5?style=flat" alt="spaCy" /></a>
  <a href="https://openrouter.ai/"><img src="https://img.shields.io/badge/OpenRouter-LLM%20APIs-5B6CFF?style=flat" alt="OpenRouter" /></a>
  <a href="https://platform.openai.com/docs/"><img src="https://img.shields.io/badge/OpenAI-Compatible%20APIs-412991?style=flat&logo=openai&logoColor=white" alt="OpenAI-compatible APIs" /></a>
</p>
<p>
  <strong>Data, APIs & applications</strong><br />
  <a href="https://fastapi.tiangolo.com/"><img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" alt="FastAPI" /></a>
  <a href="https://streamlit.io/"><img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white" alt="Streamlit" /></a>
  <a href="https://www.postgresql.org/"><img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL" /></a>
  <a href="https://www.sqlite.org/"><img src="https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white" alt="SQLite" /></a>
  <a href="https://pandas.pydata.org/"><img src="https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white" alt="Pandas" /></a>
  <a href="https://plotly.com/python/"><img src="https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white" alt="Plotly" /></a>
  <a href="https://powerbi.microsoft.com/"><img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black" alt="Power BI" /></a>
  <a href="https://www.docker.com/"><img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker" /></a>
</p>

## More projects

- [Landslide Data Analysis](https://github.com/Nirrmitt/Case-Study-Landslide-Data-Analysis) -Python EDA of NASA's Global Landslide Catalog, including data cleaning, time/geography trends, trigger analysis, and outlier exploration.
- [Layoffs Data Cleaning & EDA](https://github.com/Nirrmitt/Data-Cleaning-Exploratory-Data-Analysis) -MySQL workflow using staging tables, CTEs, window functions, standardization, and exploratory queries on a public layoffs dataset.
- [Hospital Mortality SQL & Tableau Case Study](https://github.com/Nirrmitt/Hospital-Mortality-Prediction-) -SQL analysis and Tableau visualization of hospital outcomes. Despite the repository name, this is a SQL/BI case study, not a trained machine-learning prediction model.
- [Fitness.AIO](https://github.com/Nirrmitt/Fitness-AI) -a small diet-tracking project for logging food and monitoring calorie and macronutrient intake.
- [Portfolio site](https://nirrmitt.github.io/NRT-Terminal/) -project portfolio and personal site.

<details>
  <summary>Research and earlier work</summary>

- [GAN-Aimbot / ViZDoom experiments](https://github.com/Nirrmitt/GAN-Aimbot) -a research-oriented repository with experiment and data-collection scripts associated with GAN-Aimbots research. This is exploratory work, not a production application.
</details>

## Currently learning

- Better evaluation and testing practices for NLP and LLM applications
- Retrieval and grounded question-answering patterns
- Workflow orchestration with Airflow and transformation practices with dbt

## Contact

Interested in discussing applied AI/ML, NLP, GenAI applications, or data products? Reach me on [LinkedIn](https://www.linkedin.com/in/n-r-t/) or by [email](mailto:nirrmit.rtickoo@gmail.com).

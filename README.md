<h1 align="center">Hi, I'm Brian Mahlatini 👋</h1>

<h3 align="center">AI & ML Engineer — Production LLM & Agentic Systems</h3>

<p align="center">
  <strong>Python</strong> · <strong>FastAPI</strong> · <strong>n8n</strong> · <strong>Node.js</strong> · <strong>AWS</strong> · <strong>LLMs, RAG, Fine-Tuning, MLOps</strong>
</p>

<p align="center">
  📍 Cape Town, South Africa &nbsp;•&nbsp; 🌍 Open to <strong>Remote · Contract · Full-Time</strong>
</p>

***

I build **AI systems that actually run in production** — not demos, not notebooks. Systems that handle real traffic, fail safely, and leave an audit trail.

My work spans four connected areas:

**🤖 AI Agents & LLM Engineering** — I design agentic pipelines that classify, reason, and act: multi-agent panels with disagreement detection, **RAG** grounded in real knowledge bases, structured output contracts, tool calling, and prompt engineering built around **confidence floors** rather than blind trust. I work with **Claude and OpenAI APIs**, and fine-tune open models with **LoRA/QLoRA** on Hugging Face when an API call isn't the right answer.

**⚡ Workflow Automation** — I build large-scale **n8n** pipelines (40–113 nodes) that move work end to end: multi-source intake, parallel enrichment, deterministic pre-scoring that gates LLM spend, confidence-based routing, idempotent writes, and quarantine paths so nothing is ever silently dropped.

**🧠 Machine Learning** — Classification, forecasting, recommendation and risk scoring with **scikit-learn, XGBoost, LightGBM and PyTorch** — with leakage-free feature engineering, threshold optimisation tied to business cost, **SHAP** explainability, and MLflow-tracked deployment rather than models that die in a notebook.

**🔧 Backend & Integration** — **Python/FastAPI** and **Node.js** services, PostgreSQL schema and query design, ETL pipelines, third-party REST/SOAP integration, HMAC-secured APIs, atomic state machines, and AWS infrastructure provisioned with Terraform.

The thread running through all of it is **safety engineering**: *idempotency, confidence gates, explicit autonomy boundaries, quarantine fallbacks, append-only audit rows, and human-in-the-loop escalation* — the things that decide whether an AI system survives contact with real users.

***

## 💼 Experience

### **AI & Full-Stack Developer**
**Genius Humans** · Cape Town, South Africa · *Jul 2024 – Present*

- Designed and shipped **production agentic AI systems** — multi-lane classification pipelines, LLM answering layers grounded in **RAG**, structured output contracts, tool calling, and confidence-gated routing with explicit autonomy boundaries
- Built **large-scale workflow automation** in **n8n** (40–113 node pipelines): multi-source intake, parallel enrichment, deterministic pre-scoring that gates LLM spend, idempotent writes, quarantine paths, and per-run metrics
- Developed **backend services and REST APIs** in **Python/FastAPI** and **Node.js** — Pydantic validation, HMAC-secured endpoints, atomic state machines, structured logging, and full test suites
- Built and served **machine learning models** for classification, forecasting and risk scoring — leakage-free feature engineering, threshold optimisation tied to business cost, **SHAP** explainability, and tracked deployment
- Designed **PostgreSQL/Supabase schemas**, ETL pipelines, and analytics views supporting operational reporting and executive dashboards
- Integrated **third-party REST and SOAP systems** — Microsoft Graph, helpdesk platforms, payment gateways, identity verification and banking validation services
- Provisioned and secured **AWS infrastructure with Terraform** — S3 with KMS encryption and versioning, least-privilege IAM, Lambda, and Docker-based deployment
- Built **React/Next.js frontends** and internal dashboards over FastAPI services for operational visibility

> `Python` · `FastAPI` · `Node.js` · `n8n` · `Claude/OpenAI APIs` · `scikit-learn` · `PostgreSQL/Supabase` · `AWS (S3, Lambda, IAM, KMS)` · `Terraform` · `React` · `Docker`

<br>

### **Software Engineer — Backend & Data Systems**
**Wenzhou Hams IT Co., Ltd** · Wenzhou, China · *Feb 2021 – Jun 2024*

- Built **backend services and REST APIs** using Python, Node.js, and Express against PostgreSQL and MongoDB
- Designed **ETL workflows** and integration services for ingestion, transformation, validation, and reporting
- Designed **relational schemas and indexing strategies**; optimised slow query paths across reporting workloads
- Delivered production software in **agile, cross-functional teams**

> `Python` · `Node.js` · `Express` · `PostgreSQL` · `MongoDB` · `Docker`

***

## 🤖 Production Automation & Agentic Systems

*Seven production-grade n8n workflow showcases — each with full architecture documentation, decision-path tables, honest design trade-offs, and runnable demos.*

### 🔹 [Multi-Agent Support Triage Orchestrator](https://github.com/brianmahlatini/Northwind-Cloud-Multi-Agent-Support-Triage-Orchestrator-)
**`n8n`** **`Multi-Agent`** **`HMAC`** **`PII Redaction`** — **66 nodes**

Multi-agent consensus pipeline with **signature verification**, parallel enrichment, a **weighted agent panel**, a **disagreement index** that forces human review when agents diverge, and a **self-healing dead-letter replay** path.

### 🔹 [Idempotent Financial Reconciliation Engine](https://github.com/brianmahlatini/Idempotent-Financial-Reconciliation-Engine)
**`n8n`** **`Reconciliation`** **`Idempotency`** — **44 nodes**

Scheduled **three-way reconciliation** across payment providers and a card gateway. Deterministic **GL cross-reference with 0.01 tolerance**, exposure-banded routing, and **suspense-account parking** for unmatched exposure.

### 🔹 [Real-Time E-Commerce Order Intelligence Pipeline](https://github.com/brianmahlatini/Real-Time-E-Commerce-Order-Intelligence-Pipeline)
**`n8n`** **`Fraud Scoring`** **`LLM Cost Gate`** — **43 nodes**

**Dual-mode intake** (webhook + batch sweep), parallel risk/inventory/shipping enrichment, a **deterministic fraud prescorer that gates LLM spend**, and confidence-gated fulfilment routing.

### 🔹 [AI-Powered HR Candidate Screening Pipeline](https://github.com/brianmahlatini/AI-Powered-HR-Candidate-Screening-Pipeline)
**`n8n`** **`Bias Shield`** **`Structured LLM Output`** — **40 nodes**

A **bias shield** scrubs PII and detects protected-attribute language ***before*** inference; the scorer only ever sees a scrubbed CV, and **any bias flag forces unconditional human review**.

### 🔹 [Multi-Channel Customer Support Triage & Auto-Resolution](https://github.com/brianmahlatini/Multi-Channel-Customer-Support-Triage-Auto-Resolution-Engine)
**`n8n`** **`Intent Classification`** **`SLA Engine`** — **47 nodes**

Webhook + email intake, language detection, sentiment scoring, **KB-powered auto-resolution**, and **SLA clocks scaled by tier and urgency** — with complaints and non-English traffic **always** escalating to a human.

### 🔹 [Claims Confidence-Gated Document Extraction](https://github.com/brianmahlatini/Claims-Confidence-Gated-Document-Extraction)
**`n8n`** **`OCR`** **`Confidence Floors`**

Document extraction with **per-field confidence floors** — anything below threshold routes to human verification rather than silently entering the system.

### 🔹 [IBU Claims Self-Healing Ingest Pipeline](https://github.com/brianmahlatini/IBU-Claims-Self-Healing-Ingest-Pipeline)
**`n8n`** **`Self-Healing`** **`Retry & Backoff`**

Claims ingest with **automatic fault recovery** — failed records are quarantined, diagnosed, and replayed rather than silently dropped, with **exponential backoff** and an append-only failure ledger.

> ***Design principles shared across all seven:***
> *idempotency-first · parallel enrichment · rules before models with a measurable LLM cost gate · confidence floors · explicit autonomy boundaries · append-only audit rows · quarantine fallbacks · per-run metrics*

***

## 🧠 Machine Learning & AI Projects

### 🔸 [Fraud Detection System — Real-Time ML Risk Scoring](https://github.com/brianmahlatini/Fraud-Detection-System)
**`Python`** **`LightGBM`** **`XGBoost`** **`SHAP`** **`FastAPI`** **`PostgreSQL`**

Millisecond transaction scoring. Logistic Regression, Random Forest, XGBoost and LightGBM compared on **PR-AUC — 0.871 best**, with **SHAP explainability** and Postgres-backed audit logging behind a production inference API.

### 🔸 [Customer Analytics & A/B Testing Platform](https://github.com/brianmahlatini/Customer-Analytics-AB-Testing-Platform)
**`Python`** **`scikit-learn`** **`FastAPI`** **`React`** **`Docker`**

**RFM segmentation**, clustering, churn prediction, **CLV modelling**, cohort and funnel analysis, market basket analysis and **A/B testing** — with **leakage-free feature engineering** throughout.

### 🔸 [RAG Document Q&A Platform](https://github.com/brianmahlatini/RAG-PROJECT)
**`FastAPI`** **`OpenAI`** **`FAISS`** **`TF-IDF`** **`React`**

Retrieval-augmented question answering over uploaded PDFs. **TF-IDF retrieval with optional FAISS acceleration**, plus auth, RBAC, audit logging and an admin analytics dashboard.

### 🔸 [Recommendation Engine](https://github.com/brianmahlatini/Recommendation-Engine)
**`Python`** **`Matrix Factorization`** **`Neural CF`** **`FastAPI`**

Collaborative filtering, **SVD**, **neural collaborative filtering** and popularity baselines — evaluated with **Leave-One-Out validation, Hit Rate, Precision@K, NDCG@K** and catalogue coverage. Shared feature pipelines **eliminate train/serve skew**.

### 🔸 [End-to-End Data Warehouse & Analytics Platform](https://github.com/brianmahlatini/End-to-End-Data-Warehouse-Analytics-Platform)
**`Python`** **`PostgreSQL`** **`SQLAlchemy`** **`FastAPI`** **`React`**

ETL with validation and cleansing into a **star-schema warehouse**, reusable SQL analytics views powering **executive KPIs**, and a React BI dashboard over FastAPI.

### 🔸 [Customer Churn Prediction Platform](https://github.com/brianmahlatini/Customer-Churn-Prediction-Platform)
**`Python`** **`scikit-learn`** **`XGBoost`** **`FastAPI`**

End-to-end churn modelling with **leakage-aware feature engineering**, class-imbalance handling, threshold optimisation tied to retention cost, and a served inference endpoint.

### 🔸 [Demand Forecasting Platform](https://github.com/brianmahlatini/Demand-Forecasting-Platform)
**`Python`** **`Prophet`** **`Time Series`** **`FastAPI`**

Time-series forecasting with **trend, seasonality and stationarity analysis**, strict **time-based train/test splitting** to prevent lookahead bias, and MAPE/MAE/RMSE evaluation.

***

## 🛠️ Tech Stack

| | |
|---|---|
| **Languages** | **Python** · **TypeScript** · **JavaScript** · SQL · Java · C# |
| **AI & LLM Systems** | RAG · AI Agents & Tool Calling · Prompt Engineering · Structured Output · Claude API · OpenAI API · LangChain · MCP · Hugging Face · **LoRA/QLoRA Fine-Tuning** · Llama 3 · BERT |
| **Machine Learning** | scikit-learn · XGBoost · LightGBM · PyTorch · CNNs & Transfer Learning · Prophet · Pandas · NumPy · SHAP/LIME · Feature Engineering · Imbalanced Data · Leakage Detection |
| **Model Evaluation** | ROC-AUC · PR-AUC · Precision/Recall/F1 · NDCG@K · Cross-Validation · Threshold Optimisation |
| **MLOps** | MLflow · Experiment Tracking · Model Registry & Versioning · Drift Detection · Retraining Pipelines · Model Deployment |
| **Backend & APIs** | FastAPI · Django · **Node.js** · Express · REST · SQLAlchemy · Pydantic · WebSockets · Background Workers *(Celery, BullMQ)* |
| **Automation & Integration** | **n8n** · Microsoft Graph · Freshdesk · Payment gateways · Webhooks · Third-party REST/SOAP integration |
| **Data** | PostgreSQL · Supabase · MongoDB · Redis · ETL · Star Schema · Data Validation |
| **Cloud & DevOps** | AWS *(EC2, S3, Lambda, IAM, KMS, RDS)* · Terraform · Docker · GitHub Actions · CI/CD · Nginx · Linux |
| **Security** | JWT · OAuth2 · RBAC · HMAC-SHA256 · PBKDF2/BCrypt · POPIA-aware data handling |
| **Frontend** | React · Next.js · TypeScript · Tailwind CSS |

**Also worked with:** Java / Spring Boot · C# / ASP.NET Core · Angular · Kafka · RabbitMQ · SignalR · Elasticsearch

***

## 🎓 Education

**B.Eng. Computer Science and Technology**
*Wenzhou University, Zhejiang, China* · **2021 – 2024**

***

## 🎯 Currently

- 🚀 Running a **live agentic AI system in production** handling real enterprise traffic
- 🔬 Building out **production ML serving** with MLflow tracking and drift monitoring
- 💼 Open to **AI/LLM Engineering** · **ML Engineering** · **Automation & Integration Engineering** — *remote or contract*

***

## 📫 Contact

**Email:** mahlatinibrian@gmail.com
**LinkedIn:** [brian-m-a87a3341a](https://www.linkedin.com/in/brian-m-a87a3341a)

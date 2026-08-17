# Hi there 👋 I'm Duy

**Senior Data Engineer @ [MoMo](https://momo.vn/)** — Data Platform, Technology Center.
I build the data platform behind Vietnam's leading fintech super-app: lakehouse architecture, data governance & protection, and the Agentic-AI systems that sit on top of it.

📄 TL;DR — grab the [PDF version of my CV](https://cdn.statically.io/gh/viplazylmht/viplazylmht/76a6ae0/HaVanDuy_DataEngineer.pdf)
🎓 Google Cloud Certified [**Professional Data Engineer**](https://www.credly.com/badges/0d8ee49b-019f-41eb-81e8-34761de76683/public_url) · Aug 2026 – Aug 2028

---

## 💼 Experience

**[MoMo (M_Service)](https://momo.vn/)** — Data Platform, Technology Center · Ho Chi Minh City · *Jan 2022 – Present*

Joined through the **MoMo Talents Program** and grew through the full track: Trainee → Junior Data Engineer → Data Engineer II → **Senior Data Engineer (Apr 2026)**.

What I own day to day:

- **Lakehouse architecture & migration** — Trino + Iceberg/Delta on GCS, running on GKE.
- **Data governance & protection** — unified catalog, credential vending, PII classification, access control.
- **Agentic-AI platform** — the framework MoMo teams use to ship AI workflows into production.
- **Platform cost & reliability** — query optimization, resource allocation, on-call data platform ops.

## 🎓 Education

**[University of Science, VNU-HCM](https://hcmus.edu.vn/)** — [Faculty of Information Technology](https://www.fit.hcmus.edu.vn/) · *Sep 2018 – May 2022*

B.Sc. in Computer Science, **Data Science** major · GPA 8.5 / 10

## 📜 Certifications

- **Professional Data Engineer** — Google Cloud. Issued Aug 14, 2026 · valid through Aug 14, 2028. [Verify on Credly](https://www.credly.com/badges/0d8ee49b-019f-41eb-81e8-34761de76683/public_url)
- A stack of Google Cloud badges (AI, Machine Learning, Deep Learning, Data Science) from Qwiklabs — [public profile](https://www.qwiklabs.com/public_profiles/d993ef28-71fb-4d72-9480-b89600dabc71).

## 📚 [Publications](https://orcid.org/0000-0003-2077-0435)

- **[MEP: A Comprehensive Medicines Extraction System on Prescriptions](https://doi.org/10.1007/978-3-031-41456-5_54)** — ICCCI 2023, *Computational Collective Intelligence*, pp. 713–725 (Sep 13, 2023).
- **[Medical Prescription Recognition Using Heuristic Clustering and Similarity Search](https://doi.org/10.1007/978-3-031-16014-1_60)** — ICCCI 2022, *Computational Collective Intelligence*, pp. 768–780 (Sep 21, 2022).

---

## 🚀 Projects

### Company projects (newest first)

**🛡️ Data Protection & Unified Catalog** · *2026 – Present*
Rolled out **Apache Gravitino** as the single unified catalog governing all metadata under the lakehouse, so every engine sees one consistent, centrally-managed view.
Researched and shipped **credential vending** to keep the platform compliant and secure: storage tokens are now auto-generated at runtime, short-lived and scoped, and every over-privileged service account was revoked from the Spark compute engines.
Also deployed **PII auto-classification**: automated scanning and tagging of sensitive personal data across the lakehouse to enforce least-privilege access and regulatory compliance.
*Fluent in:* Apache Gravitino, credential vending, short-term token exchange, Apache Ranger, Spark, Iceberg / Delta Lake

**🤖 Data Agent & Agentic-AI Platform** · *2025 – Present*
A scalable, maintainable framework that lets MoMo engineers ship new AI agents in days instead of months, with room to explore autonomous decision-making patterns in agentic design.
It powers chatbots and AI summarization for engineers and business users querying internal data and documents, clusters customer feedback into key topics with metrics, and delivers AI-generated daily insight reports to every business unit over Google Chat.
**Impact:** 30+ AI workflows, 100K+ total runs, 10B+ tokens processed, 3K+ weekly executions, and an 80% reduction in engineer time spent on periodic data analysis.
*Fluent in:* GenAI, Agentic AI, LangChain, FastAPI, SMTP Email, chatbots, RAG, evaluation pipelines, Claude (Cowork, Code)

**⚡ Agentic AI for Growth — AI Harness (POC)** · *2026*
Built an AI Harness on Claude Cowork + Claude Code for the Growth team's cashback campaign (*Hoàn Tiền Mua Sắm*) — agent instructions, skills, data interfaces, and evaluation criteria.
Ran cross-team knowledge sharing and trained non-technical users on prompt design, skill authoring, and evaluating agent output.
*Fluent in:* Claude Cowork, Claude Code, skill authoring, prompt engineering, agent evaluation, enablement & training

**🔐 Access Management** · *2024 – Present*
A **SOC 2-compliant** platform for time-based privileged access to all data, sensitive data, and policy tags across data warehouses, lakehouses, and internal services. It centralizes the approval process for **100% of data-access requests** on the data platform, with audit logs and compliance reports, plus a Google Chat bot for instant approval and execution — rated highly by data owners, leaders, and managers.
*Fluent in:* SOC 2 controls, FastAPI, OAuth2 / OpenID Connect, Apache Ranger, SMTP Email

**🔁 Data Pipeline Migration** · *2023 – Present*
A transpiling tool built on top of open-source projects (SQLGlot) to migrate SQL end-to-end from the production warehouse into the lakehouse, translating BigQuery → Trino and Spark dialects.
**Impact:** up to **90%** of the human cost of the migration phase removed, across hundreds of pipelines.
*Fluent in:* SQLGlot, Trino/Presto, BigQuery, Spark, Airflow

**🏞️ Data Lakehouse** · *2023 – Present*
Collaborated on the lakehouse solution that reduced the cost of workloads at MoMo. Researched and selected the open table format (Iceberg / Delta), then designed Trino/Spark on GKE as query engines over large batch data in GCS.
**Impact:** up to **70% lower cost per workload** thanks to spot instances, with no data SLA breaches.
*Fluent in:* Trino, Spark, GKE, GCS, BigQuery Storage, dbt, Airflow, Apache Ranger, Delta Lake, Apache Iceberg

**💰 Cost Optimization on GCP** · *2022 – 2023*
Led query optimization with other teams, moved services and ETL/ELT pipelines to on-premise Kubernetes, ran a BigQuery → Vertica experiment, and centralized BigQuery resource allocation per team by a divide-and-conquer principle.
**Impact:** **40%** cost saved, with zero stuck workloads.
*Fluent in:* BigQuery, Vertica, Kubernetes, Oracle APEX, GCP gRPC API

**🥇 Golden Record** — process for high-value Data Marts at MoMo
Built tools and services on top of open-source projects to control the data model's quality, freshness, and extensibility. Golden Record serves many dataflows, including events and transactions of the MoMo Super App.
*Fluent in:* dbt, Great Expectations, Airflow, GitLab, Kubernetes, Oracle OCI, Oracle APEX

### University projects

- **Citizens Problems Detection** — Deep Learning @ AI4VN
- [**Predict Covid19**](https://github.com/viplazylmht/Predict_Covid19) — Machine Learning / Data Visualization / Data Analysis
- [**Plant Pathology**](https://colab.research.google.com/drive/1Ypg77-WWaohRW_mIce7q2mshGX1vBlk5) — Deep Learning
- [**Hospital Inpatient Discharges**](https://github.com/viplazylmht/P4DS_final) — Data Visualization / Data Analysis
- [**Image Color Compression**](https://colab.research.google.com/github/viplazylmht/viplazylmht.github.io/blob/master/Projects/ImageProcessing/ImageColorCompression.ipynb) using K-means — Image Processing
- [**Image Transformation**](https://colab.research.google.com/github/viplazylmht/viplazylmht.github.io/blob/master/Projects/ImageProcessing/ImageTransformation.ipynb) — Image Processing
- [**Data Preprocessing Toolkits**](https://github.com/viplazylmht/DataMiningLab01) from scratch (Python) — Data Processing

---

## 🌍 Open Source Contributions

- [**SQLGlot**](https://sqlglot.com/) — improvements to BigQuery ↔ other-dialect translation accuracy; the same engine powers MoMo's internal transpiler.
- [**Great Expectations**](https://github.com/great-expectations/great_expectations/pull/6145) — added Vertica dialect support so GX can validate data quality on Vertica.
- [**dbt-vertica**](https://github.com/vertica/dbt-vertica/pull/32)
- [**dbt-oracle**](https://github.com/oracle/dbt-oracle/issues/31)

---

## 🧰 Skills

**Languages** · Python · SQL · Java · Kotlin · C/C++ · R · Bash

**Big Data & Lakehouse** · [Apache Spark](https://spark.apache.org/) · [Trino](https://trino.io/) / Presto · BigQuery · Vertica · MS SQL Server · Oracle OCI · Delta Lake · Apache Iceberg · [dbt](https://www.getdbt.com/) · [SQLGlot](https://sqlglot.com/) · ETL / ELT · Data modeling

**Orchestration & Infra** · [Airflow](https://airflow.apache.org/) · Kubernetes (GKE & on-prem) · Docker · Helm · Skaffold · kubectl · Bazel · CI/CD (GitHub Actions, GitLab CI, Jenkins) · IaC with Pulumi · Policy as code · Shell / Linux · Git

**Cloud** · Google Cloud (BigQuery, PubSub, Dataproc, GKE, GCS, Cloud Functions, Identity, Looker, gRPC API) · Oracle (APEX, OCI)

**Data Governance & Security** · [Apache Gravitino](https://gravitino.apache.org/) (unified catalog) · credential vending · [Apache Ranger](https://ranger.apache.org/) · [DataHub](https://datahubproject.io/) · [Great Expectations](https://greatexpectations.io/) · SOC 2 controls · OAuth2 / OpenID Connect · PII auto-classification · Data observability / quality / catalog

**AI / ML Engineering** · Generative AI · Agentic AI design · LangChain · Claude (Cowork, Code) · RAG · prompt engineering · evaluation pipelines · Scikit-learn · ML algorithms

**Ways of working** · Agile / Scrum · technical writing & documentation · cross-team enablement · MS Office

---

## 📊 GitHub Stats

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=viplazylmht&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

![Duy's GitHub stats](https://github-readme-stats.vercel.app/api?username=viplazylmht&show_icons=true&theme=radical)

---

## 📫 Contact

- 🔗 [LinkedIn](http://linkedin.com/in/duy-ha-6b2a11218)
- 🌐 [viplazylmht.github.io](https://viplazylmht.github.io/)
- 📧 hvduy37@gmail.com
- 👤 [Facebook](https://www.fb.com/viplazylmht)

<!--
**viplazylmht/viplazylmht** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->

# Hi, I'm Aayushi Jha 👋

**AI Data Engineer & GenAI Platform Lead** · 8+ years in Data Engineering

📧 aayushijha27@gmail.com · 🔗 [LinkedIn](https://www.linkedin.com/in/aayushi-jha-492778a0) · 📍 India

I design and build data pipelines, RAG systems, and AI-ready data infrastructure. Currently at **KPMG India**, designing AI-ready data architectures and governed data pipelines for enterprise clients in automobile manufacturing and IT research.

---

### My journey: Python Developer → Data Engineer → AI Data Engineer

**2017–2021 · Python Developer** (Head Field Solutions → Smile Internet Technologies)
Built 50+ Python data-source connectors with retry logic and scheduling, designed a PostgreSQL storage schema from scratch, and refactored undocumented legacy stored procedures for a 40% query performance gain.

**2021–2023 · Data Engineer** (Course5 Intelligence → Springbord Systems)
Scaled that foundation into production platforms: dbt/Redshift ELT pipelines across 5+ concurrent clients, and a Kafka + Databricks streaming rebuild that cut pricing-data latency from 18 hours to under 8 minutes across 70M+ daily events.

**2023–Present · AI Data Engineer** (Bitwise Solutions → KPMG India)
Extended data engineering into the systems behind production AI: a RAG knowledge platform over 500K+ documents (Bedrock, LangChain, OpenSearch), governed AI-ready lakehouses, and data-quality gates that keep LLM outputs grounded in accurate data.

---

### What I work on

- Production RAG systems and vector search over large document corpora
- AI-ready data lakehouses with governed, permissioned access for LLM workflows
- Data pipelines feeding GenAI workloads: ingestion, chunking, metadata tagging, freshness monitoring
- Data quality and governance frameworks (lineage, access tiers, automated checks)

### Highlight

Built a production RAG knowledge platform ingesting 500K+ documents (PDF, HTML, JSON), embedded with AWS Bedrock, indexed in OpenSearch, and served via FastAPI with user-level access control — full corpus searchable in under 2 seconds.

### Featured projects

The write-ups for my actual production work (the RAG platform above, a manufacturing data platform, and a real-time pricing pipeline) are in my [portfolio repo](https://github.com/aayushi-jha2018/portfolio). The repos below are open-source, CI-tested projects I built to show how I approach specific engineering problems, grouped by the career stage they represent -- each README explains the design decisions and includes at least one real failure case the tests catch.

**Data engineering foundations**

- **[resilient-connector-framework](https://github.com/aayushi-jha2018/resilient-connector-framework)** -- a reusable multi-source ingestion framework: pluggable connectors, retry with backoff, and scheduling, built to run unattended.
- **[pyspark-databricks-lakehouse](https://github.com/aayushi-jha2018/pyspark-databricks-lakehouse)** -- a Databricks-style medallion pipeline (bronze/silver/gold) in PySpark, with data-quality rules proven by tests and a documented Delta Lake migration path.
- **[airflow-etl-demo](https://github.com/aayushi-jha2018/airflow-etl-demo)** -- an Airflow DAG (extract/transform/validate/load) with a Great Expectations data-quality gate that's proven in tests to actually reject bad data.
- **[dbt-snowflake-elt-demo](https://github.com/aayushi-jha2018/dbt-snowflake-elt-demo)** -- staging/marts dbt models for Snowflake, with schema tests that CI proves catch bad data, not just pass on good data.
- **[streaming-dedup-pipeline](https://github.com/aayushi-jha2018/streaming-dedup-pipeline)** -- Kafka producer/consumer demo handling at-least-once delivery: deduplication and tumbling-window aggregation, tested in CI against a real broker.
- **[terraform-aws-network-module](https://github.com/aayushi-jha2018/terraform-aws-network-module)** -- a reusable VPC module (subnets, NAT, routing, security groups) with `fmt`/`validate`/`plan` running in CI, no cloud credentials needed.

**AI / GenAI layer**

- **[mini-rag-pipeline](https://github.com/aayushi-jha2018/mini-rag-pipeline)** -- chunking, embeddings, and FAISS retrieval over a small doc set.
- **[agentic-research-assistant](https://github.com/aayushi-jha2018/agentic-research-assistant)** -- a tool-using research agent: rule-based planner routes questions to a calculator, SQL lookup, or doc search tool, falls back on failure, and is checked against a labeled eval set in CI.

### Core Skills

**AI & GenAI**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square) ![RAG Pipelines](https://img.shields.io/badge/RAG%20Pipelines-4B8BBE?style=flat-square) ![AWS Bedrock](https://img.shields.io/badge/AWS%20Bedrock-232F3E?style=flat-square&logo=amazonaws&logoColor=white) ![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=flat-square) ![FAISS](https://img.shields.io/badge/FAISS-4B8BBE?style=flat-square) ![Prompt Engineering](https://img.shields.io/badge/Prompt%20Engineering-4B8BBE?style=flat-square) ![Agentic Workflows](https://img.shields.io/badge/Agentic%20Workflows-4B8BBE?style=flat-square)

**Data Engineering**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square) ![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white) ![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white) ![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white) ![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white) ![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white) ![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white) ![Spark Streaming](https://img.shields.io/badge/Spark%20Streaming-E25A1C?style=flat-square)

**Cloud**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white) S3 · Glue · EMR · Redshift · Bedrock · Lake Formation · IAM · Kinesis · CloudWatch

**Data Quality & Governance**

![Great Expectations](https://img.shields.io/badge/Great%20Expectations-FF6600?style=flat-square) ![Data Lineage](https://img.shields.io/badge/Data%20Lineage-546E7A?style=flat-square) ![Metadata Management](https://img.shields.io/badge/Metadata%20Management-546E7A?style=flat-square) ![Schema Governance](https://img.shields.io/badge/Schema%20Governance-546E7A?style=flat-square)

**DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![CI/CD](https://img.shields.io/badge/CI%2FCD-2088FF?style=flat-square) ![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

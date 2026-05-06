# E-Commerce Event-Driven Data Pipeline (Industrial Data Engineering Project)

## Project Overview

This project is a production-style Event-Driven Data Engineering Pipeline built using Databricks, PySpark, and Delta Lake. The pipeline processes multi-source e-commerce datasets with automated ingestion, validation, enrichment, SCD Type 2 processing, and analytics generation.

The project simulates a real-world industrial ETL workflow with modular notebook architecture, automated orchestration, file-based triggering, and scalable Delta Lake storage.

---

# Tech Stack

| Technology | Purpose |
|---|---|
| Databricks | Unified Data Engineering Platform |
| PySpark | Distributed Data Processing |
| Delta Lake | ACID Transactions & Incremental Processing |
| Databricks Volumes | Centralized Data Storage |
| Databricks Workflows | Pipeline Orchestration |
| GitHub | Version Control & Collaboration |
| Unity Catalog | Data Governance |
| SQL | Analytics & Reporting |
| JSON Triggers | Event-Driven Workflow Execution |

---

# Project Architecture

```text
Source Files
     ↓
Databricks Volumes
     ↓
JSON Trigger Detection
     ↓
Databricks Workflow
     ↓
Stage Load Pipelines
     ↓
Data Validation Layer
     ↓
Data Enrichment Layer
     ↓
Gold Analytics Tables
     ↓
Dashboard & KPI Reporting

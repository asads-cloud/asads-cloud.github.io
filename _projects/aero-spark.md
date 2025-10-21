---
layout: page
title: "Aero Spark"
subtitle: "Distributed data processing & orchestration"
featured: true
weight: 2
repo: "https://github.com/asads-cloud/aero-spark"
stack: ["Apache Spark", "Airflow", "Docker", "S3", "Athena"]
---

**What it is.** A modular framework demonstrating batch pipelines with **Spark** and orchestration via **Airflow**, containerized for reproducibility.

**Highlights**
- Declarative DAGs with sensible defaults for retries & SLAs
- Containerized dev/test via **Docker Compose**
- Data lake pattern using **S3** with query surfaces in **Athena**
- CI/CD ready for GitHub Actions

**Repository:** [asads-cloud/aero-spark]({{ page.repo }})

**Stack:** {{ page.stack | join: ", " }}

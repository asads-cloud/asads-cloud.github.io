---
layout: page
title: "Nimbus Transcribe"
subtitle: "Serverless speech-to-text pipeline on AWS"
featured: true
weight: 1
repo: "https://github.com/asads-cloud/nimbus-transcribe"
stack: ["AWS Lambda", "Amazon Transcribe", "S3", "IAM", "CloudWatch", "Terraform"]
---

**What it is.** A serverless transcription pipeline that ingests audio, triggers processing, and delivers text outputs with metadata.

**Highlights**
- Event-driven using **S3 → Lambda → Transcribe** with status callbacks
- Infrastructure via **Terraform** with least-privilege **IAM**
- Operational metrics + alerts in **CloudWatch**
- Designed for cost efficiency and easy extension (e.g., translate, redact PII)

**Repository:** [asads-cloud/nimbus-transcribe]({{ page.repo }})

**Stack:** {{ page.stack | join: ", " }}

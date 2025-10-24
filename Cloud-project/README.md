# CloudTrail Threat Hunter (with AI Anomaly Insights)

A beginner-friendly, free-tier **Cloud Security** project:
- Enable secure AWS logging (CloudTrail, Config, GuardDuty)
- Query logs with **Athena** to detect suspicious behaviors
- Use **AI embeddings + clustering** to surface anomalies from CloudTrail events
- Document findings and share a portfolio-ready write-up

## Why this project?
Recruiters want proof. This repo shows hands-on logging, detection engineering, and AI-assisted analysis end to end.

## Architecture (Phase 1–4)
1. CloudTrail/Config/GuardDuty → S3 (secure)
2. Athena tables + SQL detections (root activity, failed logins, unusual geo)
3. AI notebook (sentence-transformers + DBSCAN) to cluster anomalies
4. Findings report in `/docs/ai_findings.md`

## Repo structure

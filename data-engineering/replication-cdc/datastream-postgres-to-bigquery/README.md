# Datastream: PostgreSQL Replication to BigQuery

## 🎯 Objective
Set up **Datastream for BigQuery** to replicate changes from **Cloud SQL for PostgreSQL** into **BigQuery** for low-latency analytics (ELT/CDC).

## 🧱 Architecture
```mermaid
flowchart LR
  A[(Cloud SQL: PostgreSQL)] --> B[Datastream]
  B --> C[(BigQuery Dataset)]

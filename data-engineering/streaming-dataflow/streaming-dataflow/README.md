# Streaming Data Pipeline for NYC Taxi Dashboard (Dataflow)

## 🎯 Objective
Launch a **Dataflow** streaming job from a **template** to read taxi events from **Pub/Sub** and write to **BigQuery**, then analyze with SQL (and optionally visualize in Looker Studio).

## 🧱 Architecture
Pub/Sub (JSON events) → Dataflow (template) → BigQuery table → SQL/Looker Studio

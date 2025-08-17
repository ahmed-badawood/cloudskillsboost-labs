# BigLake: Qwik Start

## 🎯 Objective
Create a **BigLake** table over data in **Cloud Storage**, enforce **fine-grained access control** (row/column), and query it via **BigQuery**—without granting users raw bucket access.

## 🧱 Architecture
```mermaid
graph LR
  A[Cloud Storage] --> B[BigQuery Connection]
  B --> C[BigLake table]
  C --> D[BigQuery APIs]
  D --> E[Analysts and Pipelines]

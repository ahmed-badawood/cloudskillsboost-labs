# Cloud Run Function to Load BigQuery

## 🎯 Objective
Create, deploy, and test a **Cloud Run function (2nd gen Cloud Functions)** that loads a file from **Cloud Storage** into a **BigQuery** table using the BigQuery Python SDK.

## 🧱 What this demonstrates
- Event-driven ELT with Cloud Run functions (HTTP or GCS trigger)
- BigQuery Load Jobs (autodetect schema) from `gs://...`
- Minimal IAM and safe config via environment variables

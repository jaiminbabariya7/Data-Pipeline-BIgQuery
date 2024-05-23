# Data Pipeline Project

# GCP Console Link
- https://console.cloud.google.com/home/dashboard?project=data-pipeline-bigquery-424104

## Goal
Develop a data pipeline to ingest daily sales data files, product information, and customer details from Cloud Storage (GCS) into BigQuery, enabling efficient updates, historical analysis, and data joining capabilities.

## Project Phases
Phase 1: Data Preparation
Phase 2: BigQuery Schema Definition
Phase 3: Data Ingestion with Upsert Logic
Phase 4: Data Joining and Analysis
Phase 5: Partitioning for Scalability
Phase 6: Automation

## Repository Structure
- [`data`](data): Sample data files (CSV).
- [`query`](query): SQL scripts for table creation, data ingestion, and queries.
- [`scripts`](scripts): Cloud Function code for automating data ingestion, and code for data stilumation.
- [`docs`](docs): Detailed documentation for each phase of the project.
- [`output`](output): Images of the SQL Query Output.

## Getting Started
Follow the setup instructions in each phase's documentation.

## License
This project is licensed under the MIT License.

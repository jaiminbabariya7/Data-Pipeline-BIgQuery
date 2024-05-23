# Data Pipeline Project

## Goal
Develop a data pipeline to ingest daily sales data files, product information, and customer details from Cloud Storage (GCS) into BigQuery, enabling efficient updates, historical analysis, and data joining capabilities.

## Project Phases
1. [Data Preparation](docs/phase1_data_preparation.md)
2. [BigQuery Schema Definition](docs/phase2_schema_definition.md)
3. [Data Ingestion with Upsert Logic](docs/phase3_data_ingestion.md)
4. [Data Joining and Analysis](docs/phase4_data_joining_analysis.md)
5. [Partitioning for Scalability](docs/phase5_partitioning.md)
6. [Automation](docs/phase6_automation.md)

## Repository Structure
- `data/`: Sample data files (CSV).
- `sql/`: SQL scripts for table creation, data ingestion, and queries.
- `cloud_function/`: Cloud Function code for automating data ingestion.
- `docs/`: Detailed documentation for each phase of the project.

## Getting Started
Follow the setup instructions in each phase's documentation.

## License
This project is licensed under the MIT License.

# Data Pipeline Project

## Goal
Develop a data pipeline to ingest daily sales data files, product information, and customer details from Cloud Storage (GCS) into BigQuery, enabling efficient updates, historical analysis, and data joining capabilities.

## Project Phases
1. [`Phase 1: Data Preparation`](docs/Phase1: Data Preparation.md)
2. [`Phase 2: BigQuery Schema Definition`](docs/Phase2_schema_definition.md)
3. [`Phase 3: Data Ingestion with Upsert Logic`](docs/Phase3_data_ingestion.md)
4. [`Phase 4: Data Joining and Analysis`](docs/Phase4_data_joining_analysis.md)
5. [`Phase 5: Partitioning for Scalability`](docs/Phase5_partitioning.md)
6. [`Phase 6: Automation`](docs/Phase6_automation.md)

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

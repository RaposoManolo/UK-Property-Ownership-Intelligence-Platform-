# UK Property Ownership Analysis - Azure + Databricks

## Objective
Build a scalable data engineering pipeline to analyze UK property ownership data, focusing on companies and entities owning property across the UK.

## Tech Stack
- Azure Storage Account
- Azure Databricks
- PySpark
- Delta Lake
- Medallion Architecture (Bronze / Silver / Gold)

## Architecture
Raw UK Land Registry data (csv files) lands in Bronze storage.
Data is cleaned and standardized in Silver.
Business-ready analytical datasets are created in Gold.

## Project Status

| Component | Status |
|---|---|
| Azure Resource Group | Complete |
| Storage Layers (Bronze/Silver/Gold) | Complete |
| Databricks Workspace | Complete |
| Raw Data Ingestion | In Progress |
| Silver Transformations | Planned |
| Gold Analytics Layer | Planned |

<img width="1280" height="720" alt="Architecture" src="https://github.com/user-attachments/assets/73bdf9c9-826c-4daa-ab22-f2ce97957b80" />


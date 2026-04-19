
## Healthcare Medallion Pipeline

This project showcases a healthcare data engineering pipeline built using Bronze, Silver, and Gold architecture on Azure. It processes clinical and operational data through multiple layers for analytics, reporting, and downstream consumption.

### Overview
The pipeline ingests healthcare data from multiple source systems, stores raw data in the Bronze layer, standardizes and validates it in the Silver layer, and creates curated Gold datasets for reporting and analytics.

### Tech Stack
- Azure Data Factory
- Azure Databricks
- ADLS Gen2
- PySpark
- Spark SQL
- Delta Lake
- SQL

### Architecture
- Bronze layer for raw ingestion
- Silver layer for cleansing, standardization, and validation
- Gold layer for business-ready and analytics-ready datasets

### Example Data Sources
- Electronic Health Records
- Patient encounters
- Lab results
- Claims data
- Pharmacy data
- Reference datasets

### Key Features
- Metadata-driven ingestion
- Incremental and full loads
- Data quality validation
- Schema standardization
- Audit logging
- Reporting-ready outputs

### Folder Structure
- `data/` sample source references
- `notebooks/` transformation notebooks
- `pipelines/` orchestration documentation
- `docs/` architecture and design notes
- `sql/` validation and reporting queries

### Skills Demonstrated
- Azure data engineering
- Medallion architecture
- Healthcare data processing
- Incremental ETL design
- PySpark transformation development
- Data quality engineering

# insuranceanalaysis
# Insurance Data Engineering Project

This project implements a data pipeline using Azure Data Factory and Azure Databricks.

## Architecture
Source → ADLS → Bronze → Silver → Gold

## Technologies
- Azure Data Factory
- Azure Databricks
- PySpark
- Delta Lake
- Azure Data Lake Storage

## Pipeline
1. Raw insurance data ingested to Bronze layer
2. Data cleaning and transformation in Silver layer
3. Aggregated analytics tables created in Gold layer
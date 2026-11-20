# DineDash – End-to-End Data Engineering Project

## Project Overview

DineDash is an end-to-end data engineering project developed using Azure Databricks. It processes food delivery data through a structured data pipeline to transform raw data into meaningful, analysis-ready datasets.

## Technologies Used

- Azure Databricks
- PySpark
- Spark SQL
- Delta Lake
- Unity Catalog
- Delta Live Tables 
- Auto Loader
- COPY INTO
- Medallion Architecture

## Project Architecture

### Bronze Layer

Ingests raw data from source files into Bronze tables.

### Silver Layer

Cleans, validates, and transforms raw data.

### Gold Layer

Creates aggregated and analysis-ready datasets for reporting.

## Dataset

The project includes data related to:

- Customers
- Restaurants
- Locations
- Delivery Agents
- Menu Items
- Orders

## Key Concepts Implemented

- Data ingestion and transformation
- Incremental data loading
- Data quality and validation
- Delta table management
- Medallion Architecture
- Data pipeline development

## Project Outcome

Built a structured data pipeline that transforms raw food delivery data into curated datasets suitable for analytics and reporting.


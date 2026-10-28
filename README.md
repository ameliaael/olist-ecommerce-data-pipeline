# Olist E-Commerce Data Engineering Pipeline

An end-to-end data engineering project exploring Brazilian e-commerce data using a Medallion Architecture.

## Project Overview

This project transforms raw Olist e-commerce datasets into structured, analytics-ready tables. It focuses on data ingestion, transformation, data quality validation, and preparing data for downstream analysis and visualisation.

## Architecture

**Bronze → Silver → Gold**

- **Bronze:** Ingest raw datasets into the data platform.
- **Silver:** Clean and validate records, handle data quality issues, and prepare consistent datasets.
- **Gold:** Build analytical tables to support business analysis and reporting.

## Tech Stack

- **Databricks**
- **PySpark**
- **SQL**
- **Delta Lake**
- **Tableau** for visualisation

## Data Quality

The project explores data quality issues including:

- Missing and duplicate keys
- Invalid prices and payment values
- Unexpected order statuses
- Orphaned order items
- Missing entity references
- Incomplete geographic information

Validation checks help identify data issues before downstream analysis.

## Analytical Goals

The transformed datasets support exploration of e-commerce operations, including:

- Order and payment patterns
- Customer and seller relationships
- Product and order-item data
- Geographic distribution of customers
- Data quality and consistency across related datasets

## Repository Contents

- `Olist 13_48_13.ipynb` — project notebook containing the pipeline implementation.

## What I Learned

This project strengthened my understanding of:

- Building multi-stage data pipelines
- Applying Medallion Architecture
- Transforming data with PySpark and SQL
- Identifying and validating data quality issues
- Preparing structured datasets for analytics

## Future Improvements

- Automate pipeline execution and monitoring
- Expand automated data quality testing
- Improve incremental processing and recovery
- Document data lineage and transformation logic

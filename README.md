# Healthcare Claims ETL Pipeline with PySpark
Gcp bigquery pipeline for US healthcare domain.Practice for GCP Data Engineer roles (BigQuery, Dataproc ready),Mirrors real-world Facets 837/834 processing.

## Overview
Built a scalable ETL pipeline using PySpark for processing healthcare claims data (similar to Trizetto Facets claims modules). 
Demonstrates data ingestion, cleaning, transformations, aggregations, and output to Parquet — ready for cloud deployment on GCP Dataproc or Dataflow.

## Technologies
- PySpark (DataFrames, Spark SQL)
- Python
- Healthcare domain focus (claims, provider, enrollment style data)

## Features
- Load CSV data
- Handle nulls and clean data
- Aggregations (e.g., average claim amount by state/provider)
- Joins with provider data
- Write output as Parquet

## How to Run
1. Install pyspark: `pip install pyspark`
2. python healthcare_etl.py

## Screenshots
[Add output screenshots here]

## Next Steps
Planning to deploy on GCP BigQuery + Cloud Composer.

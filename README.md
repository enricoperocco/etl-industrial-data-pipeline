# ETL Industrial Data Pipeline

This project implements a simple ETL (Extract, Transform, Load) pipeline to process industrial and manufacturing datasets.

The goal is to simulate real-world data engineering workflows used in Industry 4.0 environments, transforming raw production data into structured datasets that can support analytics and decision-making.

## Technologies

- Python
- Pandas
- SQL
- Databricks concepts
- ETL pipelines

## Project Structure
data/
raw_data.csv
processed_data.csv

scripts/
extract.py
transform.py
load.py

notebooks/
etl_analysis.ipynb

## Pipeline Steps

1. **Extract**
   - Load raw production data
   - Validate schema and missing values

2. **Transform**
   - Clean inconsistent records
   - Normalize industrial measurements
   - Aggregate production KPIs

3. **Load**
   - Store processed data into structured datasets
   - Prepare tables for analytics workflows

## Use Case

Industrial environments generate large amounts of operational data.  
This pipeline demonstrates how raw machine and production data can be transformed into usable datasets for analytics and monitoring.

## Author

Enrico Perocco  
Systems & Data Engineer

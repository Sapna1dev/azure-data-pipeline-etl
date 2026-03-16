# Azure Data Pipeline ETL Project

## Project Overview
This project demonstrates building a data pipeline using Azure Data Factory to perform ETL (Extract, Transform, Load) operations.  
The pipeline processes raw datasets, performs transformations, and loads structured data into a SQL database for reporting and analytics.

## Tools & Technologies
- Azure Data Factory
- Azure SQL Database
- Azure Storage Account
- SQL
- Data Pipeline / ETL Architecture

## Project Workflow

### 1. Data Extraction
Raw datasets were stored in Azure Storage and ingested using Azure Data Factory pipelines.

### 2. Data Transformation
Data transformations were performed to:
- Clean inconsistent values
- Convert data types
- Remove invalid records
- Prepare structured data for analysis

### 3. Data Loading
The transformed data was loaded into Azure SQL Database where it can be queried for reporting and analytics.

### 4. Data Validation
Pipeline execution was validated using Azure Data Factory monitoring tools to ensure successful data movement and transformation.

## Key Features
- Automated ETL pipeline
- Scalable cloud-based data processing
- Structured data storage for analytics
- Integration between Azure services

## Business Value
This pipeline enables organizations to:
- Process large datasets efficiently
- Automate data workflows
- Store cleaned and structured data for analysis and reporting

## Future Improvements
- Schedule automated pipeline runs
- Add additional data transformations
- Integrate dashboards for reporting

## Author
Sapna Gondaliya  
MS Data Science – Boston University

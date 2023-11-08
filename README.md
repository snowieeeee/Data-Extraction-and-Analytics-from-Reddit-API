# Data-Extraction-and-Analytics-from-Reddit-API

## Project Overview
This project involves a comprehensive data pipeline:

- Data extraction is performed using the Reddit API.
- Data is loaded into Amazon Web Services (AWS) S3 for storage.
- Data transformation is achieved using dbt.
- Data is copied into AWS Redshift for analysis.
- A dashboard is created using Looker Studio for data visualization.
- Orchestration of the pipeline is handled with Airflow in Docker containers.
- Terraform is used to provision AWS resources required for the project.

## Data Pipeline 
Below is a visualization of the data pipeline:

![Data Pipeline](https://github.com/snowieeeee/Data-Extraction-and-Analytics-from-Reddit-API/blob/main/pipeline.png)


# ModaStyle - Batch Data Engineering Project 
## Overview 
ModaStyle is a retail analytics data engineering project that processes batch data from multiple sources (CSV, JSON, API, SQL) into a medallion lakehouse architecture on Azure using ADF, ADLS, Databricks, Azure SQL, and Power BI. 
 
## Tech Stack 
- Azure Data Factory (orchestration) 
- Databricks (PySpark + Delta) 
- ADLS Gen2 (data lake) 
- Azure SQL / Synapse (serving) 
- Power BI (reporting) 
 
## Architecture 
Medallion design with Raw  Bronze  Silver  Gold layers following best practices for batch data pipelines. 
 
## Goals 
- End-to-end batch pipeline 
- Data modeling (star schema) 
- CI/CD with GitHub Actions 
- Power BI dashboard with KPIs 
 
## Author 
Parth Bhavthankar 

# Indian_Tech_Job_Market_2026_Analysis
Production-style Azure Data Engineering project demonstrating data ingestion, transformation, orchestration and reporting using Synapse Analytics, Medallion Architecture, Power BI dashboards.


# Azure Synapse End-to-End Data Engineering Project – Job Market Analytics

##  Project Overview

This project is an end-to-end **Azure Data Engineering solution** built using real-world job posting data (23,000+ records, 32 columns).  
It demonstrates how raw unstructured job data can be transformed into a structured analytics-ready model using **Azure Synapse Analytics, ADLS Gen2, SQL, and Power BI**.

The goal is to analyze **job market trends in Data Science and AI roles**, including salary insights, hiring demand, Salary Disclosure Analysis,Startup vs Enterprise Comparison,Remote Work Analysis and company behavior.

---

##  Architecture

The project follows the **Medallion Architecture (Bronze → Silver → Gold)** using Synapse:

Bronze Layer → Raw data ingestion from CSV into ADLS Gen2  
Silver Layer → Data cleaning, transformation, and feature engineering using Synapse SQL    
Gold Layer → Business-ready star schema using Synapse SQL  

---

##  Tech Stack

- Azure Data Lake Storage Gen2 (ADLS)
- Azure Synapse Analytics
- Synapse Pipelines
- Apache Spark (Synapse Notebooks)
- Synapse SQL (Serverless)
- Power BI

---

##  Pipeline Flow

1. Raw CSV uploaded to ADLS (Bronze)
2. Synapse Pipeline triggers ingestion workflow Copy Data Activity
3. Synapse SQL   performs:
   - Data cleaning
   - Missing value handling
4. Cleaned data stored in Silver layer (Parquet format)
5. Synapse SQL Analysis and Create Required attributes:
6. Gold layer prepared for reporting
7. Power BI dashboards 

---

## 📊 Business Objectives

This project answers key business questions:

- Hiring demand across roles, cities, and company sizes  
- Salary trends by role, location, and company  
- Impact of company rating on hiring patterns  
- Remote vs onsite job distribution  
- Startup vs enterprise hiring behavior  
- Salary transparency across companies  


## 🚀 Setup Instructions

### 1. Prerequisites
- Azure Subscription
- Azure Synapse Workspace
- ADLS Gen2 Storage Account
- Power BI Desktop
---
## Trigger 
  Run Pipeline

---
### 2. Pipeline Execution
---
  Ingestion_Pipeline
  ```
- This will:
  - Trigger Spark notebook
  - Create Silver layer
  - Load External tables

---

### 4. SQL Layer
Run scripts in `/sql` folder:

- Load Gold layer

---

#### 5. Power BI
- Connect Power BI to Synapse SQL endpoint
- Load Gold Tables
- Build dashboards

---

##  Key Features

- Medallion architecture implementation
- End-to-end Synapse pipeline orchestration
- Scalable ETL design using Synapse
- Business-ready Power BI dashboards
- Real-world job market analytics

---

##  Key Learnings

- Designing Azure-based data pipelines
- Handling messy real-world CSV data
- Building ETL workflows using Synapse
- Integrating Synapse  + Power BI

---

## 👨‍💻 Author

**MINNU LATHIKA**  
Azure Data Engineer Project  

---

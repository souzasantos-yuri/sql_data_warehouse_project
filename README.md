# 🏗️ Data Warehouse and Analytics Project
 
Data warehouse built with Medallion Architecture (Bronze / Silver / Gold), consolidating sales data from ERP and CRM sources into a star schema ready for reporting and analytics.
 
---
 
## 🎯 Objective
 
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making. The project covers:
 
- Data Architecture using Medallion Architecture (Bronze / Silver / Gold)
- ETL Pipelines in SQL to ingest, clean, and transform data
- Data modeling with star schema, fact and dimension tables
- Analytical SQL queries to support reporting and business intelligence
- Data quality checks and test scripts for validation
- Documentation: data catalog, schema diagrams, naming conventions
 
---
 
## 🛠️ Technologies
 
| Technology | Use |
|---|---|
| SQL Server (T-SQL) | Database and ETL scripting |
| Medallion Architecture | Bronze / Silver / Gold layering |
| Star Schema | Dimensional data modeling |
| CSV Files | Data sources (ERP and CRM) |
 
---
 
## 🗂️ Structure
 
```
sql_data_warehouse_project/
├── datasets/                   # Raw datasets (ERP and CRM)
├── docs/
│   ├── data_architecture.png   # Architecture diagram
│   ├── data_catalog.md         # Field descriptions and metadata
│   ├── data_flow.png           # Data flow diagram
│   └── data_models.png         # Star schema diagram
├── scripts/
│   ├── bronze/                 # Raw data ingestion
│   ├── silver/                 # Cleaning and transformation
│   └── gold/                   # Analytical models
└── tests/                      # Data quality and validation scripts
```
 

## Azure Data Factory – Orders ETL Pipeline

### Overview
End-to-end ETL pipeline built using **Azure Data Factory** for a fictional e-commerce orders system. The solution ingests data into a data lake and processes it through **Landing, Raw, Cleansed, Structured, and Analytics** layers using modular pipelines and Mapping Data Flows.

The project focuses on production-style design, schema standardization, and analytics-ready outputs.


### Architecture
- **Landing → Raw**: Source ingestion using Copy activities  
- **Raw → Cleansed**: Data type casting, renaming, and null handling  
- **Cleansed → Structured**: Joins, derived columns, and business entities  
- **Structured → Analytics**: Monthly aggregations for reporting  

A master pipeline orchestrates the full end-to-end flow.


### Key Components
- Azure Data Factory pipelines for orchestration  
- Mapping Data Flows for transformations (casts, joins, filters, aggregates)  
- Layered data lake design  
- Parameterized and reusable datasets  


### Repository Contents
- **ARM templates** defining pipelines, datasets, data flows, and triggers  
- **Architecture screenshots** showing pipeline orchestration and transformations  


### Technologies
- Azure Data Factory  
- Azure Data Lake Storage  
- Mapping Data Flows  
- ARM Templates (Infrastructure as Code)

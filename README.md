**Overview**

This project focuses on building a comprehensive SQL-based analytics pipeline. It uses a layered data architecture (Bronze → Silver → Gold) to ingest, cleanse, transform, and analyze customer, product, and sales data. The project supports analytics and reporting by preparing structured and quality-assured datasets in the Gold layer.

**Technologies Used**

SQL Server: Used for hosting and restoring the data warehouse

T-SQL: For data transformations, cleansing, and analysis

CSV Files: Used as source input and for exporting final results

Dimensional Modeling: To organize data into fact and dimension tables

**Setup Instructions**

Restore the DataWarehouseAnalytics.bak backup in SQL Server Management Studio (SSMS).

Review and run transformation logic using provided CSV files to simulate ETL pipelines.

Use the gold/ CSVs to query report-ready data such as:

Customer-level insights

Product-level sales summaries

Fact and dimension data for dashboards

**Data Layers Description**

Bronze: Raw data directly extracted from CRM and ERP systems

Silver: Filtered, cleaned, and combined data ready for further transformation

Gold: Final output used for reporting, KPIs, and business intelligence

**Project Goal**

To build a scalable and maintainable analytics data pipeline that integrates disparate data sources and provides actionable insights through structured reporting layers.

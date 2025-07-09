# 📊 Data Warehouse and Analytics Project

Welcome to the Data Warehouse and Analytics Project repository! 🚀
This project presents a complete data warehousing solution, following industry best practices from raw data ingestion to business-ready data modeling. This project integrates CRM and ERP datasets into a centralized data platform following a layered architecture: Bronze, Silver, and Gold.

### 🎯 Objectives

- Integrate CRM and ERP datasets into a centralized data warehouse
- Build a layered ETL pipeline using SQL Server and T-SQL stored procedures
- Implement the Medallion Architecture: Bronze (Raw), Silver (Cleaned), Gold (Business-Ready)
- Apply dimensional modeling using a star schema for efficient querying
- Maintain traceability and clarity through naming standards and documentation
- Deliver a modular, maintainable, and scalable data warehousing solution

### 🛠️ Tech Stack

- Database: Microsoft SQL Server
- ETL Development: T-SQL Stored Procedures
- Architecture: Medallion-style (Bronze → Silver → Gold)
- Tools: SQL Server Management Studio (SSMS), Git
- Modeling Technique: Star Schema

### 🧱 Layered Architecture

🔹 Bronze Layer
Raw import of source CSV files (CRM and ERP)
Minimal transformations for historical accuracy

🔸 Silver Layer
Standardized, cleaned, and validated data
Business rules applied for enriched attribute values

⭐ Gold Layer
Final star schema for business consumption
Includes: dim_customers, dim_products, fact_sales

### 🧩 Key Features
- End-to-End ETL pipeline using Truncate-Insert logic
- Centralized data cleansing and transformation rules
- Integrated CRM + ERP model for unified reporting
- Clear data lineage and naming conventions
- Ready-to-query views for analytics and BI tools

### ▶️ How to Use

- Clone this repository
- Run SQL scripts in order: Bronze → Silver → Gold
- Explore the resulting views
- Run SQL scripts for analytics


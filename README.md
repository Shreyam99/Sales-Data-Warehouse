# Sales Data Warehouse & Analytics

A modern sales data warehouse built using **Microsoft SQL Server and T-SQL**, following a **Bronze, Silver and Gold layered architecture** for data ingestion, transformation, cleaning and analytics.

## Project Overview

This project demonstrates the development of an end-to-end data warehouse for sales data. Raw data is loaded into the Bronze layer, cleaned and transformed in the Silver layer, and organized into analytics-ready views in the Gold layer.

## Architecture

### Bronze Layer
Stores raw data from CRM and ERP source systems with minimal transformation.

### Silver Layer
Cleans, standardizes and transforms the raw data to improve data quality and consistency.

### Gold Layer
Provides business-ready data using fact and dimension views following a **Star Schema** for reporting and analysis.

## Technologies Used

- Microsoft SQL Server
- T-SQL
- SQL Server Management Studio (SSMS)
- ETL
- Data Warehousing
- Data Modeling
- Star Schema

## SQL Concepts Used

- SQL Joins
- Aggregations
- CTEs
- Subqueries
- Window Functions
- Data Cleaning
- Data Quality Checks
- Views

## Project Structure

```text
Sales-Data-Warehouse/
│
├── datasets/
├── docs/
├── scripts/
│   ├── init_database.sql
│   ├── bronze/
│   │   ├── ddl_bronze.sql
│   │   └── proc_load_bronze.sql
│   ├── silver/
│   │   ├── ddl_silver.sql
│   │   └── proc_load_silver.sql
│   └── gold/
│       └── ddl_gold.sql
│
└── tests/

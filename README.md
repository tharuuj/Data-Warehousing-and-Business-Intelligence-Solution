# Data-Warehousing-and-Business-Intelligence-Solution
DW &amp; BI solution using the Olist Brazilian e-commerce dataset


#### Dataset
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

This project demonstrates a complete Data Warehousing and Business Intelligence (DW & BI) solution built using the Olist Brazilian E-Commerce Public Dataset from Kaggle. The project covers the full pipeline — from raw data extraction to analytical reporting — for a real-world e-commerce scenario

▪️Source Data: Over 100,000 records of real transactional data from Olist’s Brazilian marketplace, covering customers, orders, products, payments, sellers, and reviews.

▪️ETL Process: Designed and implemented with SQL Server Integration Services (SSIS). Raw CSV files and Text files are staged, cleaned, transformed, and loaded into a structured star schema.

▪️Data Warehouse: A star schema with a central fact table (fact_order_items) and supporting dimension tables for customers, products, sellers, and dates. Slowly Changing Dimensions (SCD Type 2) are used to track changes over time.

▪️Analytics & Reporting: The final data warehouse supports downstream reporting using Power BI and SSAS cubes, enabling interactive dashboards, KPIs, and drill-down analytics
for business insights.

▪️Real-World Complexity: Handles raw OLTP data with no pre-defined models — the project includes surrogate keys, SCD logic, aggregations, and performance optimizations.

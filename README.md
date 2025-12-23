# Azure_Databricks_ETL_Pipelines

This project implements an end-to-end retail analytics data pipeline on Azure using the **Medallion Architecture** (Bronze, Silver, Gold).

Raw data from five CSV files (**Sales, Products, Customers, Stores, and Date**) is ingested into **Azure Data Lake Storage Gen2** using **Azure Data Factory**.

Data is cleaned, transformed, and enriched using **SQL in Azure Databricks**.

A **Star Schema data model** is created in **Azure Data Lake Storage Gen2** and processed using **Azure Databricks**, with orchestration handled by **Azure Data Factory**.

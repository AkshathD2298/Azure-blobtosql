# Azure Data Factory: Blob Storage to Azure SQL Database Pipeline

## Project Overview
This project demonstrates building an Azure Data Factory pipeline to copy sales data stored as CSV files in Azure Blob Storage into an Azure SQL Database table for further analytics.

## Architecture
- Data stored in Blob Storage
- ADF pipeline extracts and optionally transforms data
- Data loaded into Azure SQL Database

## Features
- Linked Services for Blob Storage and Azure SQL
- Copy activity with column mapping
- Optional Data Flow for data cleansing
- Pipeline debugging and scheduling

## Setup
1. Create Azure Blob Storage and upload sales CSV files
2. Create Azure SQL Database and execute `sql/create_sales_table.sql`
3. Import linked services, datasets, and pipeline into Azure Data Factory (JSON files provided)
4. Test and schedule pipeline

## Technologies
- Azure Data Factory
- Azure Blob Storage
- Azure SQL Database
- SQL
- ARM Templates (optional)

## Author
Akshath Dsouza  
[LinkedIn](https://www.linkedin.com/in/akshathdsouza) | [GitHub](https://github.com/AkshathD2298)

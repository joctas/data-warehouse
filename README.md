# Data Warehouse Project  
A data warehouse built with SQL Server, including ETL processes, data modeling, and analytics.

## Data Architecture

The data architecture for this project follows the Medallion Architecture with **Bronze**, **Silver**, and **Gold** layers:

1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV files into a SQL Server database.  
2. **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.  
3. **Gold Layer**: Contains business-ready data modeled into a star schema, required for reporting and analytics.

## Project Requirements

### Building the Data Warehouse (Data Engineering)

#### Objective  
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications  
- **Data Sources**: Import data from two source systems (ERP and CRM), provided as CSV files.  
- **Data Quality**: Clean and resolve data quality issues before analysis.  
- **Integration**: Combine both sources into a single, user-friendly data model optimized for analytical queries.  
- **Scope**: Focus on the latest dataset only; data historization is not required.  
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

---

### BI: Analytics & Reporting (Data Analysis)

#### Objective  
Develop SQL-based analytics to deliver detailed insights into:  
- **Customer Behavior**  
- **Product Performance**  
- **Sales Trends**

These insights empower stakeholders with key business metrics, enabling strategic decision-making.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

## About Me

Hi! I'm **João Octávio** — a CS student and English teacher who has fallen in love with Data Engineering.

Let's stay in touch! Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/joaoctaviosantiago/).

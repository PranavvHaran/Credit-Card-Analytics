# Credit-Card-Analytics
End-to-end fraud &amp; risk analytics on 500K+ credit card transactions using Snowflake, SQL (star schema, stored procedures), and Power BI dashboards.

## Project Overview

This project demonstrates an end-to-end Credit_Card_Analytics using Snowflake, SQL, and Power BI. The objective was to transform raw banking transaction data into a business-ready data warehouse using Kimball dimensional modeling and build interactive dashboards for fraud detection and business insights.

The project covers data cleaning, star schema design, business views, analytical SQL, and dashboard development.

---

## Business Problem

Financial institutions process millions of transactions every day, making fraud detection a critical challenge.

This project aims to:

- Build a scalable analytical data warehouse
- Analyze customer spending behavior
- Identify fraudulent transactions
- Monitor merchant performance
- Track transaction trends over time
- Enable business reporting through Power BI

---

## Tech Stack

| Tool | Purpose |
|------|----------|
| Snowflake | Cloud Data Warehouse |
| SQL | Data Cleaning & Analytics |
| Power BI | Dashboard & Reporting |
| Git | Version Control |
| GitHub | Project Repository |

---

##  Project Workflow

Raw Dataset

↓

Data Cleaning

↓

Clean Transactions Table

↓

Dimension Tables

- Dim Date
- Dim Customer
- Dim Merchant
- Dim Category

↓

Fact Transactions

↓

Business Views

↓

Power BI Dashboard

---

## Data Warehouse Design

The project follows the **Kimball Star Schema** approach.

### Fact Table

- FACT_TRANSACTIONS

### Dimension Tables

- DIM_DATE
- DIM_CUSTOMER
- DIM_MERCHANT
- DIM_CATEGORY

---

## Business Views

The following business views were created:

- VW_FRAUD_TRANSACTIONS
- VW_CUSTOMER_SPENDING
- VW_CATEGORY_ANALYSIS
- VW_MERCHANT_ANALYSIS
- VW_MONTHLY_TRANSACTION_SUMMARY

These views simplify reporting and serve as the data source for business analytics.

---

## Dashboard Highlights

The Power BI dashboard provides insights into:

- Total Transactions
- Total Revenue
- Fraud Rate
- Customer Spending Analysis
- Merchant Performance
- Monthly Transaction Trends
- Category-wise Performance

---

## Repository Structure

```

Credit-Card-Analytics

│

├── SQL/
│ ├── 01_Database_Setup.sql
│ ├── 03_Create_Table.sql
│ ├── 03_Load_Table.sql
│ ├── 04_Data_Validation.sql
│ ├── 05_Data_Cleaning.sql
│ ├── 06_Data_Cleaning_Clean_Transaction.sql
│ ├── 07_Dim_Date.sql
│ ├── 08_Dim_Category.sql
│ ├── 09_Dim_Customer.sql
│ ├── 10_Dim_Merchant.sql
│ ├── 11_Fact_Transactions.sql
│ ├── 12_Views.sql

│

├── PowerBI/
├── DAX Measures_01.png
├── Dashboard_01.png
├── Data Modeling_01.png

│

├── Images/

│ ├── Star_Schema.png

│ ├── Dashboard.png

│ └── Architecture.png

│

└── README.md

```

---

## SQL Concepts Used

- Data Cleaning
- Data Validation
- ETL
- CTEs
- Window Functions
- Aggregate Functions
- Views
- Star Schema
- Fact & Dimension Modeling

---

## Future Enhancements

- Automated ETL Pipeline
- Incremental Data Loading
- dbt Transformations
- Apache Airflow Scheduling
- Real-time Fraud Detection
- Cloud Data Pipeline Integration

---

## Author

**Pranav Haran**
Linkedin: *(linkedin.com/in/pranavv-haran)*


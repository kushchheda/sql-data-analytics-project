# Data Analytics Project

Welcome to my Data Analytics Project repository! 🚀

This is **Part 2** of my **Microsoft SQL Server** project series.

This project demonstrates a comprehensive data analytics solution. Designed as a portfolio project, it highlights industry best practices in data analytics.

---
## 🏗️ Data Architecture

The data architecture for this project follows the Part 1 Medallion Architecture **Bronze**, **Silver**, and **Gold** layers:
![Data Architecture](docs/data_architecture.png)

1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.

---
## 📖 Project Overview

This project involves:

**Analytics & Reporting**: Creating SQL-based reports and dashboards for actionable insights.

🎯 This 2-part repository is an excellent resource for people looking to showcase expertise in:
- SQL Development
- Data Architect
- Data Engineering  
- ETL Pipeline Developer  
- Data Modeling  
- Data Analytics  

---

## 🚀 Project Requirements

### BI: Analytics & Reporting (Data Analytics)

#### Objective
Develop SQL-based analytics to deliver detailed insights into:
- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

These insights empower stakeholders with key business metrics, enabling strategic decision-making.

---

## 📂 Repository Structure
```
data-warehouse-project/
│
├── datasets/                           # Prepared Medallion data from Project Part 1
│
├── docs/                               # Project documentation (view in order)
│   ├── Project Roadmap.png             # Shows the scope of our project analysis
│   ├── data_architecture               # (1) This file shows the project's high-level architecture
│   ├── data_model                      # (2) This file shows the final data model (star schema)
│
├── scripts/                            # All SQL scripts for initializing database and Project Roadmap
│
├── LICENSE                             # License information for the repository
└── README.md                           # Project overview and instructions
```
---

## 🛡️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

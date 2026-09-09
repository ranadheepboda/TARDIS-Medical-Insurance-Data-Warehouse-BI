# 🏥 TARDIS – Medical Insurance Data Warehouse & BI

## 📌 Project Overview

TARDIS is a Medical Insurance Data Warehouse and Business Intelligence project designed to integrate, transform, validate, and analyze healthcare insurance data.

The project demonstrates an end-to-end data analytics workflow using **SQL Server, T-SQL, SSIS, SSAS, and Power BI**.

---

## 🎯 Business Objective

The primary objective of this project is to build a centralized data warehouse and BI solution that enables:

- Medical insurance policy analysis
- Claims analysis
- Customer and policyholder analysis
- Healthcare trend analysis
- Business KPI reporting
- Interactive management dashboards
- Automated and scheduled reporting

---

## 🏗️ Data Warehouse Architecture

The project follows a dimensional data warehouse approach using a **Snowflake Schema**.

### Data Flow

```text
Source Systems
     ↓
SQL Server / Excel / Flat Files
     ↓
SSIS ETL
     ↓
Staging Tables
     ↓
Data Validation & Transformation
     ↓
Data Warehouse
     ↓
SSAS Model
     ↓
Power BI
     ↓
Business Dashboards & Reports

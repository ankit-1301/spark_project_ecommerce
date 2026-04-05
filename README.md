# 🛒 ShopVista Data Modernization Project

## 📌 Overview
ShopVista, a fast-growing e-commerce company, faced challenges due to fragmented data across multiple systems (orders, shipments, returns, and dimension tables). This led to manual reconciliation, delayed reporting, and limited visibility.

This project builds a centralized, automated data platform on Microsoft Azure, enabling a single source of truth for analytics and reporting.

---

## 🎯 Objectives
- Unify all key datasets (orders, shipments, returns, dimensions)
- Automate data ingestion, transformation, and aggregation
- Implement Medallion Architecture (Bronze → Silver → Gold)
- Enable real-time insights using Power BI dashboards

---

## 🏗️ Architecture
```
Source Files → ADLS (Bronze) → Databricks (Silver) → Gold Layer → Power BI
```

### Tech Stack:
- Azure Data Lake Storage Gen2 (ADLS)
- Azure Databricks
- PySpark / SQL
- Power BI

---

## ⚙️ Scope of Work

### 🔹 1. Data Architecture & Setup
- Configured ADLS Gen2 for centralized storage
- Set up Databricks for data processing
- Implemented Bronze, Silver, Gold layer structure

---

### 🔹 2. Data Ingestion (Bronze Layer)
- Automated daily ingestion pipelines
- Loaded raw datasets (orders, shipments, returns)
- Implemented ingestion tracking & error handling

---

### 🔹 3. Data Transformation (Silver Layer)
- Schema enforcement and validation
- Data cleaning (null handling, deduplication)
- Ensured referential integrity across datasets

---

### 🔹 4. Data Modeling (Gold Layer)
- Created fact tables:
  - Orders
  - Shipments
  - Returns
- Integrated dimension tables:
  - Customers, Products, Categories, Brands, Date
- Designed Star Schema for analytics
- Optimized tables for Power BI

---

### 🔹 5. Reporting & Visualization
Developed Power BI dashboards for:
- Sales by Brand, Category, Country  
- Monthly Revenue Trends  
- Return Analysis by Product & Category  

- Implemented role-based access
- Enabled automated data refresh

---

## 📦 Deliverables

| Category        | Description |
|----------------|------------|
| Data Pipeline  | Automated daily ingestion into Bronze layer |
| Data Quality   | Cleaned & validated datasets in Silver layer |
| Data Warehouse | Gold layer with fact & dimension tables |
| Visualization  | Power BI dashboards |

---

## 🚀 Outcomes
- Eliminated manual data consolidation
- Reduced reporting time from hours → minutes
- Established a single source of truth
- Enabled real-time, data-driven decisions
- Built scalable data foundation

---

## ⏱️ Timeline
**Estimated Duration:** 6–8 Weeks  

Phases:
1. Setup & Architecture  
2. Data Ingestion  
3. Transformation & Validation  
4. Data Modeling  
5. Dashboard Development  

---

## ⚠️ Assumptions
- Source data is consistently available
- Azure & Power BI access is provisioned
- Business team provides reporting requirements

---

## 📌 Future Enhancements
- Real-time streaming pipelines  
- Advanced analytics & forecasting  
- Data quality monitoring dashboards  

---

## 👨‍💻 Author
**Ankit**  
Data Engineer  

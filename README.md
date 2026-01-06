# Power BI Power Query – Sales Data Cleaning and Transformation Project

## 📌 Project Overview
This project demonstrates hands-on experience using **Power BI Power Query** to clean, transform, and prepare **complex, unstructured raw sales data** spread across **multiple CSV files**.  
The work reflects real-world data challenges where datasets are messy, inconsistent, and require careful preprocessing before analysis.

---

## 📂 Dataset Description
- Multiple raw CSV files:
  - Customers
  - Products
  - Stores
  - Transactions (1997 & 1998)
  - Returns
- Approximately **200,000+ rows of raw data** across files
- Common data issues:
  - Missing values and nulls
  - Incorrect and inconsistent data types
  - US vs Indian date format inconsistencies
  - Duplicate records
  - Disconnected tables requiring joins

---

## 🛠 Tools & Technologies
- **Power BI Desktop**
- **Power Query Editor**
- ETL & Data Transformation Concepts

---

## 1️⃣ Data Ingestion & Exploration
**Objective:** Understand data structure, scale, and quality before cleaning.

- Imported **multiple raw CSV files** (Customers, Products, Stores, Transactions, Returns) into Power BI
- Worked with **200,000+ rows of unstructured raw data** across files
- Reviewed schemas, column names, and key identifiers
- Used **Column Quality, Column Distribution, and Column Profiling** to identify:
  - Missing and null values
  - Data type inconsistencies
  - Duplicate records
  - Invalid and error-prone fields

**Outcome:** Identified critical data quality issues and transformation requirements.

---

### 2️⃣ Data Cleaning & Transformation
**Objective:** Convert messy raw data into clean, consistent, and reliable datasets.

- Standardized data types across all tables
- Fixed **US vs Indian date format issues** using *Change Type → Using Locale*
- Handled missing and null values appropriately
- Removed duplicate records using distribution analysis
- Standardized categorical fields (Yes/No, Married/Single)
- Created calculated columns:
  - **Sales** = Quantity × Retail Price
  - **Cost** = Quantity × Cost Price
  - **Profit** = Sales − Cost
  - **Return Amount** = Quantity × Retail Price

**Outcome:** Cleaned and standardized datasets with accurate business metrics.

---

### 3️⃣ Data Integration & Analytics Preparation
**Objective:** Prepare structured datasets ready for reporting and dashboards.

- **Appended** multi-year transaction data (1997 & 1998) into a single fact table
- **Merged** fact data with dimension tables (Products, Customers, Stores) using key columns
- Validated unique identifiers (Customer ID, Product ID, Store ID)
- Structured final **fact and dimension tables**
- Prepared datasets for Power BI reporting and visualization
**Outcome:** Analytics-ready data model suitable for dashboards and business insights.

---

## 📊 Output
- Clean, structured **fact and dimension tables**
- Data prepared for Power BI reporting and dashboard creation

---


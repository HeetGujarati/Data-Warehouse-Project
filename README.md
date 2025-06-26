# 🧠 Data Warehouse Project

Welcome to the **Data Warehouse Project**!  
This repository showcases a complete data warehousing pipeline using best practices in data modeling, ETL, and reporting. It is designed to help learners and professionals understand how to structure and manage large-scale analytical data systems.

---

## 🏗️ Project Overview

This project is built on the **Medallion Architecture**, which organizes data in layers to improve data quality, reliability, and scalability. It includes:

- Raw data ingestion (Bronze Layer)
- Cleaned and structured data (Silver Layer)
- Business-ready aggregated data (Gold Layer)
- Consumption for BI tools (Consume Layer)

---

## 🪙 Medallion Architecture Explained

The **Medallion Architecture** breaks the data flow into three main layers:

### 🟫 Bronze Layer (Raw)
- Stores raw, unprocessed data exactly as ingested from the source.
- Acts as a historical record of source data.
- Minimal transformations applied.
- Example: Original CSV/JSON files, logs, raw API outputs.

### 🟪 Silver Layer (Cleansed)
- Performs data cleaning, type casting, joins, and normalization.
- Adds structure and quality checks.
- Used by analysts and developers for further transformations.

### 🟨 Gold Layer (Aggregated)
- Contains business-level metrics and KPIs.
- Optimized for performance and reporting.
- Tables are usually in dimensional models (Star/Snowflake).

---

## 📊 DWH Consume Layer (Consumption)

The **Consume Layer** refers to the part of the Data Warehouse that directly serves the end users — typically dashboards, reports, or data extracts. This is also called the **Presentation Layer** or **Semantic Layer**.

### Features:
- Uses data from the Gold Layer (aggregated and business-ready).
- Serves **BI tools** like Power BI, Tableau, or Looker.
- Designed for speed, usability, and business interpretation.
- Contains KPIs, performance indicators, and visual-friendly formats.

> 🔍 Think of the Consume Layer as the bridge between raw data and real-time decisions.

---

## 📁 Repository Structure


# amazon-prime-tv-project
Azure End-to-End ETL Pipeline Project | Azure Data Factory + Databricks + Power BI

# 📺 Amazon Prime TV Shows Data Engineering Project

This is an end-to-end Data Engineering project built using Azure services and Power BI. The goal is to extract, transform, and visualize Amazon Prime TV show data using the medallion architecture.

---

## 🔗 Dataset

- Source CSV: [amazon_prime_titles.csv](https://raw.githubusercontent.com/RutujaKadam95/AzureETLPipeline-AmazonPrimeDataset/main/amazon_prime_titles.csv)

---

## 🛠️ Tech Stack

- **Azure Data Factory** – Ingest data into ADLS Gen2 (Bronze layer)
- **Azure Data Lake Storage Gen2 (ADLS)** – Stores data in Bronze, Silver, and Gold layers
- **Azure Databricks** – Transforms and cleans data (Silver & Gold layers)
- **Power BI** – Visualizes the final data from Gold layer

---

## 🧱 Medallion Architecture

1. **Bronze Layer** – Raw data from source ingested using Data Factory.
2. **Silver Layer** – Cleaned and filtered data using Databricks (handles nulls, duplicates, etc.).
3. **Gold Layer** – Final refined and business-ready data stored in Parquet/Delta format.

---

## 📊 Final Output

The cleaned Gold layer data is connected to **Power BI** for generating insightful reports.

---

## 📌 Summary

This project demonstrates how to build a scalable and production-ready data pipeline using Azure and visualize data with Power BI.


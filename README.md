<h1>📦 Medallion Architecture Pipeline (Bronze → Silver → Gold)</h1>

An end-to-end data engineering pipeline designed and implemented using Azure Databricks, Delta Lake, and Azure Storage, following the Medallion Architecture to transform raw data into high-quality analytics-ready datasets.

<h2>🎯 Step 1: Project Objective</h2>

Build a scalable cloud data pipeline that ingests raw sales data, cleans and transforms it, and outputs analytics-ready datasets for business insights.

This pipeline uses:

• Azure Data Factory – Data ingestion & orchestration

• Azure Databricks (PySpark) – Data transformation

• Delta Lake – Reliable storage with ACID transactions

• Azure Synapse Analytics – Gold layer aggregations

• Power BI – Interactive dashboards

<h3>🧠 Skills Demonstrated</h3>

• Azure Data Factory (ETL pipelines, incremental loading)

• Azure Databricks + PySpark (transformations, Delta Lake)

• Azure Synapse Analytics (Gold layer modelling)

• Medallion Architecture (Bronze → Silver → Gold)

<h2>🏗️ Step 2: Architecture — Medallion Model (Bronze → Silver → Gold)</h2>

<img width="1543" height="891" alt="Image" src="https://github.com/user-attachments/assets/11d253c1-6b68-475e-ac0f-ed03f581398f" />

<h2>🗂️ Step 3: Data Sources</h2>

• Batch Files: CSV (sales, products, customers)

• Dataset Folder: [View Dataset Files](https://github.com/Guptasonu2725/Medallion_Architecture_Pipeline/tree/main/datasets)

<h2>☁️ Step 4: Azure Setup</h2>

• Azure Free Account

• ADLS Gen2 Storage Account

• Azure Databricks Workspace

• Service Principal for secure access

<img width="1673" height="860" alt="Image" src="https://github.com/user-attachments/assets/03a05525-ca53-4bb9-943a-7ebacc4385c4" />

<h2>🥉 Step 5: Bronze Layer — Data Ingestion</h2>

Azure Data Factory pipelines to copy raw data → ADLS Gen2 - Parameterized pipelines for incremental loads

<img width="1919" height="875" alt="Image" src="https://github.com/user-attachments/assets/9a2cd1c1-edf6-4bf2-aa29-e71b6acdfc20" />

<h2>🥈 Step 6: Silver Layer — Data Transformation</h2>

Azure Databricks + Delta Lake used for:

• Data cleaning

• Handling nulls, duplicates, schema enforcement

• Joining multiple datasets

• Writing transformed data as Delta Tables

<img width="1919" height="875" alt="Image" src="https://github.com/user-attachments/assets/7779d133-175b-4fa9-8929-593e19f1476f" />

<h2>🥇 Step 7: Gold Layer — Aggregation & Analytics</h2>

• Azure Synapse Analytics performs:

• Business-level aggregations

• Creation of external tables with OPENROWSET()

• Output ready for BI tools

<img width="1919" height="872" alt="Image" src="https://github.com/user-attachments/assets/adc5ced4-124b-4b4d-a8de-684c046b5a7e" />

<h2>🚀 Step 8: Project Conclusion</h2>

This project showcases a complete cloud data engineering solution using the Medallion Architecture:

🔹 Bronze Layer:

Raw data ingestion through ADF pipelines

🔹 Silver Layer:

Data transformation using Databricks + PySpark

🔹 Gold Layer:

Aggregated business tables using Synapse Analytics

• This architecture ensures scalability, reliability, and performance—ideal for enterprise analytics and Power BI dashboards.

<h2>🧑‍💻 Prepared By</h2>

        Sonu Gupta







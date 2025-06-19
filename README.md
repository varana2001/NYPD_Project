# NYPD Arrest Data Pipeline & Dashboard

A data engineering and analytics project to ingest, model and visualize NYPD Arrest Year-to-Date data using Azure Data Factory, Snowflake, Alteryx, Tableau and Power BI. The project aims to provide insights into crime trends across New York City by location, time, crime type and demographics.

## 🚀 Project Objectives

- Build a dimensional model for arrest analysis
- Design a robust ETL pipeline from raw CSV to Snowflake
- Visualize patterns in crime types, demographics and boroughs using dashboards

## 📊 Tools & Technologies

- Azure Data Factory (ETL pipeline)
- Alteryx (Data profiling & transformation)
- Snowflake (Cloud Data Warehouse)
- Tableau & Power BI (Data visualization)

## 📌 Business Questions Addressed

- What are the top 5 most common arrest charges?
- How do arrest rates vary across boroughs and precincts?
- What is the demographic distribution of arrestees (age, race, gender)?
- Which crime types are increasing or decreasing over time?

## 🛠️ Features

- Robust staging pipeline using ADF + Snowflake
- Data quality checks and profiling via Alteryx
- Logical and physical data models with fact & dimension tables
- Dashboards for time-based, geographic and demographic analysis

## 📁 Project Structure

├── ADF_Pipelines/ # JSON export of Azure pipelines
├── Alteryx_Flows/ # Alteryx profiling/cleaning workflows
├── Snowflake_SQL/ # DDL scripts & staging queries
├── Tableau_Dashboards/ # Tableau packaged workbooks (.twbx)
├── PowerBI_Reports/ # .pbix reports
├── Inference_Document.docx # Dashboard insights & interpretations
└── README.md

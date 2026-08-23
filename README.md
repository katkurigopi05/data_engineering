# 📊 Data Engineering & Cloud Data Warehousing

Welcome to the **Data Engineering & Data Warehousing** repository! This repository serves as a comprehensive collection of coursework, laboratory guides, hands-on assignments, architectural documentations, ETL job designs, and analytical datasets covering core principles of data engineering, dimensional modeling, cloud data warehousing, data integration, and business intelligence.

---

## 📑 Table of Contents
1. [Overview](#-overview)
2. [Core Knowledge Domains](#-core-knowledge-domains)
   - [1. Dimensional Modeling & Schema Design](#1-dimensional-modeling--schema-design)
   - [2. Cloud Data Warehousing (AWS Redshift & Google BigQuery)](#2-cloud-data-warehousing-aws-redshift--google-bigquery)
   - [3. Data Integration & ETL Pipelines (Talend)](#3-data-integration--etl-pipelines-talend)
   - [4. Business Intelligence & Analytics (Tableau)](#4-business-intelligence--analytics-tableau)
3. [Repository Directory & File Map](#-repository-directory--file-map)
4. [Datasets & Data Sources](#-datasets--data-sources)
5. [Prerequisites & Tools Setup](#-prerequisites--tools-setup)
6. [Troubleshooting & Best Practices](#-troubleshooting--best-practices)
7. [Author](#-author)

---

## 🌟 Overview

Modern Data Engineering bridges operational source systems and enterprise analytical reporting. This repository documents end-to-end data workflows, including:
- Designing **Star Schemas** and **Snowflake Schemas** with Fact and Dimension tables.
- Handling **Slowly Changing Dimensions (SCD)**, Step Dimensions, and Super/Subtype Dimension Patterns.
- Provisioning and optimizing **AWS Redshift** clusters (Distribution Keys, Sort Keys, S3 COPY commands).
- Designing **Google BigQuery** data warehouses leveraging partitioned and clustered tables.
- Building robust **ETL/ELT Data Integration Pipelines** using **Talend Open Studio** / Talend Cloud.
- Developing interactive dashboards and advanced data visualizations in **Tableau Desktop**.

---

## 🧠 Core Knowledge Domains

### 1. Dimensional Modeling & Schema Design
- **Concepts**: Business Process Matrix, Grain Definition, Fact Tables (Transaction, Periodic Snapshot, Accumulating Snapshot), Dimension Tables.
- **Advanced Patterns**:
  - Slowly Changing Dimensions (SCD Type 1, Type 2, Type 3).
  - Super/Subtype dimensions, Step dimensions, and Dimension Hierarchies.
- **Key Resources**:
  - [`RN7945_Lab 1_Dimensional Modeling-2U-1.docx`](./RN7945_Lab%201_Dimensional%20Modeling-2U-1.docx) & [`RN7945Assignment 1_Dimensional Modeling.docx`](./RN7945Assignment%201_Dimensional%20Modeling.docx)
  - [`Dimensional Modeling Practice (1).docx`](./Dimensional%20Modeling%20Practice%20(1).docx)
  - [`SCD Practice Questions (1).docx`](./SCD%20Practice%20Questions%20(1).docx)
  - [`Super_Subtype, Step Dimension Practice (2).docx`](./Super_Subtype,%20Step%20Dimension%20Practice%20(2).docx)

### 2. Cloud Data Warehousing (AWS Redshift & Google BigQuery)
- **AWS Amazon Redshift**:
  - Columnar storage architecture, Node types (RA3, Dense Storage/Compute).
  - Data distribution styles (`KEY`, `EVEN`, `ALL`).
  - Compound and Interleaved Sort Keys.
  - High-speed data loading from Amazon S3 via the `COPY` command.
  - Document: [`Cloud Data Warehousing_RedShift-2.docx`](./Cloud%20Data%20Warehousing_RedShift-2.docx)
- **Google BigQuery**:
  - Serverless architecture (Slots, Dremel execution engine).
  - Table Partitioning (by ingestion time or column timestamp/date) and Clustering.
  - Document: [`Cloud Data warehousing_BigQ_v2.docx`](./Cloud%20Data%20warehousing_BigQ_v2.docx)
- **Hands-on Assignments**:
  - [`RN7945_Assignment 3-Cloud DW Assignment_v2 (1).docx`](./RN7945_Assignment%203-Cloud%20DW%20Assignment_v2%20(1).docx)
  - [`Assignment 3-Cloud DW Assignment_v2.docx`](./Assignment%203-Cloud%20DW%20Assignment_v2.docx)

### 3. Data Integration & ETL Pipelines (Talend)
- **Talend Studio & Cloud Integration**:
  - Job creation, context variables, metadata connection management.
  - Components: `tFileInputDelimited`, `tMap`, `tAggregateRow`, `tJoin`, `tPostgresqlOutput`, `tRedshiftOutput`.
  - Data validation, null handling, transformation logic, and error handling.
- **Key Resources**:
  - [`RN7945_Assignment 4-Data Integration-v3 .docx`](./RN7945_Assignment%204-Data%20Integration-v3%20.docx)
  - [`Talend Data Integration Tasks (2).docx`](./Talend%20Data%20Integration%20Tasks%20(2).docx)
  - [`Talend Studio from Cloud (1).docx`](./Talend%20Studio%20from%20Cloud%20(1).docx)

### 4. Business Intelligence & Analytics (Tableau)
- **Tableau Fundamentals & Advanced Visualizations**:
  - Basic charts, bar plots, scatter plots, geographic maps.
  - Advanced calculations, LOD expressions (FIXED, INCLUDE, EXCLUDE), dual-axis charts, parameters, and interactive dashboards.
- **Key Resources**:
  - [`RN7945Lab 2_Tableau Basic-1.pdf`](./RN7945Lab%202_Tableau%20Basic-1.pdf) & [`Lab 2_Tableau Basic-1-2.docx`](./Lab%202_Tableau%20Basic-1-2.docx)
  - [`RN7945_Lab 3_Advanced Tableau.docx`](./RN7945_Lab%203_Advanced%20Tableau.docx) & [`Lab 3_Advanced Tableau (2).docx`](./Lab%203_Advanced%20Tableau%20(2).docx)
  - [`RN7945_Assignment 2_Tableau Analysis (1).docx`](./RN7945_Assignment%202_Tableau%20Analysis%20(1).docx)

---

## 📁 Repository Directory & File Map

| Category | File Name | Description |
| :--- | :--- | :--- |
| **Assignments** | [`RN7945Assignment 1_Dimensional Modeling.docx`](./RN7945Assignment%201_Dimensional%20Modeling.docx) | Assignment 1: Dimensional Modeling & ERD Design |
| | [`RN7945_Assignment 2_Tableau Analysis (1).docx`](./RN7945_Assignment%202_Tableau%20Analysis%20(1).docx) | Assignment 2: Business Analytics & Tableau Dashboards |
| | [`RN7945_Assignment 3-Cloud DW Assignment_v2 (1).docx`](./RN7945_Assignment%203-Cloud%20DW%20Assignment_v2%20(1).docx) | Assignment 3: AWS Redshift & Google BigQuery Implementation |
| | [`RN7945_Assignment 4-Data Integration-v3 .docx`](./RN7945_Assignment%204-Data%20Integration-v3%20.docx) | Assignment 4: Talend ETL Data Integration |
| **Labs** | [`RN7945_Lab 1_Dimensional Modeling-2U-1.docx`](./RN7945_Lab%201_Dimensional%20Modeling-2U-1.docx) | Lab 1: Dimensional Modeling hands-on exercises |
| | [`RN7945Lab 2_Tableau Basic-1.pdf`](./RN7945Lab%202_Tableau%20Basic-1.pdf) | Lab 2: Introduction to Tableau Desktop |
| | [`RN7945_Lab 3_Advanced Tableau.docx`](./RN7945_Lab%203_Advanced%20Tableau.docx) | Lab 3: Advanced Tableau Visualizations & LOD Expressions |
| **Architecture & Guides** | [`Cloud Data Warehousing_RedShift-2.docx`](./Cloud%20Data%20Warehousing_RedShift-2.docx) | Guide to AWS Redshift architecture & loading |
| | [`Cloud Data warehousing_BigQ_v2.docx`](./Cloud%20Data%20warehousing_BigQ_v2.docx) | Guide to Google BigQuery partitioning & performance |
| | [`Common Trouble Shooting...docx`](./Common%20Trouble%20Shooting-%20AWS%20Access%20Key%20ID%20Error%20and%20IAM%20role%20authority%20to%20S3%20bucket%20Error%20Solutions%20(1).docx) | Solutions for AWS IAM role & S3 access key errors |
| | [`Software Download Instruction_v4 (1).docx`](./Software%20Download%20Instruction_v4%20(1).docx) | Environment setup instructions for software tools |
| **Datasets** | [`tickitdb (1).zip`](./tickitdb%20(1).zip) & [`tickitdb-1.zip`](./tickitdb-1.zip) | AWS Redshift TICKIT sample database |
| | [`Sample - Superstore.xlsx`](./Sample%20-%20Superstore.xlsx) | Classic Superstore retail dataset for Tableau analytics |
| | [`DW_DataSets.zip`](./DW_DataSets.zip) | Comprehensive Data Warehousing data package |
| | `Customer`, `Order`, `Product` CSV files | Relational source tables for ETL testing |

---

## 🗄 Datasets & Data Sources

1. **AWS TICKIT Database (`tickitdb.zip`)**:
   - Contains 7 tables representing a sports/event ticketing database: `USERS`, `VENUE`, `CATEGORY`, `DATE`, `EVENT`, `LISTING`, `SALES`.
   - Used for demonstrating Redshift distribution/sort keys and join optimizations.
2. **Superstore Sales (`Sample - Superstore.xlsx`)**:
   - Retail sales order data including Orders, Returns, and People across various regions.
3. **Partitioned Customer & Order CSV Files**:
   - CSV datasets (`Cust_Part1`, `Cust_Part2`, `Cust_Part3`, `CustomerDetail`, `OrderLine`, `Charges`, `Product`) for testing file merging and pipeline staging in Talend.

---

## 🛠 Prerequisites & Tools Setup

- **Database / Data Warehousing**:
  - AWS Account (Amazon Redshift, Amazon S3, AWS IAM)
  - Google Cloud Platform (Google BigQuery)
- **ETL / Integration**:
  - Talend Open Studio for Data Integration (v7.x / v8.x)
- **Business Intelligence**:
  - Tableau Desktop or Tableau Public
- **Spreadsheet / Tools**:
  - Microsoft Excel / LibreOffice for dataset inspection

---

## 🔧 Troubleshooting & Best Practices

- **AWS IAM S3 Access Errors**: Refer to [`Common Trouble Shooting- AWS Access Key ID Error and IAM role authority to S3 bucket Error Solutions (1).docx`](./Common%20Trouble%20Shooting-%20AWS%20Access%20Key%20ID%20Error%20and%20IAM%20role%20authority%20to%20S3%20bucket%20Error%20Solutions%20(1).docx) for step-by-step role trust policy configurations.
- **Redshift COPY performance**: Ensure S3 files are split into multiples of your slice count and compressed using gzip or bzip2.
- **BigQuery Partitioning**: Use partition filters in `WHERE` clauses to avoid full table scans and control query costs.

---

## 👤 Author

- **Gopi Krishna Reddy Katkuri**
- **GitHub**: [@katkurigopi05](https://github.com/katkurigopi05)
- **Repository**: [https://github.com/katkurigopi05/data_engineering](https://github.com/katkurigopi05/data_engineering)
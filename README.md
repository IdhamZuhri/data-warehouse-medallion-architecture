# 📊 Data Warehouse & Analytics Practice Project

Welcome to this repository. This project documents my hands-on learning journey in building a **Data Warehouse and Analytics solution** using SQL Server, based on a guided YouTube tutorial and expanded with my own practice, setup, and implementation.

The purpose of this project is to strengthen practical skills in:

- Data Warehousing
- ETL Development
- SQL Querying
- Data Modeling
- Analytics Reporting
- Git Version Control

---

## 📌 About This Project

I followed a full tutorial project and recreated the entire workflow step-by-step in my own environment, while managing the files, scripts, and progress inside this repository.

Rather than simply copying code, this repo serves as my personal implementation and learning reference to understand how a modern data warehouse is designed and developed.

---

## 🏗️ Data Architecture

This project uses a **Medallion Architecture** approach with three layers:

### 🥉 Bronze Layer
Stores raw source data imported from CSV files into SQL Server.

### 🥈 Silver Layer
Handles cleaning, standardization, transformation, and quality improvements.

### 🥇 Gold Layer
Contains business-ready tables optimized for reporting and analytics using dimensional/star schema design.

---

## ⚙️ Project Scope

The project includes:

- Importing raw data from multiple source systems
- Building ETL pipelines using SQL scripts
- Cleaning and transforming data
- Designing fact and dimension tables
- Running business analysis queries
- Generating insights from customer, product, and sales data

---

## 🛠️ Tools Used

- :contentReference[oaicite:0]{index=0}
- :contentReference[oaicite:1]{index=1}
- :contentReference[oaicite:2]{index=2}
- :contentReference[oaicite:3]{index=3}

---

## 📂 Repository Structure

```text
datasets/        -> Raw CSV source files  
docs/            -> Architecture diagrams & documentation  
scripts/         -> SQL scripts for Bronze / Silver / Gold layers  
tests/           -> Validation or testing scripts  
README.md        -> Project overview  

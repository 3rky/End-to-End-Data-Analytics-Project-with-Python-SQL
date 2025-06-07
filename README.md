# 🧠 End-to-End Data Analytics Project with Python & SQL

This project walks through a complete data analytics workflow, starting from fetching a dataset using the **Kaggle API**, cleaning and transforming it with **Python (Pandas)**, storing it in a **SQL Server** database, and finally analyzing it using powerful **SQL queries** to extract meaningful insights.

---

## 📌 Project Overview

**Objective:**  
To demonstrate how Python and SQL can be combined to perform real-world data analytics — from raw data acquisition to answering business questions using structured query language.

---

## 🔧 Technologies Used

- **Python 3.10+**
  - Pandas
  - SQLAlchemy
  - pyodbc
  - Kaggle API
- **SQL Server**
- **Jupyter Notebook**
- **Kaggle Dataset** (accessed via API)

---

## 📈 Workflow Summary

1. **Dataset Access**
   - Use Kaggle API to programmatically download a dataset

2. **Data Processing & Cleaning**
   - Load CSV into Pandas
   - Handle missing values, standardize columns, optimize data types

3. **Load Data to SQL Server**
   - Create database & table schemas
   - Use `pyodbc` or `SQLAlchemy` to insert cleaned data into SQL Server

4. **Data Analysis Using SQL**
   - Run SQL queries to answer interesting business questions
   - Aggregate, filter, and join data to extract insights

---

## 💡 Key Learnings

- Automating data access with the Kaggle API
- Effective use of Pandas for preprocessing
- Interfacing between Python and SQL databases
- Writing efficient SQL queries to support business intelligence

---

## 📁 Project Structure

```bash
├── data/
│   └── raw_dataset.csv
├── notebooks/
│   └── data_cleaning.ipynb
│   └── sql_analysis.ipynb
├── scripts/
│   └── kaggle_download.py
│   └── load_to_sql.py
├── README.md

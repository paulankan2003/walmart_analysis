# Walmart Sales Data Analysis: End-to-End MySQL + Python Project

## Project Overview

This project is an **end-to-end data analysis solution** built on Walmart’s sales dataset.  
It combines **Python (for cleaning & processing), SQL (for advanced querying), and problem-solving techniques** to extract meaningful business insights.  

The goal is to replicate a real-world workflow that a **Data Analyst** would follow — from raw data collection to actionable insights.  

---

## Project Workflow

### 1. Environment Setup
- **Tools**: VS Code, Python, MySQL, PostgreSQL  
- Organized project structure for smooth development and version control.  

### 2. Dataset Access via Kaggle API
- Download datasets directly using Kaggle API.  
- Store datasets inside the `data/` folder for easy access.  

 Dataset Link: [Walmart Sales Dataset](https://www.kaggle.com/najir0123/walmart-10k-sales-datasets)

### 3. Data Exploration & Cleaning
- Checked datatypes, null values, and duplicates.  
- Cleaned and standardized columns (e.g., date formatting, price conversion).  
- Ensured the dataset is consistent and analysis-ready.  

### 4. Feature Engineering
- Created new features such as **Total Amount** (`unit_price * quantity`).  
- These engineered columns simplified SQL queries and enabled deeper analysis.  

### 5. Database Integration
- Loaded cleaned data into **MySQL** and **PostgreSQL** using `SQLAlchemy`.  
- Automated table creation and insertion from Python.  
- Verified data accuracy via sample queries.  

### 6. SQL Analysis (Business Problem-Solving)
Used SQL to answer real-world business questions:  
- Revenue trends across branches and categories.  
- Best-selling product categories.  
- Sales performance by time, city, and payment method.  
- Peak shopping hours and customer behavior.  
- Profitability and margin insights.  

Each query was documented with objective → approach → results.  

### 7. Documentation & Publishing
- Complete workflow explained in **Markdown + Jupyter Notebook**.  
- Published on **GitHub** with project structure, scripts, and results.  

---

## 🛠️ Tech Stack & Requirements

- **Python 3.8+**  
- **Databases**: MySQL
- **Libraries**: `pandas`, `numpy`, `sqlalchemy`, `mysql-connector-python` 
- **Kaggle API Key** for data access  

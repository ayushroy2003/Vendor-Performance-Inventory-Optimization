# Vendor Performance & Inventory Optimization

## Project Overview

This project is an end-to-end Data Analytics and Business Intelligence solution focused on optimizing vendor performance, inventory management, and profitability in the retail and wholesale industry.

Using SQL, Python, Statistics, and Power BI, the project analyzes over 10 million transactional records to uncover inefficiencies in purchasing, inventory turnover, and pricing strategies. The final outcome is a set of actionable business recommendations designed to improve profitability and capital utilization.

---

## Business Problem

Organizations frequently struggle with:

* Excess inventory causing capital blockage
* Poor stock turnover
* Vendor dependency risks
* Inefficient pricing strategies
* Lack of data-driven purchasing decisions

This project aims to identify these issues and provide analytical solutions to improve operational efficiency and profit margins.

---

## Tech Stack

### Database

* SQLite

### Programming

* Python
* Pandas
* NumPy
* SQLAlchemy

### Statistical Analysis

* SciPy
* Statsmodels

### Data Visualization

* Matplotlib
* Seaborn

### Business Intelligence

* Power BI
* DAX

---

## Dataset

* Original Dataset Size: 10M+ Records
* Database Size: ~2 GB SQLite Database
* Analytical Dataset: 10,692 Aggregated Vendor Records

**Note:** Due to GitHub repository size limitations, only the processed analytical dataset (`vendor_sales_summary.csv`) is included in this repository.

---

## Project Workflow

### 1. Data Ingestion & ETL

Developed an automated ETL pipeline using Python and SQLAlchemy to:

* Extract raw CSV files
* Load data into SQLite
* Validate successful ingestion
* Log execution times and errors

Script:

* `ingestion_db.py`

---

### 2. SQL Data Aggregation

Created optimized SQL queries and joins to combine:

* Vendor Data
* Purchase Data
* Sales Data
* Inventory Data

The process transformed millions of transactional records into a clean analytical dataset containing 10,692 vendor-level observations.

Script:

* `get_vendor_summary.py`

---

### 3. Data Cleaning & Feature Engineering

Performed:

* Missing value treatment
* Data type corrections
* String standardization
* Outlier validation

Created business KPIs including:

* Gross Profit
* Profit Margin
* Sales-to-Purchase Ratio
* Stock Turnover

---

### 4. Exploratory Data Analysis

Conducted comprehensive EDA using Python to:

* Identify trends
* Analyze vendor performance
* Explore profitability drivers
* Examine inventory behavior

Notebook:

* `Exploratory Data Analysis.ipynb`

---

### 5. Statistical Hypothesis Testing

Performed:

* 95% Confidence Interval Analysis
* Independent Sample T-Test

Validated statistically significant differences in profit margins between high-performing and low-performing vendors.

Notebook:

* `Vendor Performance Analysis.ipynb`

---

### 6. Power BI Dashboard

Built an interactive dashboard featuring:

* Vendor Performance KPIs
* Inventory Insights
* Profitability Analysis
* Purchase Contribution Analysis
* Brand Performance Tracking

Dashboard File:

* `vendor_performance.pbix`

---

## Key Business Insights

### Inventory Optimization

Identified approximately **$2.7 Million** in capital locked within slow-moving inventory.

---

### Revenue Growth Opportunities

Discovered **198 high-margin but low-sales brands** that present strong opportunities for targeted promotions and pricing optimization.

---

### Cost Reduction

Found that bulk purchasing strategies reduce per-unit procurement costs by approximately **72%**, significantly improving margins.

---

### Vendor Performance Strategy

Statistical testing revealed:

* High-volume vendors achieved margins of approximately **30.74% – 31.61%**
* Lower-volume vendors achieved margins of approximately **40.48% – 42.62%**

This indicates opportunities for differentiated pricing and distribution strategies.

---

## Repository Structure

```text
Vendor-Performance-Inventory-Optimization/
│
├── Exploratory Data Analysis.ipynb
├── Vendor Performance Analysis.ipynb
├── Vendor Performance Report.pdf
├── get_vendor_summary.py
├── ingestion_db.py
├── vendor_performance.pbix
├── vendor_sales_summary.csv
├── README.md
└── requirements.txt
```

---

## Files Included

| File                              | Description                                 |
| --------------------------------- | ------------------------------------------- |
| ingestion_db.py                   | ETL pipeline for data ingestion             |
| get_vendor_summary.py             | SQL aggregation and feature engineering     |
| Exploratory Data Analysis.ipynb   | EDA and visualization                       |
| Vendor Performance Analysis.ipynb | Statistical analysis and hypothesis testing |
| vendor_performance.pbix           | Interactive Power BI dashboard              |
| Vendor Performance Report.pdf     | Final business report                       |
| vendor_sales_summary.csv          | Processed analytical dataset                |

---

## Skills Demonstrated

* SQL Query Optimization
* ETL Pipeline Development
* Data Cleaning
* Feature Engineering
* Exploratory Data Analysis
* Statistical Analysis
* Hypothesis Testing
* Data Visualization
* Power BI Dashboard Development
* Business Intelligence
* Data Storytelling
* Business Problem Solving

---

## Author

**Ayush Kumar**

Aspiring Data Analyst | SQL | Python | Power BI | Statistics | Data Visualization

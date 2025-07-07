# 📊 Sales Data Dashboard & Analysis Project

This project analyzes a real-world retail sales dataset using **Excel**, **Python**, **SQL**, and **AWS QuickSight**. It focuses on building data dashboards, performing business analysis, and automating reporting tasks for scalable insights.

---

## 🚀 Objective

To explore and visualize historical sales trends, identify key revenue drivers, and automate reporting tasks to support data-driven business decisions.

---
## 📁 Dataset

- Source: [Kaggle - Sample Sales Data](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data)
- Size: 2,000+ records of retail sales
- Columns: ORDERDATE, SALES, PRODUCTLINE, CUSTOMERNAME, DEALSIZE, etc.

---
## 📌 Key Features

### Data Cleaning (Python)
- Converted `ORDERDATE` into standard date format
- Handled missing values in STATE, POSTALCODE, and TERRITORY using `pandas`
- Ensured 0 duplicate rows
- Standardized categorical variables (e.g., `DEALSIZE`)
- Performed EDA with **Matplotlib** and **Seaborn**:
  - Sales distribution
  - Deal size counts
  - Outlier detection
  - Correlation matrix
  - Top products and top countries

---
### Python + SQLite
- Loaded cleaned data into a SQLite database
- Wrote and executed multiple business queries:
  - Monthly sales trends
  - Top customers & top products by revenue
  - Sales by product line and country
  - Revenue share by `DEALSIZE`


### 📈 Excel Dashboard & Automation
- Built **pivot tables** for:
  - Total sales by product line
  - Total sales by country
- Implemented:
  - **VLOOKUP** for MSRP lookup
  - **INDEX/MATCH** for flexible cross-sheet matching
  - **Data linking** across sheets for dynamic summaries
- Recorded **macros** to refresh pivot tables and apply filters

### 📊 AWS QuickSight Dashboard
- Imported dataset and created visuals:
  - Sales by Month-Track trends and seasonality  
  - Top 5 Products by Revenue (Bar Chart)-Identify best-selling products
  - Sales by Product Line (Bar Chart)- Regional performance 
  - Deal Size Distribution (Donut Chart)-Compare revenue from Small, Medium, Large
  - Sales by Country (Map Visual)-Show Total Sales, Avg Order Value, Order Coun
- Created **KPI cards**:
  - Total Sales
  - Average Order Value
  - Total Orders
  - highest single sale
- Applied filters for Year, Product Line, and Deal Size


## 🧠 Tools Used

| Tool         | Purpose                          |
|--------------|----------------------------------|
| Python       | Data cleaning, preprocessing     |
| Pandas       | Exploratory data analysis (EDA)  |
| SQLite       | SQL queries, joins, aggregations |
| Excel        | Pivot tables, macros, automation |
| AWS QuickSight | Dashboard building, KPI visuals  |


## 📌 Sample Business Insights

- **Top country**: United States (> 3.6M sales)
- **Best-selling product**: Classic Cars (> $3.9M revenue)
- **Deal size impact**:
  - Medium deals → 60% of revenue
  - Small deals → 26%
  - Large deals → 13%
- **Highest sales month**: November 2004 ($1M+)
---

## 📂 Project Structure

├── sales_data_sample.csv # Raw dataset
├── sales_cleaned.csv # Cleaned version
├── sales.ipynb # Python + SQL analysis
├── sales.db # SQLite database
├── /images/ # Dashboard screenshots
└── README.md # Project summary (this file)

---

## ✅ Outcomes
This project simulates a real-world data analyst workflow — combining data wrangling, SQL queries, visual storytelling, and dashboarding to extract actionable insights. It demonstrates proficiency across data cleaning, visual analysis, and cloud-based BI tools.

---
## 🚀 Next Steps

- Enable **QuickSight Q** for natural language queries
- Schedule automated report generation using Python scripts or Excel VBA

Nethra Shiva
MS in Computer Science | Data & Full Stack Enthusiast
✉️ nxr6130@mavs.uta.edu
🔗 https://www.linkedin.com/in/nethra-renjarla-920b3a197/

# Vendor Performance Analysis - Retail Inventory &Sales 

Analysing vendor efficiency and profitability to support startegic purchasing and inventory decisions using SQL, Python, and Power BI.  

## Table of Contents
 - [Oerview](#overview)
- [Business Problem](#business-problem)
- [Tools & Technologies](#tools--technologies)
- [Data Cleaning & Preparation](#Data--Cleaning--Preparation)
- [Exploratory Data Analysis EDA](#Exploratory--Data--Analysis--EDA)
- [Research Questions & Key Findings](#Research--Questions--Key--Findings)
- [Dashboard](#Dashboard)
- [Final & Reccomendation](#Final--Reccomendation)
- [How to Run](#how-to-run)
- [Author](#author)

----
## Oerview

This project evaluating vendor performance and retail inventory dynamics to drive strategic insights for purchasing , pricing, and inventory optimization. A complete data pipeline was built using SQL for ETL, Python for analysis and hypothesis testing, and Power BI for visualization.


## Business Problem

Effective inventory and sales management are critical in the retail sector, This project aims to:
- Identify underperforming brands needing pricing or promotional adjustments.
- Determine vendor contribution to sales and profits.
- Analyze the cost- benefit of bulk purchasing.
- Investigate inventory turnover inefficiencies.
- Statistically validate differences in vendor profitablity.




## Tools & Technologies

- SQL  (Common table analysis, Filtering, Joins)
- Python (Pandas,Matplotlib,Seaborn,SciPy)

- Power BI  (Interactive Visualization)

- Github



## Data Cleaning & Preparation

- Removed transacions with:
  - Gross Profit <= 0
  - Profit Margin <= 0
  - Sales Qunatity = 0
- Created summary tables with vendor-level metrics
- Converted data types,handled outliers, mered lookup tables

## Exploratory Data Analysis EDA

**Negative or Zero Values Detected:**
- Gross Profit: Min -  (loss-making sales)
- Profit Margin: Min -    (sales at zero or below cost)
- Unsold Inventory: Indicating slow- mooving stock

**Outliers Indentified:**
- High Freight Cost
- LArge Purchase/ Actual Prices

**Correlation Analysis:**
- Weak between Purchase Prices & Profit
- Strong betwen Purchase Qty & Sales Qty
- Negative between Profit Margin & Sales Price

## Research Questions & Key Findings

1. **Brands for promtions** 
2. **Top Vendors**
3. **Bulk Purchasing Impact**
4. **Inventory Turnover**
5. **Vendor Profitibitability**
6. **Hypothesis Testig**


## Dashboard

- Power BI Dashboard Shows:
 - Vendor-wise Sales and Margins
 - Inventory Turnover
 - Bulk Purchase Savings 
 - Performance Heatmaps

![Vendor Performance Dashboard](images/dashboard.png)



## Final & Reccomendation

- Diversity Vendor Base to reduce risk 
- Optimize bulk order stratigies 
- Reprice slow-moving , ig-margin brands
- clear unsold inventory Strategically 
- Improve marketing for underperforming vendors




## How to Run

1. Clone the repository:

git -https://github.com/simransaini0212-tech/vendor-performance-analysis-sql-python-powerbi/edit/main/README.md

2. Load the CSVs and ingest into batabase:

python [ingestion_db](ingestion_db.ipynb)

3. Create Vendor summary tables:

python [vendor_sales_summary](vendor_sales_summary.ipynb)


4. Open Power BI Dashboard:
 - https://drive.google.com/file/d/1QOOnt0arZh-ez3aVYuqKTcxNMufcFx64/view?usp=sharing




## Author 

**Simran Saini**

Data Analyst

Email - simransaini0212@gmail.com

linkedIn - https://www.linkedin.com/in/simran-saini-92a301369/

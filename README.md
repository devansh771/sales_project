# Automated Sales ETL Pipeline (Excel → Python → SQL → Power BI)

## Project Overview
Built an end-to-end ETL pipeline to automate sales reporting and replace manual Excel-based analysis. The project uses Python for data cleaning and transformation, MySQL for centralized storage, and Power BI for interactive dashboarding.

## Objective
- Eliminate manual Excel reporting issues
- Automate data cleaning and loading
- Create a scalable SQL-based data warehouse
- Enable automatic dashboard updates with new data

## Dataset
- Raw sales dataset in Excel format
- Initial dataset: ~500 rows
- Incremental update test: +200 rows (2026 records)

### Key Columns
- Order ID
- Order Date
- Customer
- Region
- Product
- Sales
- Cost

## Tools & Technologies
- **Python** (Pandas, SQLAlchemy, PyMySQL)
- **MySQL**
- **Power BI**
- **Jupyter Notebook**
- **Excel**

## ETL Workflow
1. Extract raw Excel sales data  
2. Clean missing values and duplicates using Python  
3. Perform feature engineering and transformations  
4. Load cleaned data into MySQL  
5. Connect Power BI to MySQL for live reporting  

## KPIs Tracked
- Total Sales
- Total Profit
- Profit Percentage
- Monthly Sales Trend
- Regional Profit Analysis
- Product-wise Sales Performance

## Dashboard Features
- KPI summary cards
- Monthly sales trend analysis
- Regional profit comparison
- Product performance visualization
- Interactive slicers for Region & Year
- Automated refresh from SQL database

## Key Insights
- Prevented duplicate records using SQL unique constraints
- Improved scalability compared to Excel-only reporting
- Identified seasonal sales patterns and regional performance trends
- Created stable Power BI connections using MySQL backend

## Conclusion
This project demonstrates how Python, SQL, and Power BI can be integrated to build a scalable and automated business intelligence solution. The pipeline reduces manual work, improves data accuracy, and supports real-time decision-making.

## Data Source
[Google Sheets Dataset](https://docs.google.com/spreadsheets/d/1433yAYI53DJTnp5FozoXWict56goq4nL/edit?gid=890605535#gid=890605535)


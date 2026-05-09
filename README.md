# Automated Sales ETL Pipeline (Excel → Python → SQL → Power BI)

## Project Overview
Built an end-to-end ETL pipeline to automate sales reporting and replace manual Excel-based analysis. The project uses Python for data cleaning, MySQL for centralized storage, and Power BI for interactive dashboarding.

---

## Business Problem
Manual Excel reporting created:
- Duplicate records
- Broken Power BI connections
- Slow reporting workflows
- Poor scalability with growing data

This project solves these issues using an automated SQL-based ETL pipeline.

---

## Objective
- Automate data cleaning and transformation
- Create a centralized SQL database
- Enable scalable reporting infrastructure
- Support automatic dashboard updates with new records

---

## Dataset
- Raw operational sales data in Excel format
- Initial dataset: ~500 rows
- Incremental update test: +200 rows (2026 data)

### Key Columns
- Order ID
- Order Date
- Customer
- Region
- Product
- Sales
- Cost

---

## Tools & Technologies
- **Python** (Pandas, SQLAlchemy, PyMySQL)
- **MySQL**
- **Power BI**
- **Jupyter Notebook**
- **Excel**

---

## Skills Demonstrated
- ETL Pipeline Development
- Data Cleaning & Transformation
- SQL Database Integration
- Dashboard Development
- Data Modeling
- Incremental Data Loading
- Business Intelligence Reporting

---

## Data Flow Architecture
Excel Data → Python ETL → MySQL Database → Power BI Dashboard

---

## ETL Workflow
1. Extract raw Excel sales data
2. Clean missing values and duplicates using Python
3. Transform and prepare data for analysis
4. Load cleaned data into MySQL
5. Connect Power BI to MySQL for live reporting

---

## KPIs Tracked
- Total Sales
- Total Profit
- Profit Percentage
- Monthly Sales Trend
- Regional Profit Analysis
- Product-wise Sales Performance

---

## Dashboard Features
- KPI summary cards
- Monthly sales trend analysis
- Regional profit comparison
- Product performance charts
- Interactive slicers for Region & Year
- Automated SQL-based dashboard refresh

---

## Technical Highlights
- Automated duplicate removal using Python
- Used SQL unique constraints for data integrity
- Built reusable ETL workflow
- Enabled automatic Power BI refresh from MySQL

---

## Key Insights
- Improved scalability compared to Excel-only reporting
- Identified seasonal sales trends
- Analyzed regional profitability differences
- Created stable Power BI connections using SQL backend

---

## Conclusion
This project demonstrates how Python, SQL, and Power BI can be integrated to build a scalable and automated business intelligence solution that reduces manual effort and improves reporting efficiency.

---

## Data Source
[Google Sheets Dataset](https://docs.google.com/spreadsheets/d/1433yAYI53DJTnp5FozoXWict56goq4nL/edit?gid=890605535#gid=890605535)


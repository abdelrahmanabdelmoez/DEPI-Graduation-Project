📊 WideWorldImporters Data Analysis Project
by X-ANALYTIX TEAM

📘 Project Overview
This project focuses on analyzing the WideWorldImporters database to extract actionable insights across multiple business domains: Sales, Human Resources (HR), Supply Chain, and Marketing.
We utilize SQL Server, Python, and Power BI to transform raw data into strategic, decision-driving visualizations.

👥 Team Members

- AbdelRahman AbdelMoez Anwar
- Fatma Ali Khaled
- Youssef Mohamed Farag
- Noha Soliman Mohamed

👨‍🏫 Supervisor
Eng. Ahmed Alaa

🎯 Project Objectives
Deliver data-driven insights to support business decisions.

Create interactive dashboards and automated reports.

Ensure data integrity and apply robust analytical methods.

🧭 Project Scope
Design and execution of data analysis methodologies.

SQL Server for structured data extraction.

Python for preprocessing and statistical exploration.

Power BI for dashboard creation and advanced visual storytelling.

📈 Key Performance Indicators (KPIs)
Sales
Revenue Growth

Best-Selling Products

Customer Retention Rate

HR
Employee Turnover Rate

Performance Distribution

Supply Chain
Inventory Turnover Ratio

Supplier Efficiency Metrics

Marketing
Campaign Effectiveness

Customer Acquisition Cost

🛠 System Architecture

Layer	Technology Used
Backend	SQL Server (Data Storage & Queries)
Processing	Python (Pandas, Matplotlib, Seaborn)
Frontend	Power BI (Dashboards & Visuals)

🔄 Data Flow Pipeline

Data Extraction – Raw data retrieved via SQL queries.

Data Cleaning – Preprocessing and transformation in Python.

Data Analysis – Exploratory data analysis and KPI derivation.

Visualization & Reporting – Dashboards built using Power BI.

🔧 Implementation Details

💾 SQL Server
Used for data querying and transformation:

sql
-- Example: Total Sales by Customer
SELECT CustomerID, SUM(LineTotal) AS TotalSales
FROM Sales.InvoiceLines
GROUP BY CustomerID;

🐍 Python
Utilized for data preprocessing and exploratory data analysis:

python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Example: Sales Over Time
plt.figure(figsize=(10,6))
df.groupby(df['InvoiceDate'].dt.to_period('M'))['OrderValue'].sum().plot(kind='line')
plt.title('Sales Over Time')
plt.xlabel('Month')
plt.ylabel('Total Sales')
plt.show()

📊 Power BI
Built interactive dashboards with custom DAX measures
Performed data transformation using Power Query

dax
Total Sales = SUM('InvoiceLines'[LineTotal])

📦 Final Deliverables

📄 Executive Summary Report: Actionable insights and strategic recommendations.
🧑‍💼 Stakeholder Presentation: Interactive data storytelling using Power BI.

✅ Conclusion
The WideWorldImporters Data Analysis Project provides a comprehensive framework for analyzing enterprise data using industry-standard tools. Our structured pipeline supports data-driven decisions across various business functions—empowering stakeholders with actionable, visual insights.

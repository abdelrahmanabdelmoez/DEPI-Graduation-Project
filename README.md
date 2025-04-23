
📊 WideWorldImporters Data Analysis Project  
by X-ANALYTIX TEAM

📘 Project Overview  
This project analyzes the WideWorldImporters database to extract actionable insights across core business domains:  
Sales, Human Resources (HR), Supply Chain, and Marketing.  
We leverage SQL Server, Python, and Power BI to convert raw data into strategic, decision-enhancing visualizations.

👥 Team Members  
- AbdelRahman AbdelMoez Anwar  
- Fatma Ali Khaled  
- Youssef Mohamed Farag  
- Noha Soliman Mohamed  

👨‍🏫 Supervisor  
- Eng. Ahmed Alaa  

🎯 Project Objectives  
- Deliver data-driven insights to support business decisions.  
- Create interactive dashboards and automated reports.  
- Ensure data integrity through robust analytical practices.

🧭 Project Scope  
- Develop and apply data analysis methodologies.  
- Use SQL Server for structured data extraction.  
- Utilize Python for data preprocessing and statistical analysis.  
- Design Power BI dashboards for advanced data storytelling.

📈 Key Performance Indicators (KPIs)  

🔹 Sales  
- Revenue Growth  
- Best-Selling Products  
- Customer Retention Rate  

🔹 Human Resources (HR)  
- Employee Turnover Rate  
- Performance Distribution  

🔹 Supply Chain  
- Inventory Turnover Ratio  
- Supplier Efficiency  

🔹 Marketing  
- Campaign Effectiveness  
- Customer Acquisition Cost  

🛠 System Architecture  

Layer       | Technology Used                             
------------|----------------------------------------------
Backend     | SQL Server – Data Storage & Querying         
Processing  | Python – Pandas, Matplotlib, Seaborn         
Frontend    | Power BI – Dashboards & Visualizations      

🔄 Data Flow Pipeline  
1. Data Extraction – Retrieve raw data using SQL queries.  
2. Data Cleaning – Clean and preprocess using Python.  
3. Data Analysis – Perform EDA and KPI derivation.  
4. Visualization & Reporting – Build dashboards in Power BI.

🔧 Implementation Details  

💾 SQL Server  
Used for data querying, joining, and aggregating:

-- Example: Total Sales by Customer
SELECT CustomerID, SUM(LineTotal) AS TotalSales
FROM Sales.InvoiceLines
GROUP BY CustomerID;

🐍 Python  
Applied for data cleaning, manipulation, and EDA:

import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Example: Sales Over Time
plt.figure(figsize=(10, 6))
df.groupby(df['InvoiceDate'].dt.to_period('M'))['OrderValue'].sum().plot(kind='line')
plt.title('Sales Over Time')
plt.xlabel('Month')
plt.ylabel('Total Sales')
plt.show()

📊 Power BI  
- Created interactive dashboards highlighting business KPIs.  
- Used Power Query for data transformation.  
- Defined DAX measures for dynamic reporting:

Total Sales = SUM('InvoiceLines'[LineTotal])

📦 Final Deliverables  
- Executive Summary Report – Actionable insights & business recommendations.  
- Stakeholder Presentation – Data storytelling using Power BI dashboards.

✅ Conclusion  
The WideWorldImporters Data Analysis Project presents a scalable and structured methodology for transforming data into insights.  
By integrating SQL Server, Python, and Power BI, our project enables informed decision-making across multiple departments, empowering stakeholders with clear, visual business intelligence.

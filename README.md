# End-to-End-Data-Analysis-Project
🚴 End-to-End Data Analysis Project

This project demonstrates a complete end-to-end data analysis workflow, starting from raw data processing in SQL to interactive insights and visualizations in Power BI.

📌 Project Overview

The goal of this project is to:

- Combine and clean multi-year bike share data

- Perform cost and profit calculations using SQL

- Build an interactive Power BI dashboard for business insights

- This mirrors a real-world analytics workflow used in data analyst and business intelligence roles.

🗂️ Project Files
File	Description
- SQLQuery1.sql	SQL script used for data merging, transformation, and profit analysis
- End to End Data Analysis.pbix	Power BI report built on top of the SQL output

🧠 Data Processing (SQL)

The SQL script performs the following steps:

Uses a CTE (Common Table Expression) to:

- Combine multiple yearly bike-share tables using UNION

- Joins operational data with a cost table

Calculates:

1. Revenue

2. Costs

3. Profit metrics

4. Produces a clean, analysis-ready dataset for visualization

This step ensures that all business logic lives in SQL before visualization.

📊 Data Visualization (Power BI)

The Power BI report includes:

- Key performance indicators (KPIs)

 Revenue

- Cost

- Profit

- Trend analysis across years

- Clean, interactive visuals for decision-making

- A dashboard layout suitable for stakeholders

- The .pbix file connects to the processed data and turns it into actionable insights.

🛠️ Tools & Technologies

1. SQL (CTEs, joins, aggregations)

2. Power BI

3. Relational databases

4. Business analytics & reporting

🚀 How to Use This Project

Run SQLQuery1.sql in your SQL environment to generate the analysis dataset

Open End to End Data Analysis.pbix in Power BI Desktop

Refresh the data connection if needed

Explore the dashboard and insights

Have fun :)


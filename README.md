# E-commerce-Sales-Analysis-Pipeline

## 📝 Project Overview
This project is an end-to-end data analysis solution designed to identify the root causes of Negative Profit Margins in an e-commerce business. I built a complete ETL (Extract, Transform, Load) pipeline that integrates SQL, Python, and Power BI to turn raw transactional data into actionable business insights.

## 🚀 Business Problem & Key Insights
The primary goal was to investigate why the platform was facing losses despite high sales volume.

Critical Findings:
Loss-Making Sub-Categories: Analysis revealed that Tables and Electronic Games have such low profit margins that they are essentially "Loss Leaders"—the business is losing money on every unit sold.

Geographical Impact: Negative profit is heavily concentrated in Bihar, Andhra Pradesh, Punjab, and Tamil Nadu. This is directly linked to a high volume of 'Table' and 'Electronic Games' orders in these specific regions.

Category Imbalance: While Furniture and Clothing drive high sales, their profit-to-sales ratio is significantly lower compared to Electronics.

The Monday Slump: Data shows that Monday is the weakest day for sales, and transactions occurring on this day consistently result in negative profit margins.

## 🛠️ Tech Stack & Tools
MySQL: For database management and performing complex INNER JOIN operations between datasets.

Python (Pandas): For advanced data cleaning, handling missing values, and feature engineering.

Matplotlib & Seaborn: For exploratory data analysis (EDA) and finding statistical correlations.

Power BI: For building an interactive, high-impact dashboard for executive decision-making.

## ⚙️ Step-by-Step Workflow
Step 1: Database Management (SQL)
I imported two core datasets—List of Orders and Order Details—into MySQL. Using the Order ID as a primary key, I performed an Inner Join to create a unified view of the customer journey and financial data.

Step 2: Data Cleaning & Feature Engineering (Python)
Using a Python-to-SQL connection, I performed the following:

Standardized date formats for time-series analysis.

Engineered new features like Order Month and Order Year to detect seasonal trends.

Calculated Profit Margin % at a granular level to isolate unprofitable transactions.

Step 3: Advanced Visualization (Power BI)
The final cleaned dataset was visualized using an interactive dashboard featuring:

Decomposition Trees: For root-cause analysis of sales across States and Cities.

KPI Cards: Tracking real-time Revenue, Total Profit, and Sales volume.

Profitability Analysis: Highlighting sub-categories that require immediate pricing reviews.

<img width="1042" height="851" alt="Screenshot 2026-04-24 160841" src="https://github.com/user-attachments/assets/56f99ff1-9948-4339-af31-4742b39a2c47" />


[**Download Power BI Dashboard (.pbix)**](./E-commerce-Sales-Analysis-Pipeline.pbix)

🎓 Key Learnings
How to build a seamless data pipeline across different platforms (SQL ➔ Python ➔ Power BI).

The ability to identify "Hidden Losses" where high sales volume masks poor profitability.

Identifying specific geographical and temporal patterns (like the Monday Slump) that impact the bottom line.

📂 Explore the Project
E-commerce-Sale-Analysis-Pipeline.ipynb: View the full Python cleaning and EDA code.

E-commerce-Sales-Analysis-Pipeline.pdf: Detailed documentation of the analysis process.

📬 Contact
I am an aspiring Data Analysis Engineer looking for internship opportunities where I can solve real-world business problems.

Name: Anil Saini

Email: [anilsaini978571@gmail.com]

LinkedIn: [https://www.linkedin.com/in/anil-saini-data/]

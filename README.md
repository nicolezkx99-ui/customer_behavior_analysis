🛍️ Retail Customer Behavior Analysis (End-to-End Pipeline)
📌 Project Overview
This project demonstrates a complete data analytics lifecycle: from raw data cleaning in Python and database management in PostgreSQL to interactive storytelling in Tableau. The goal was to analyze 3,900+ retail transactions to identify high-value customer segments and optimize marketing strategies for subscription services.

🛠️ Tech Stack
Language: Python 3.12 (Pandas, NumPy, SQLAlchemy)

Database: PostgreSQL 16 (Relational Data Modeling & Storage)

BI Tool: Tableau Desktop (Interactive Dashboarding & Visual Analytics)

Environment: macOS / JDBC Driver Integration

📂 Repository Structure
notebooks/: Jupyter Notebook containing ETL (Extract, Transform, Load) logic.

sql/: DDL scripts for table creation and data insertion.

tableau/: .twbx (Tableau Packaged Workbook) for the final dashboard.

data/: Sample of the cleaned dataset used for visualization.

📊 Key Insights & Features
Subscription Impact: Although only 27% of customers are subscribers, they represent a significantly higher average purchase frequency compared to non-subscribers.

Product Performance: The Clothing category is the primary revenue driver, contributing to over 40% of total sales.

Demographic Targeting: Customers aged 18-30 (Young Adults) are the most active segment, suggesting a need for social-media-focused marketing campaigns.

Interactive UX: Built a dynamic dashboard with Global Filter Actions, allowing stakeholders to drill down by Category, Age Group, and Gender simultaneously.


⚙️ How to Run
Database: Import the .sql file into your local PostgreSQL instance.

Drivers: Ensure you have the postgresql-42.7.10.jar driver in your Tableau Drivers folder.

Workbook: Open Customer_Behavior_Analysis.twbx to explore the visualizations

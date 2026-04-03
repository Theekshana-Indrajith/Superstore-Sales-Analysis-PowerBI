# Superstore-Sales-Analysis-PowerBI<img width="1901" height="818" alt="Screenshot 2026-04-03 011147" src="https://github.com/user-attachments/assets/3c3ecfc5-7619-4b3b-bcbb-32a85cf2a30e" />


📊 Sales Performance & Business Insights Dashboard

🚀 Project Overview
This project involves an end-to-end Business Intelligence solution developed using Power BI to analyze the sales performance of a global retail superstore. The goal was to transform raw transactional data into actionable insights, helping stakeholders identify high-growth categories, monitor profitability, and optimize regional sales strategies.

🛠️ Technical Workflow (ETL & Data Engineering)
Before building the visuals, I performed extensive Data Engineering to ensure data integrity:

Extraction: Connected and imported raw datasets from CSV/Excel sources.

Transformation (Power Query):

Data Cleaning: Handled missing values, removed duplicates, and corrected data types.

Text Manipulation: Standardized category names and formatted geographical data (City, State, Region).

Custom Columns: Created conditional columns for seasonal grouping and priority levels.

Data Modeling: Established a star-schema-inspired model to ensure efficient filtering and high-performance DAX calculations.

🧠 Advanced Analytics with DAX
I developed several custom measures using DAX (Data Analysis Expressions) to extract deeper business KPIs:

Profit Margin %:

Code snippet
Profit Margin % = DIVIDE([Total Profit], [Total Revenue], 0)
Year-over-Year (YoY) Growth: Calculated to track performance compared to previous periods.

Total Orders & Unique Customers: Used DISTINCTCOUNT to analyze customer loyalty and volume.

📈 Key Business Insights
Top Performers: The Technology category consistently drives the highest profit margins despite lower transaction volumes compared to Office Supplies.

Regional Trends: The West Region dominates in total revenue, while the South Region shows the highest potential for growth in specific sub-categories.

Shipping Impact: Identified a correlation between "Same Day" shipping and lower profit margins due to high operational costs.

🖥️ Dashboard Features
Dynamic Slicers: Filter by Region, Segment, and Year for real-time data exploration.

Interactive Visuals: Cross-filtering enabled across all charts to drill down into specific data points.

KPI Cards: High-level summary of Revenue, Profit, and Orders for instant status checks.

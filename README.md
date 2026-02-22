# Task-3-ApexPlanet-
worked with data to answer complex, multi-faceted business problems by performing deep-dive analysis defined core KPI's &amp; made interactive Dashboards.


📊 Apex Planet Internship - Task 3: Sales Deep-Dive & Customer Segmentation


Power BI Python Pandas


📝 Project Overview

This project is part of the Apex Planet Data Analytics Internship (Task 3).

The objective was to perform a deep-dive analysis of sales data to identify customer behavior patterns.


I utilized Python (Pandas) to perform RFM (Recency, Frequency, Monetary) Analysis and developed an Interactive Power BI Dashboard to visualize the findings. 
This helps the business identify "Best Customers" for rewards and "Lost Customers" for re-engagement campaigns.


📂 Files in Repository

File Name	Description
Task_3_Power_BI_Customer_Segmentation.pbix:	The Interactive Dashboard file. Contains all visuals, KPIs, and Slicers.
Task3_DeepDive_Analysis.ipynb	Python Notebook: Contains the code for Data Cleaning, RFM Scoring, and Segmentation logic.
Task3_RFM_Analysis.csv	Output Data: The final dataset with Customer Segments (Best, Loyal, Lost, etc.) created by Python.
cleaned_data.csv	Cleaned Dataset: The processed sales data used for analysis.
Task3_DeepDive_Report.txt	Summary Report: A text file summarizing key insights and methodology.


🔍 Methodology: RFM Analysis


I used the RFM technique to score customers based on three factors:

Recency (R): How recently did the customer purchase?
Frequency (F): How often do they purchase?
Monetary (M): How much do they spend?
Based on these scores, customers were grouped into segments:

Best Customers: High spending, frequent buyers, bought recently.
Loyal Customers: Frequent buyers.
Big Spenders: High monetary value.
Lost Customers: Haven't bought in a long time.
Standard Customers: Average behavior.


📊 Dashboard Features (Power BI)


The interactive dashboard includes:

KPI Cards: Displaying Total Sales ($2.26M), 
Total Orders (4,922),
and Unique Customers (793).

Donut Chart: Visualizing the distribution of customer segments (Best vs. Lost).

Interactive Slicer: Allows filtering the entire dashboard by Segment (e.g., clicking "Best Customers" filters the sales data).

Bar & Line Charts: Trend analysis over time and sales by category.


💡 Key Insights

Total Revenue: $2,261,536.78
Best Customers: We identified 35 high-value customers who contribute significantly to revenue.
Retention Risk: There are 158 Lost Customers who require immediate marketing attention.
Average Order Value: $459.48


🚀 How to Run


Download the Task_3_Power_BI_Customer_Segmentation.pbix file.
Open it in Microsoft Power BI Desktop.
Ensure the data source (cleaned_data.csv and Task3_RFM_Analysis.csv) paths are correct if you want to refresh the data.
Interact with the Segment Slicer on the left to explore the data.


Author: Poorvi Malvi
Internship: Apex Planet (Data Analytics)
Internship: Apex Planet (Data Analytics)


📊 Website Traffic Dashboard – Tableau

This repository contains the data preparation scripts, analysis workflow, and screenshots for an interactive website traffic analytics dashboard, built using Tableau.
The project visualizes daily website activity, focusing on user acquisition, retention, and engagement patterns over time.

📁 Project Overview

The goal of this project is to transform raw website traffic data into meaningful visual insights.
By combining Python (for data cleaning) with Tableau (for analytics & visual storytelling), this project delivers:

Trends in unique visitors

Patterns in first-time vs returning visits

Weekly traffic behavior

Relationships between page loads and visitor activity

Composition of visit types over time

An interactive Tableau dashboard

A Tableau Story summarizing trends

📷 Dashboard Preview

(Insert your screenshot here — for example):

🔗 Live Tableau Dashboard

Access the fully interactive dashboard on Tableau Public:

👉 https://public.tableau.com/views/Rohan_GERMANY/Dashboard1

🧰 Features & Visualizations
1️⃣ Unique Visitors Over Time (Line Chart)

Shows long-term traffic patterns and significant peaks or dips.

2️⃣ New vs Returning Visits Trend (Dual-Axis Line Chart)

Illustrates acquisition vs retention performance.

3️⃣ Average Unique Visits by Day of Week (Bar Chart)

Helps identify the best-performing days for publishing and engagement.

4️⃣ Page Loads vs Unique Visitors (Scatter Plot)

Reveals correlations or anomalies in user engagement.

5️⃣ Visit Composition Over Time (Stacked Bar Chart)

Displays how new and returning visitors contribute to overall website traffic.

6️⃣ Interactive Filters & Tooltips

Includes:

Date filters

Visitor type filters

Hover tooltips

Highlight interactions across charts

📂 Files Included
File	Description
cleaned_daily_visitors.csv	Preprocessed dataset used for Tableau
daily-website-visitors.csv	Original raw dataset
Dashboard_Screenshot.png	Static preview of Tableau dashboard
Q1079237 ROHAN NAGENDRA VSTT 2.pdf	Full project report & analysis
README.md	Project documentation
🛠️ Technologies Used

Tableau Public – dashboard creation, analytics, storytelling

Python (Pandas) – data cleaning, transformations, export

CSV dataset – daily website traffic metrics

🧹 Data Preparation Workflow

Loaded raw CSV into Python

Cleaned headers and standardized formats

Converted date column to proper datetime

Removed commas in numeric columns and fixed datatypes

Filled missing values with zeros

Created Day_Of_Week field for grouping

Exported cleaned dataset to CSV for Tableau

📈 Key Insights

Wednesday & Friday have the highest average unique visits

Clear positive correlation between page loads and visitor count

First-time visits are consistently higher than returning in most years

Traffic peaks vary seasonally and monthly

Composition trends show strong new-user acquisition but lower retention at times

🚧 Limitations

Static dataset (no real-time updates)

No demographic or geographic user segmentation

Lacks session-level engagement metrics (bounce rate, session duration)

No traffic-source attribution (e.g., social, email, ads)

🔮 Future Enhancements

Connect with Google Analytics API for live data

Add demographic segmentation

Incorporate session-level engagement metrics

Build predictive models for forecasting traffic

Automate anomaly detection and reporting

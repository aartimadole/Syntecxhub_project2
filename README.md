🚀 Automated Data Visualization & Statistical Analysis Pipeline


📌 Overview

This repository contains three end-to-end data analysis projects completed as part of the Syntecxhub Data Analytics Internship Program.

The objective was to transform raw retail sales data into actionable insights through structured visualization, statistical analysis, and correlation modeling using Python.

The projects simulate real-world analytics workflows followed in industry environments.


🗂 Dataset

Sample Superstore Dataset

Features include:

Order Date

Sales

Profit

Quantity

Discount

Category

Sub-Category

Region


📊 Project 2.1 — Time Series & Category Analysis

🎯 Business Objective

Analyze sales trends over time and evaluate revenue contribution across product categories.

🔍 Analysis Performed

Monthly aggregation of sales

Time-series line chart visualization

Category-wise revenue comparison

Proportional revenue share using pie chart

📈 Why These Charts?

Line chart → Best suited for time-series trend analysis

Bar chart → Effective for category comparison

Pie chart → Displays percentage contribution clearly

📦 Deliverables

monthly_sales.png

category_sales.png

category_share.png

Exported summary report


📈 Project 2.2 — Statistical Distribution & Outlier Detection
🎯 Business Objective

Understand the distribution behavior of sales and detect anomalies.

🔍 Analysis Performed

Histogram to inspect data distribution

Boxplot for regional comparison

IQR-based outlier detection

Skewness & spread analysis

📊 Key Findings

Sales data is right-skewed

Presence of extreme high-value outliers

Regional variation in sales spread

📦 Deliverables

sales_histogram.png

sales_boxplot_region.png

Outlier summary report


🔥 Project 2.3 — Correlation & Relationship Analysis
🎯 Business Objective

Identify relationships between numeric business variables.

🔍 Analysis Performed

Pearson correlation computation

Correlation heatmap visualization

Masked upper triangle for clarity

Annotated correlation values

Identification of strongest positive & negative relationships

📊 Key Insights

Strong positive correlation between Sales and Profit

Negative correlation observed between Discount and Profit

📦 Deliverables

correlation_heatmap.png

Correlation summary report


🛠 Tech Stack

Python

Pandas

NumPy

Matplotlib


🏗 Project Architecture
Syntecxhub_Project_AartiMadole/
│
├── project2.1_time_series.py
├── project2.2_distribution_analysis.py
├── project2.3_correlation_analysis.py
├── Sample - Superstore.csv
│
├── Generated Charts (PNG)
├── Summary Reports (.txt)
└── README.md


💡 Skills Demonstrated

✔ Time-Series Aggregation
✔ Statistical Distribution Analysis
✔ Outlier Detection (IQR Method)
✔ Correlation Modeling
✔ Data Visualization Best Practices
✔ Business Insight Interpretation


🚀 How to Execute
pip install pandas numpy matplotlib
python project1_time_series.py
python project2_distribution_analysis.py
python project3_correlation_analysis.py


📊 Professional Impact

This project demonstrates the ability to:

Translate raw data into business insights

Apply statistical reasoning

Choose appropriate visualizations

Present structured analytical findings

Follow clean, reproducible coding practices


👩‍💻 Author

Aarti Sachin Madole
Data Analytics Intern – Syntecxhub

LinkedIn: https://www.linkedin.com/in/aarti-madole-9ab74b220/
GitHub:https://github.com/aartimadole

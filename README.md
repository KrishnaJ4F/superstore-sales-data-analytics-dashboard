🛒 Superstore Sales Data Analytics Dashboard
📌 Project Overview

This project analyzes the Superstore Sales Dataset to uncover sales trends, profitability patterns, discount impact, and regional performance.

The objective is to transform raw transactional data into actionable business insights using Excel-based analytics techniques.

🎯 Project Objectives

Analyze sales trends across time (2014–2017)

Identify top-performing product categories

Evaluate profit stability

Measure impact of discount strategies

Build an interactive dashboard for decision-making

Perform What-If and Goal Seek analysis

📂 Dataset Information

The dataset contains transactional sales records including:

Order ID / Sale ID (Unique identifiers)

Order Date

Product Category & Sub-Category

Sales, Quantity, Discount, Profit

Customer Segment

City, State, Region

Ship Mode & Shipping Date

🧹 Data Cleaning Process

The following preprocessing steps were applied:

Removed duplicate records

Handled missing values

Standardized date formats

Validated numerical data types

Cleaned categorical values (Segment, Category, Region)

Ensured consistency across financial metrics

📊 Key Performance Indicators (KPIs)
KPI	Formula Used
Total Sales	=SUM(Sales)
Average Sales per Order	=AVERAGE(Sales)
Total Discount	=SUM(Discount)
Total Orders	=COUNTA(Customer_ID)
Order Count by Segment	=COUNTIF(Segment, "Criteria")
Discount by Category	=SUMIF(Category, "Criteria", Discount)
📈 Analytical Techniques Used
1️⃣ Pivot Tables & Pivot Charts

Sales by Category

Profit by Segment

Monthly Sales Trend

Discount Distribution

2️⃣ Dashboard Development

Interactive dashboard includes:

Total Sales

Average Sales per Order

Top Performing Category

Slicers for Segment & Category

Trend visualization charts

3️⃣ What-If Analysis

Net Value Formula:

= Sales * (1 - Discount) * Quantity


5% Decrease Discount Simulation:

= NetValue * ((1 - Discount) - 0.05)


Used Goal Seek to analyze discount impact on profit.

🔍 Key Insights

Sales increased steadily from 2014 to 2017

Highest sales: November 2017 (118,447.82)

Lowest sales: February 2014 (4,519.892)

Significant loss recorded in January 2015

Profit trends are more stable compared to revenue

Seasonal spikes observed in November & December

💡 Business Recommendations

Reduce aggressive discounting in low-margin categories

Capitalize on holiday sales peaks

Improve loss-making product segments

Optimize shipping efficiency for cost control

🛠 Tools Used

Microsoft Excel

Pivot Tables

Pivot Charts

Power Pivot

Power Query

What-If Analysis

Goal Seek

📷 Project Deliverables

Cleaned Dataset

Interactive Excel Dashboard

PowerPoint Presentation

Business Insights Report

📎 How to Use

Download the dataset file.

Open the Excel dashboard file.

Use slicers to filter by segment or category.

Review KPI metrics and trend charts.

Explore What-If analysis sheet.

👨‍💻 Author

Krishna Kumar
B.Tech – Computer Science (AI & Data Science)
Data Analytics & Business Intelligence Enthusiast

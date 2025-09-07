# 📊 E-commerce Sales Performance Dashboard

### 📌 Project Overview

This project presents an interactive Sales Dashboard built in Power BI for a US-based e-commerce company.
It provides insights into YTD Sales, Profit, Quantity, and Profit Margin, helping stakeholders track performance and make data-driven decisions.

The dashboard allows users to explore customer categories, states, regions, shipping types, and products, with dynamic KPIs and trend indicators powered by DAX measures.


### 🎯 Objectives

- Create a KPI Banner showing:
  - YTD Sales
  - YTD Profit
  - YTD Quantity Sold
  - YTD Profit Margin
- Track YoY Growth for each KPI with sparklines to understand monthly trends.
- Compare YTD Sales vs PYTD Sales by Customer Category with trend icons.
- Analyze Sales by State across US regions.
- Identify Top 5 & Bottom 5 Products by Sales.
- Evaluate YTD Sales by Region to find best/worst performing areas.
- Measure YTD Sales by Shipping Type to identify the most effective delivery mode.


### 🛠️ Tools & Technologies

- Power BI → Dashboard development
- SQL Server → Data connection & queries
- Power Query → Data cleaning & transformation
- DAX Functions → Advanced calculations (TOTALYTD, SAMEPERIODLASTYEAR, SUMX, FILTER, VAR, etc.)
- MS Excel & Flat Files → Supporting data sources


### ⚡ Key Functionalities Learned

- Connecting Power BI to SQL Server & Flat Files
- Data Modeling with multiple tables
- Creating a Date Table for time intelligence
- Writing Basic to Advanced DAX queries
- Implementing Dynamic KPIs & Conditional Formatting
- Adding Trend Icons & Sparklines for better storytelling
- Designing Maps, Pie Charts, and Bar Charts for geographic & categorical insights


### 📈 Dashboard Preview

### 📊 Insights Generated

- Overall YTD Sales: $11.53M with a slight decline of -0.83% YoY.
- YTD Profit: $1.34M, showing a 4.5% increase YoY.
- Customer Category Analysis: Office Supplies lead sales, but Furniture shows YoY growth.
- Regional Analysis: West region performed best (32.22% contribution), while South lagged behind.
- Product Performance: Identified both top-selling and underperforming products for strategic action.
- Shipping Insights: Standard Class accounts for 60% of orders, proving to be the most efficient.


### 📂 Repository Structure
```
📦 Ecommerce-Sales-Dashboard
 ┣ 📊 Ecommerce Sales Dashboard.pbix   # Power BI Project File
 ┣ 📄 Ecommerce Sales Dashboard.png    # Dashboard Screenshot
 ┣ 📑 README.md                        # Project Documentation
 ┗ 📂 Data                             # (Optional) Sample datasets
```

### 🚀 How to Use

1. Clone this repository:
```
git clone https://github.com/yourusername/Ecommerce-Sales-Dashboard.git
```

2. Open the .pbix file in Power BI Desktop.
3. Refresh the data connections (SQL/Excel) as per your environment.
4. Explore the interactive dashboard and gain insights.


### 📌 Author

👤 Himanshu Khakre


 # 📊 Power BI Dashboard – Superstore Sales Analysis
Overview

This Power BI report analyzes the Sample Superstore dataset to provide insights into sales, profit, and customer trends.
The dashboard includes key performance indicators (KPIs), trend analysis, and category-based visualizations to help in business decision-making.

📂 Data Source

Dataset: Sample - Superstore (Orders table)

Main Fields Used: Order Date, Sales, Profit, Quantity, Category, Segment, Region

📌 KPIs in Dashboard

Total Sales → SUM(Sales) – total revenue generated.

Profit Margin % → DIVIDE(SUM(Profit), SUM(Sales), 0) – profitability ratio.

Average Order Value → DIVIDE(SUM(Sales), COUNTROWS(Orders), 0) – average sale per order.

Sales Growth % → Year-over-year growth in sales.

Total Orders → count of distinct orders.

📊 Visuals Used

Card Visuals – for KPIs (Total Sales, Profit Margin %, Avg Order Value).

Donut Chart – Profit Margin % by Category.

Line Chart – Monthly Sales Trends.

Map Visual – Sales by State/Region.

Bar Chart – Sales by Sub-Category.

🛠 How to Use

Use the filters/slicers to view data by Year, Category, or Region.

Hover over visuals for detailed tooltips.

Click on chart segments to cross-filter other visuals.

📈 Suggested Extensions

Add Customer Segment analysis.

Include Discount Impact chart.

Create Forecasting for next year’s sales.

📌 Author

Created by Chapa Dayanita
📧 Email: chapadayanita@gmail.com
🔗 LinkedIn
💻 GitHub

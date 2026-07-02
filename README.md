Sales Dashboard – Tableau

An interactive Sales Dashboard built in Tableau, analyzing sales, profit, and category performance across the US market (Superstore-style dataset). The dashboard combines geographic, categorical, and trend-based visualizations into a single view for quick business insights.

<img width="1598" height="852" alt="Dashboard using Tableau" src="https://github.com/user-attachments/assets/84515b51-0ce7-433d-b1a2-30a087691b18" />


📊 Dashboard Overview

The dashboard is divided into five key views:

1. Sales by Segment and Region

A grouped bar chart comparing total sales across Consumer, Corporate, and Home Office segments, broken down by region (Central, East, South, West).

2. Sales by Cities

An interactive US map plotting sales performance by city, with marker size/color reflecting sales and profit values. Includes zoom and search controls for drilling into specific locations.

3. Sales vs Profit

A scatter plot correlating Sales against Profit for individual orders, with color coding to highlight profitable (blue) vs. loss-making (orange) transactions and outliers.

4. Sales by Category

A stacked bar chart showing sales distribution across the three product categories — Furniture, Office Supplies, and Technology.

5. Sales by Category (Pie Chart)

A pie chart summarizing the percentage share of total sales contributed by each category:


Technology – 36.4%
Furniture – 32.3%
Office Supplies – 31.3%


🎯 Key Insights


East and West regions drive the highest sales within the Consumer segment.
Technology is the top-performing category by sales share, closely followed by Furniture and Office Supplies.
Most orders cluster around low sales/profit values, with a few high-value outliers driving significant profit or loss.
A small number of transactions show notable losses, useful for identifying discounting or cost issues.


🛠️ Tools & Technologies


Tableau Desktop / Tableau Public – Dashboard design and visualization
CSV Data Source (Managers.csv / Sales dataset)
Mapbox / OpenStreetMap for geographic visualization


📁 Repository Contents

├── Dashboard_using_Tableau.png     # Dashboard screenshot
├── Sales_Dashboard.twbx            # Tableau packaged workbook (add if available)
└── README.md                       # Project documentation

🚀 How to View


Download and install Tableau Desktop or use Tableau Public.
Open the .twbx file included in this repository.
Interact with filters, maps, and charts to explore the data.


📌 Future Improvements


Add date-based filters for trend analysis over time.
Include discount and shipping mode impact on profit.
Add KPI cards for quick summary metrics (Total Sales, Total Profit, Order Count).

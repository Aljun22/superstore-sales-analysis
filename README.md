Superstore Sales Analysis

📊 Project Overview
This project provides an in-depth analysis of the **Superstore Sales Dataset** to uncover business insights and identify critical areas for decision-making.  
The analysis focuses on:
- Sales performance by region, category, and customer segment
- Profitability trends
- Key performance metrics using DAX calculations
- Interactive dashboards for business intelligence

---

🛠 Tools Used
- **Power BI** – For building interactive dashboards and visual analytics
- **Microsoft Excel** – For initial data cleaning and preparation
- **DAX (Data Analysis Expressions)** – For creating calculated measures and KPIs

---

 📈 Dashboard Overview
Below are sample screenshots from the interactive dashboard:

1. Main Dashboard Overview  
<p align="center">
  <img src="Images/mainpage.png" alt="Main Page" width="45%">
  <img src="Images/customer_segment.png" alt="Customer Segment" width="45%">
</p>

2. DAX Measures Table**  

---

🧮 Key DAX Measures
```DAX
Total Sales = SUM ( Orders_Clean[Sales] )

Total Profit = SUM ( Orders_Clean[Profit] )

Total Quantity = SUM ( Orders_Clean[Quantity] )

Average Discount = AVERAGE ( Orders_Clean[Discount] )

Profit Margin % = DIVIDE ( [Total Profit], [Total Sales] )

Sales per Customer = DIVIDE ( [Total Sales], DISTINCTCOUNT ( Orders_Clean[Customer ID] ) )

💡 Key Insights

High Sales, Low Profit in Technology Category

While Technology drives significant revenue, profit margins are thinner compared to Furniture.

West Region Outperforms in Sales

West leads in total sales but has moderate profit margins, requiring targeted marketing to improve profitability.

Customer Segment Trends

Consumer segment dominates in both sales and profits, suggesting potential for loyalty programs.

Seasonal Sales Patterns

Q4 consistently delivers higher sales, indicating an opportunity for targeted year-end campaigns.

🎯 Business Recommendations
Focus marketing efforts on the Technology category to improve margins.
Implement cost control strategies in high-revenue but low-profit regions.
Develop customer loyalty programs targeting the Consumer segment.
Plan promotional campaigns in Q4 to capitalize on seasonal trends.

📌 How to View the Dashboard

- Download the .pbix file from this repository.

- Open it in Power BI Desktop.

- Explore interactive features to filter and drill down into data.

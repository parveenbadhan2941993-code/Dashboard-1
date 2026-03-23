Sales Performance Dashboard – Power BI
======================================
I built this Sales Performance Dashboard in Power BI to better understand sales data. It shows key metrics like Revenue, Orders, Sold Products, and AOV, and includes Pareto charts to highlight top products. Interactive charts, slicers, and dynamic filters make it easy to explore the data and spot trends.

Overview
--------
*   Tracks Revenue, Orders, Products, and AOV
*   Monthly growth analysis
*   Sales by category and country
*   Highlights top-performing products (Pareto)
*   Interactive filters and drill-through

Key Metrics & Formulas
----------------------
*   **Revenue:** SUM(Sales\[TotalAmount\])
*   **Orders:** DISTINCTCOUNT(Sales\[OrderID\])
*   **Sold Products:** SUM(Sales\[Quantity\])
*   **AOV:** Revenue ÷ Orders
*   **Revenue Growth %:** (Revenue – Previous Month Revenue) ÷ Previous Month Revenue
*   **Orders Growth %:** (Orders – Previous Month Orders) ÷ Previous Month Orders
*   **Products Growth %:** (Sold Products – Previous Month Sold Products) ÷ Previous Month Sold Products
*   **AOV Growth %:** (AOV – Previous Month AOV) ÷ Previous Month AOV
*   **Customer Count:** DISTINCTCOUNT(Customers\[CustomerID\])

Charts Used
-----------
*   **KPI Cards:** Show overall performance and growth — support quick decisions
*   **Line Chart:** Track views vs purchases over time — identify trends
*   **Donut Chart:** Show category contribution — highlight top categories
*   **Bar Chart:** Compare category sales — evaluate performance
*   **Map Chart:** Show sales by country — identify key markets
*   **Table:** Detailed country metrics — support comparison
*   **Pareto Analysis:** Highlight top products — focus on high revenue items
*   **Slicers:** Enable filtering — support easy data exploration

Key Insights
------------
*   Top-performing categories and products identified
*   Monthly sales trends observed
*   Country-level performance compared
*   Small number of products drive most revenue

Process
-------
1.  Cleaned and prepared data
2.  Built data model
3.  Created DAX measures
4.  Designed dashboard.

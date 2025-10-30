🍕 Pizza Sales Analysis Dashboard
📊 Project Overview
The Pizza Sales Analysis Dashboard provides a comprehensive view of pizza sales performance, helping businesses analyze trends, customer preferences, and overall profitability.
It is built using Power BI with dynamic visualizations, DAX calculations, and an interactive user interface for real-time insights.

🚀 Key Insights

  Total Sales: ₹817.86K

  Total Orders: 48,620

  Total Quantity Sold: 49,574

  Average Unit Price: ₹16.49

  Pizza Categories: 4

  Pizza Sizes: 5


🧠 Dashboard Features
🔹 KPI Cards
  
  Displays key metrics such as Total Sales, Orders, Quantity Sold, and Average Price.

🔹 Top & Bottom Pizzas
  
   Top Performing Pizzas: Shows pizzas with the highest quantity sold and total sales. 
    
   Bottom Performing Pizzas: Displays the least-performing pizzas to identify improvement areas.

🔹 Category & Size Analysis

   Donut charts represent total sales share by pizza category and pizza size.

🔹 Time-Series Trends

  Line charts show monthly trends of total orders, quantity, and sales.

  Bar chart compares weekday-wise performance.


🔹 Filters Panel
Interactive slicers for:

  Date Range

  Month

 Weekday Name

 Pizza Size

 Pizza Category

  These allow users to dynamically explore data.

🧮 Tools & Technologies

  Power BI Desktop

  DAX (Data Analysis Expressions)

  Data Modeling

  Excel / CSV Data Source



🗂️ Data Model
The data model includes:

  pizza_sales: Contains order details, prices, categories, sizes, and dates.

  Date Table: Used for time intelligence calculations.


Key Measures

   Total Sales = SUM(pizza_sales[total_price])

   Total Orders = COUNT(pizza_sales[order_id])

   Total Quantity = SUM(pizza_sales[quantity])

   Average Unit Price = AVERAGE(pizza_sales[unit_price])

🖼️ Dashboard Preview
🔸 Top Performing Pizzas

🔸 Bottom Performing Pizzas

🔸 Filters & Interaction Panel

🎯 Insights & Outcomes

   Identified best-selling pizzas by category and size.

   Recognized low-performing pizzas for potential improvement.

   Discovered peak sales days and seasonal demand patterns.

  Provided actionable insights for pricing and marketing strategies.


  # Picture Preview
  https://github.com/AnshulNamdev/Pizza-Sales-Analysis-Dashboard/blob/main/Snapshot%20of%20the%20Dashboard.png

🧩 Future Enhancements

* Integrate real-time data source (SQL  
   Server / API).
* Add customer demographic and regional  
   analysis.

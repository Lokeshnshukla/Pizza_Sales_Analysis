## Build Dashboard or a Report using Power BI
<br>
-Created a comprehensive dashboard in Power BI featuring key metrics and charts, <br>
-including Hourly Trend, <br>
-Weekly Trend, Sales by Category, <br>
-Sales by Size, <br>
-Total Pizzas Sold by Category, <br>
-Top 5 Best Sellers, and Bottom 5 Worst Sellers.<br>
<br>
<br>
## KPI<br>
-Total Revenue =SUM([order id])<br>
-Total_pizza_sold = SUM(Full_table[quantity])<br>
-Total_Revenue = SUMX(Full_table,Full_table[price]*Full_table[quantity])<br>
-AOV = DIVIDE([Total_Revenue],[Total_orders],0)<br>
-Avg_pizza/order = DIVIDE([Total_pizza_sold],[Total_orders],0)<br>
-Avg_revenue/pizza = DIVIDE([Total_Revenue],[Total_pizza_sold],0)<br>

<br>
<br>
<br>
<br>
<br>
![Pizza sales Dashboard ](https://github.com/user-attachments/assets/bf9bfc6d-b8ca-45dc-b319-087e49eefcec)


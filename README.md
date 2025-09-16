## Build Dashboard or a Report using Power BI
<br>
Created a comprehensive dashboard in Power BI featuring key metrics and charts including, <br>
- Hourly Trend with category, <br>
- Total Quantity By Month, <br>
- Total Revenue On Day Basis, <br>
- Total Revenue By Month <br>
- Sales Percentage by Category, <br>
- Top 10 Best Sellers.<br>
<br>
<br>
**KPI**
<br>
- Total Revenue =SUM([order id])<br>
- Total_pizza_sold = SUM(Full_table[quantity])<br>
- Total_Revenue = SUMX(Full_table,Full_table[price]*Full_table[quantity])<br>
- AOV = DIVIDE([Total_Revenue],[Total_orders],0)<br>
- Avg_pizza/order = DIVIDE([Total_pizza_sold],[Total_orders],0)<br>
- Avg_revenue/pizza = DIVIDE([Total_Revenue],[Total_pizza_sold],0)<br>
<br>

<br>

<img width="823" height="63" alt="image" src="https://github.com/user-attachments/assets/87efc36d-87a5-4f7f-b688-2a28db30ee14" />


<br>
<br>
<br>
<br>
<br>
__DASHBOARD__  -
<br>
<br>
<img width="829" height="467" alt="image" src="https://github.com/user-attachments/assets/59ba5773-8c59-4cc5-bf6c-5fc2c457115b" />


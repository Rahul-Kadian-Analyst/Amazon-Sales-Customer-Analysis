# Amazon Sales & Customer Analysis 📊

# Overview
This project analyzes 100,000+ rows of Amazon e-commerce data to uncover insights about revenue, cancellations, customer behavior, and geography. The goal was to help the business understand where revenue is coming from, where it is being lost, and how to improve performance.

# Tools Used
- Microsoft Excel — Data cleaning and feature engineering
- Microsoft Power BI — Interactive dashboard and visualizations

# Dataset
- 100,000+ rows of Amazon sales and customer data
- Columns include: OrderID, OrderDate, CustomerID, ProductName, Category, Brand, Quantity, UnitPrice, Discount, Tax, ShippingCost, PaymentMethod, OrderStatus, City, State, Country and more

# Data Cleaning (Excel)
- Removed duplicate rows
- Handled missing and null values
- Fixed inconsistent text formatting in city and category columns
- Validated data types for all columns

# Feature Engineering (Excel)
New columns created:
- Gross Revenue = Quantity × UnitPrice
- Net Revenue = Revenue from non-cancelled orders only
- Profit = Net Revenue - ShippingCost - Tax
- Discount Amount = Quantity × UnitPrice × Discount
- Revenue Lost = Gross Revenue of cancelled orders
- Order Size = Small / Medium / Large based on order value
- Month, Year, Month-Year = Extracted from OrderDate

# Dashboard (Power BI)
The dashboard contains 5 pages:

# Page 1 — Sales Overview
- KPI Cards: Total Orders, Total Profit, Total Net Revenue, Total Gross Revenue, Total Revenue Lost, Cancellation Rate
- Total Net Revenue by Month (trend)
- Orders by Status
- Total Net Revenue by Category

# Page 2 — Sales Analysis
- Total Net Revenue by Category
- Total Orders by Payment Method
- Total Orders by Order Status
- State Slicer for filtering

# Page 3 — Cancellation Analysis
- KPI Cards: Total Cancelled Orders, Cancellation Rate, Total Revenue Lost
- Total Revenue Lost by Category, Brand, State, Payment Method
- Total Revenue Lost by Month (trend)
- State Slicer for filtering

# Page 4 — Customer & Geography Analysis
- Average Order Value and Total Unique Customers
- Total Net Revenue by Customer
- Total Orders by City and State
- Total Orders by Country
- Total Discount Amount by Category

# Page 5 — Key Business Insights
Summary of all major findings and recommendations

# Key Insights
- 💰 Total Net Revenue is 88.97M with a Total Profit of 81.39M
- 🛒 Electronics is the highest revenue generating category
- 💳 Credit Card dominates payment methods with 35% of total orders
- ❌ Overall Cancellation Rate is 3.03% with 2.81M revenue lost
- 🧸 Toys & Games has the highest revenue lost from cancellations
- 🌍 70% of orders come from United States
- 📍 Charlotte is the top city and TX is the top state by total orders
- 👤 Pooja Kapoor is the highest revenue generating customer
- 📈 Revenue dipped sharply in February, recovered mid-year and is currently rising in December

# Business Recommendations
- Investigate why Toys & Games has high cancellation rate and address root cause
- Focus marketing efforts on TX and CA as they are top performing states
- Credit Card users are the most active — consider offering credit card specific discounts
- Address the February revenue dip by planning promotions or campaigns in advance

# Author
-Rahul
- Connect with me on [https://www.linkedin.com/in/rahul-kadian-0a282828a/]
# Dashboard Screenshots

# Page 1 — Sales Overview
![Page 1](Sales%20Overview.png)

# Page 2 — Sales Analysis
![Page 2](Sales%20Analysis.png)

# Page 3 — Cancellation Analysis
![Page 3](Cancellation%20Analysis.png)

# Page 4 — Customer & Geography Analysis
![Page 4](Customer%20And%20Geography%20Analysis.png)

# Page 5 — Key Insights
![Page 5](Insights%20For%20Business.png)


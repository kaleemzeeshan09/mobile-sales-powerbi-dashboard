# mobile-sales-powerbi-dashboard
'Power BI dashboard analyzing mobile phone sales across brands, cities, and payment methods.
# Mobile Sales Analysis Dashboard

## Business Problem
A mobile retailer sells multiple brands (Xiaomi, Vivo, Samsung, OnePlus, Apple) across cities 
in India. This project analyzes sales, quantity, transactions, and customer ratings to identify 
which brands, models, cities, and payment methods drive the most revenue.

## Objective
Build an interactive Power BI dashboard to help the sales/marketing team answer:
- Which brands and models generate the most revenue?
- When (month, day) do sales peak, and where (which cities)?
- How do customers prefer to pay, and how satisfied are they?

## Tools & Approach
- **Data:** Mobile_Sales_Data.xlsx (sales, quantity, transactions, payment method, city, 
  brand, mobile model, ratings)
- **Tools:** Power BI (data modeling, interactive slicers, map, trend, and ranking visuals)
- **Approach:** Loaded and modeled the sales data in Power BI, built KPI cards for headline 
  metrics, then broke sales down by city, day, month, payment method, brand, and model — with 
  Mobile Model, Payment Method, Brand, and Day Name filters for interactive drill-down.

## Key Metrics
- Total Sales: 769M | Total Quantity: 19K units | Transactions: 4K | Average Sale Value: 40K

## Key Findings
- **Brand performance:** Apple led total sales (161.6M) closely followed by Samsung (160M), 
  with OnePlus, Vivo, and Xiaomi trailing in that order — a tight competitive spread across all five brands.
- **Model performance:** iPhone SE was the top-selling model (60M), ahead of OnePlus Nord (58M) 
  and Galaxy Note 20 (56M).
- **Payment behavior:** Customers are fairly evenly split across payment methods — Credit Card 
  (26.25%) and Debit Card (25.89%) slightly lead over UPI (25.03%) and Cash (22.83%).
- **Seasonality:** Sales trend upward through the week, peaking on Monday (26.4M) versus the 
  lowest point on Thursday (23.2M). Monthly quantity also fluctuates, peaking in July (1,700 units).
- **Customer satisfaction:** The majority of ratings are positive, with 311 five-star and 185 
  four-star reviews, versus only 67 one-star reviews — indicating generally strong customer sentiment.
- **Geography:** Sales are concentrated across major Indian cities including Mumbai, Delhi, 
  Bangalore, Kolkata, and Chennai, viewable on the map.

## Business Recommendation
Since Apple and Samsung are near-neck-and-neck in sales, targeted promotions on high-margin 
models like the iPhone SE and OnePlus Nord (the top individual performers) could help widen 
the revenue gap. The near-even payment method split suggests no single payment channel needs 
urgent optimization, but Monday's sales peak could guide staffing and promotional timing.


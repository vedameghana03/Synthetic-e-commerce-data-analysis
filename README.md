# Insights: Synthetic e-commerce data analysis

1.	Clean & Complete Data
-- Dataset contains 100,000 transactions with no missing values.
-- All dates successfully converted to datetime and broken into Date, Month, Hour.

2.	Key Metrics
-- Effective Revenue
-- Revenue Per Unit
-- Discount Per Unit
-- CTR Band
-- Weekend vs Weekday Transactions
-- Weekday and weekend Revenue 
-- Revenue to Discount Ratio

3.	Trends
•	Peak Transaction Day: 14th October 2024
•	Peak Hour: 12:00 AM (Hour = 0)
•	Weekend Revenue: ₹1.55 Cr
•	Weekday Revenue: ₹3.97 Cr → Weekdays dominate in revenue

4. Product & Region Performance
•	Top 5 Products by Revenue: Product_108, 404, 370, 686, 77
•	Top Region by Revenue: Asia (₹1.84 Cr)
•	Lowest Revenue Region: Europe (₹1.83 Cr – still very close)
•	Category-Region Analysis: Electronics in North America had highest units sold (1139536) and Books in Asia has the lowest units sold (645508)
•	Product_898 has one of the highest avg. Revenue per Unit - 11.785151

5. Advertising Performance
•	Clicks, Impressions, Ad Spend nearly equal across regions
•	Home Appliances had the highest average Conversion Rate
•	Ad Spend per Click was unusually high (₹60–90 range) for products with only 1 click — indicating inefficient spending

6. Customer Behavior
•	Over 300 customers had more than 3 transactions — possible loyal customer base
•	No customers received discounts over ₹1000 → suggests controlled pricing strategy

7. ROI Insights
•	Used Revenue-to-Discount Ratio to identify efficient deals
•	Filtered regions with:
o	High Ad Spend but Low Revenue → none found

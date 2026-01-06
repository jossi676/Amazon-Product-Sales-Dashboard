
🛒 Amazon Product Sales Performance Dashboard – 2025 (Power BI)

📘 Project Context
This project simulates a Business Analyst assignment for an e-commerce platform using a public Amazon product dataset (42K items, 2025).
The goal is to support pricing, product, and category-level decisions using data.
The dashboard is designed for Product Managers, Category Managers, and Pricing Teams to quickly understand:
•	Which categories drive the most value
•	How discounts influence customer ratings
•	Where optimization opportunities exist across brands and products
________________________________________

🎯 Business Objective
To evaluate how pricing strategy, discount levels, and product ratings interact — and identify actionable levers to improve customer satisfaction and sales performance.
Key business questions addressed:
•	Which product categories dominate sales volume?
•	Is there an optimal discount range that maximizes customer ratings?
•	Do smaller brands outperform larger brands in customer satisfaction?
•	Where should Amazon focus pricing and promotional efforts?
________________________________________

🧩 Dataset & Assumptions
•	Source: Kaggle – Amazon Products Sales Dataset (42K items, 2025)
https://www.kaggle.com/datasets/ikramshah512/amazon-products-sales-dataset-42k-items-2025
Assumptions (important for interview clarity)
•	Each product record represents an active product listing
•	Discounted price is used as a proxy for sales contribution
•	Rating count is treated as a proxy for customer engagement
•	Actual profit data is not available; analysis focuses on pricing effectiveness and customer sentiment
These assumptions are realistic for early-stage product and pricing analysis.
________________________________________
📊 Key Metrics Analyzed
•	Total Product Listings
•	Total Reviews (Customer Engagement)
•	Average Product Rating
•	Discount Percentage Distribution
•	Category-wise Contribution
•	Brand-level Rating Performance
________________________________________
🔍 Analytical Findings (Core Insights)
1️⃣ Category Concentration Risk
Finding:
•	Laptops & Phones contribute ~44% of total sales value (discounted price proxy).
Insight:
Revenue and customer attention are heavily concentrated in a few categories.
Business Implication:
•	Over-dependence on limited categories increases risk.
•	Other categories may be under-leveraged.
Actionable Recommendation:
•	Invest in targeted promotions and visibility for mid-performing categories to diversify revenue.
________________________________________
2️⃣ Discount Effectiveness Sweet Spot
Finding:
•	Products with 30–50% discounts consistently show higher average ratings.
Insight:
Customer satisfaction improves with moderate discounts, but not necessarily with extreme discounting.
Business Implication:
•	Deep discounts may reduce perceived product quality.
•	Low discounts may not incentivize engagement.
Actionable Recommendation:
•	Standardize promotional strategies around the 30–50% discount band for most categories.
________________________________________
3️⃣ Brand Performance Asymmetry
Finding:
•	Smaller or niche brands often outperform larger brands in average product ratings.
Insight:
High brand visibility does not guarantee higher customer satisfaction.
Business Implication:
•	Large brands may suffer from quality inconsistency at scale.
•	High-performing niche brands represent hidden growth opportunities.
Actionable Recommendation:
•	Promote high-rated niche brands through “Recommended” or “Top Rated” badges.
•	Use ratings, not just brand power, in ranking logic.
________________________________________
4️⃣ Ratings vs Volume Trade-off
Finding:
•	High-volume categories do not always have the highest ratings.
Insight:
Sales volume and customer satisfaction are not perfectly correlated.
Business Implication:
•	Focusing only on sales can hide quality issues.
•	Long-term trust depends on balancing volume with satisfaction.

Actionable Recommendation:
•	I recommended optimizing discount strategies, promoting high-rated niche brands, and diversifying category focus to reduce revenue risk.
Also Introduce category-level quality thresholds (minimum rating benchmarks).
________________________________________


📈 What the Dashboard Enables (Decision Support)
This dashboard enables stakeholders to:
•	Identify where discounts are actually effective
•	Detect overperforming and underperforming categories
•	Compare brand performance beyond raw sales
•	Support pricing, promotion, and assortment decisions

________________________________________

⚙️ Tools & Techniques Used
•	Power BI – Data visualization and storytelling
•	Power Query – Data cleaning and transformation
•	Built-in aggregations – SUM, AVERAGE, COUNT
•	Business framing – Assumptions, insights, recommendations
(No custom DAX was required for this analysis.)
________________________________________
## 📷 Dashboard Preview
![Dashboard Overview](Dashboard_Screenshots/Overview.png)


**Created by:** *Jijo S*  
**Dataset Source:** Kaggle  
**Tool:** Power BI | 2025

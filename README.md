
# 🍽️ Naija Tastes Restaurant Sales Analysis
---
**📌 Project Overview**
---
This project analyzes four months (November–February) of restaurant sales data for Naija Tastes, a local Nigerian eatery. The goal is to explore customer demographics, identify top-performing products, and uncover sales trends to support smarter business decisions.

The data was cleaned and prepared using Python, transformed in Power Query, and visualized in Power BI. The entire process aims to empower the restaurant with actionable insights to optimize menu performance, streamline operations, and better understand its customers.

**🧹 Data Cleaning and Preparation**
---
Tools Used:
Python, power bi

Datasets:
Customers.csv
products.csv
Sales.csv

Steps taken:
Created my table and imported the datasets into Python.
Validated data structure against table definitions (customers, products, and sales)

**Checked for and confirmed:**
✅ No null primary keys
✅ No duplicate email addresses or product IDs
✅ No negative quantities or prices

Verified integrity by comparing:
total_price = quantity × price
Preserved same-day purchases from customers as valid (not treated as duplicates)

---
# 📊 Statistical Summary
---
Using python, the following key metrics were derived:
Total Sales Revenue: ₦2,290,000
Total Transactions: 500
Average Revenue per Transaction: ₦4,570
Total Unique Customers: 100
Average Revenue per Customer: ₦22,860

These metrics served as the foundation for deeper analysis and KPI design in Power BI.

📈 Sales Trends and Product Performance
🗓️ Sales by Day
Saturday consistently generated the highest revenue across the four months, peaking at over ₦400k, followed by Thursday with ₦355k. Weekends (Saturday & Sunday) accounted for 31% of sales, while weekdays captured the remaining 69%.

**🍽️ Best-Selling Products**
---
🏆 Suya & Chips – ₦343k
Amala & Ewedu – ₦318.6k
Eba & Ogbono Soup – ₦310.8k
Jollof Rice & Chicken – ₦237.5k
Palm Wine – ₦226.8k

❌ Least Performing Items
Zobo Drink – ₦110k
Chapman – ₦153k
Pepper Soup – ₦162k

👥 Customer Demographics & Segmentation
📍 Top Customer Locations
Ikeja – 28 customers
Victoria Island – 20 customers
Lekki – 19 customers
Yaba – 18 customers
Surulere – 15 customers

These areas show strong engagement and should be targeted in campaigns or delivery services.

👤 Age Group Analysis
25–34 age group led with 25 customers and the highest revenue share
35–44 followed with 24 customers
45–54 included 21 customers
18–24 had 17 customers
55+ had 13 customers

# 💳 Payment Method Preferences
---
Transfers – 36.4%
POS payments – 31.6%
Cash – 32%

Majority of customers use cashless payment options, highlighting the importance of efficient POS and transfer systems.

# 📉 Key Insights
---
High Concentration of Revenue from a Few Customers:
Customers with IDs 2, 25, 4, 53, and 63 contributed over ₦240k collectively. These high-value customers represent a core audience that should be retained with loyalty offers or VIP treatment.

Weekday Dominance with Weekend Peaks:
While weekdays account for most transactions, Saturdays dominate single-day revenue. This pattern suggests a mix of daily regulars and weekend splurges.

25–34 Year Olds are the Spending Core:
This age group leads in both frequency and revenue contribution, making them ideal for targeted upselling and personalized marketing.

Ikeja, VI, and Lekki are Core Markets:
These locations combine for nearly 70 customers, indicating regional clusters that could support localized advertising or delivery expansion.

Suya & Amala Rule the Menu:
The top 3 dishes bring in nearly ₦1M of total revenue. These are not just best-sellers but brand-defining items.

Digital Payments are Dominant:
With over 68% of payments via transfer or POS, cashless infrastructure should be a top operational priority.

![My Project Screenshot](C:\Users\USER\Desktop\screen)

**✅ Recommendations***
---
Introduce a Loyalty Program for Top Spenders:
Target the highest-value customers with exclusive deals or early access to new menu items.

Bundle Promotions on Weekends:
Create combo offers (e.g., Suya + Palm Wine + Chapman) to increase average ticket size, especially for weekend diners.

Deploy Delivery Services in Top Locations:
Focus on Ikeja, VI, and Lekki through partnerships with delivery platforms or own dispatch teams.

Launch Campaigns for the 25–34 Demographic:
Use Instagram and WhatsApp to promote events, discount codes, and offers catered to this segment.

Enhance POS and Transfer Checkout:
Install more terminals and automate transfer confirmations to minimize delay during peak hours.

Repackage Underperformers:
Bundle slow-moving drinks (Zobo, Chapman) with best-sellers or offer them at a discount with meals to boost movement.

Smart Staffing by Day:
Increase kitchen and wait staff on Thursdays and Saturdays; reduce weekday lunch crew where demand is lower.

**📊 Power BI Dashboard**
---
The final interactive dashboard is built in Power BI Desktop, showcasing:
KPI Card Row – Total Revenue, Avg Transaction Value, Total Customers
Customer Insights – Age, Location, Top Spenders
Sales Trends – Daily and Day-of-Week revenue performance
Menu Performance – Top and bottom products by revenue
Payment Method Breakdown – Transaction count and revenue share



# 🧰 Tools and Technologies
---
python – Data cleaning and analysis
Power Query – Data transformation and model structuring
DAX Measures – KPI calculations, segmentation, and conditional logic
Power BI Desktop – Visualization and storytelling
GitHub – Project documentation and version control

**📌 Conclusion**
---
Through effective data modeling, insightful python analysis, and interactive Power BI dashboards, this project delivers a comprehensive understanding of Naija Tastes' business operations. From identifying top-selling dishes and key customer segments to optimizing staffing and pricing strategies, this analysis serves as a powerful decision-making tool for management. With continued tracking and timely updates, the dashboard can evolve into a real-time performance monitor as the business scales.

About
An end-to-end analytics project for Naija Tastes restaurant using python and Power BI. It explores customer behavior, sales trends, top products, and payment methods to uncover actionable insights and support data-driven business decisions.

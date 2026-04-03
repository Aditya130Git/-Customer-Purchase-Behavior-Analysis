# -Customer-Purchase-Behavior-Analysis

📊 (Python + SQL + Power BI Project)

📌 Project Overview

This project focuses on analyzing customer purchase behavior using a combination of SQL for data extraction, Python for data processing, and Power BI for visualization.

The goal is to uncover business insights related to customer spending patterns, product performance, and behavioral segmentation to support data-driven decision-making.

🧰 Tech Stack

SQL (PostgreSQL / MySQL) → Data querying & transformation

Python (Pandas, NumPy, Matplotlib/Seaborn) → Data cleaning & analysis

Power BI → Interactive dashboards & visualization


📂 Dataset Description

The dataset contains customer-level transactional data with the following key fields:

    customer_id

    age, gender

    item_purchased, category

    purchase_amount

    review_rating

    shipping_type

    subscription_status

    discount_applied

    previous_purchases


🔍 Key Business Questions Answered


1. 💰 Revenue Analysis by Demographics
2. Used window functions to calculate revenue across gender and age groups.Helps identify high-value customer segments.

 🏷️ Discount Effectiveness
Identified customers who:

Used discounts

Still spent above average


👉 Insight: Discounts can drive higher-value purchases, not just low-value conversions.


 ⭐ Product Performance
   
      Top 5 products ranked by average review rating
      
      Helps identify:
      
      High customer satisfaction products
      
      Potential flagship offerings


🚚 Shipping Impact on Spending

  Compared Standard vs Express shipping


👉 Insight: Shipping preference influences customer spending behavior.



👥 Subscription Analysis

Compared:


  Total customers

  Average spend

  Total revenue


👉 Insight: Subscribed users typically contribute higher revenue, making them a valuable segment.



📉 Discount Usage by Product


  Calculated discount usage percentage per product


👉 Insight:


Some products rely heavily on discounts → may indicate pricing issues or demand sensitivity


🧩 Customer Segmentation


  Customers were categorized into:


  New → 1 purchase

  Returning → 2–10 purchases

  Loyal → 10+ purchases


👉 Insight:


Helps in designing targeted marketing strategies


🏆 Product Ranking Within Categories

  Used DENSE_RANK() to identify top products per category
  

👉 Insight:


Enables category-level optimization and inventory planning



🔁 Repeat Buyers vs Subscription


  Analyzed whether frequent buyers are also subscribers

👉 Insight:

Strong relationship can support subscription-based growth strategies


🎯 Revenue by Age Group


   Used window aggregation to calculate age-wise revenue contribution

👉 Insight:

Identifies high-spending age segments for targeted campaigns


📊 Power BI Dashboard



The Power BI dashboard provides interactive visualizations for:



   Revenue trends
   Customer segmentation
   Product performance
   Payment & shipping insights
Key Features:
  Dynamic filtering (age, category, gender)
  KPI cards (Revenue, Profit, Orders)
  Category & region-level breakdowns



💡 Business Recommendations


      🎯 Target high-spending age groups with personalized campaigns
      💰 Optimize discount strategies to maximize profit, not just sales
      📦 Promote top-performing products aggressively
      🔁 Encourage repeat purchases via loyalty programs
      📬 Convert frequent buyers into subscribers
      🚚 Optimize shipping options to enhance customer experience




📁 Project Structure



     📦 Customer-Behavior-Analysis
        ┣ 📜 dataAnalysisProject.ipynb   # Python analysis
        ┣ 📜 analysisQuery.sql          # SQL queries
        ┣ 📊 PowerBI_Dashboard.pbix     # Dashboard file
        ┗ 📄 README.md                  # Project documentation



 🏁 Conclusion

 

This project demonstrates how combining SQL, Python, and Power BI can deliver powerful business insights. The analysis highlights opportunities to improve customer retention, pricing strategies, and product performance, ultimately driving better business outcomes.


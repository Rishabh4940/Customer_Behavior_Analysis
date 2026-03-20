Customer Shopping Behavior Analysis
📌 Project Overview
This project provides a comprehensive analysis of customer shopping behavior using transactional data from 3,900 purchases. The goal is to uncover insights into spending patterns, customer segments, and product preferences to guide strategic business decisions.

📊 Interactive Dashboard
Below is a snapshot of the Power BI dashboard created for this analysis. It tracks key performance indicators (KPIs), demographic distributions, and sales trends.

🚀 Key Insights & KPIs
Total Transactions: 3,900

Average Purchase Value: $59.76

Average Review Rating: 3.75 / 5.0

Revenue Leader: Male customers ($157,890) vs. Female customers ($75,191).

Top Sellers: Blouses and Jewelry lead the product catalog with 171 orders each.

Shipping Impact: Express shipping users spend an average of $60.48, which is slightly higher than standard shipping users ($58.46).

🛠️ Tech Stack
Python (Pandas): For data cleaning, handling 37 missing review ratings, and feature engineering (age grouping).

PostgreSQL: For deep-dive analysis and identifying high-value customer segments.

Power BI: For building the interactive data visualization dashboard.

📂 Project Workflow
1. Data Preparation (Python)
Handled missing values in the Review Rating column.

Standardized column names to snake_case for database compatibility.

Binned ages into categories: Young Adult, Middle-aged, Adult, and Senior.

2. SQL Analysis
Subscription Opportunity: Identified 2,518 repeat buyers (more than 5 purchases) who have not yet signed up for a subscription.

Customer Loyalty: Segmented the database to find that 79% (3,116) of customers are classified as "Loyal."

Discount Strategy: Found that 839 customers used discounts while still spending above the average purchase amount.

3. Visual Storytelling (Power BI)
   ## 📷 Dashboard Preview
![Dashboard](dashboard.jpg)
Created filters for Subscription Status, Gender, and Category.

Visualized revenue by age group, showing that Young Adults ($62k) and Middle-aged ($59k) are the highest-grossing demographics.

💡 Strategic Recommendations
Target the "Unsubscribed Loyals": Launch a targeted email campaign for the 2,518 repeat buyers to convert them into subscribers.

Optimize Shipping: Promote "Express Shipping" more aggressively, as these customers tend to have a higher average order value.

Gender-Specific Marketing: Investigate the 2.1x spending gap between Male and Female customers to create more inclusive or targeted marketing for the female segment.

Review Incentives: Improve the overall rating (3.75) by incentivizing reviews on top-selling products like Blouses and Jewelry.

# E-commerce-market-analysis
Insights and Outcomes

Monthly customer acquisition varied, with a peak of 215 new customers in January 2019.
Customer retention was analyzed, revealing a steady retention rate of around 70%-80% monthly.
Revenue Trends:

Total revenue for 2019 reached over $4.3M, with November being the highest revenue-generating month ($406,866).
New customer contributions were tracked, with a consistent but lower share compared to retained customers.
Impact of Discounts:

Products with a 20% discount generated significant revenue ($1.22M), indicating discounts are a strong driver for sales.
Seasonality and Product Preferences:

Revenue and sales quantities peaked in Q4 (Oct-Dec), indicating a holiday shopping trend.
"Office" products were the most purchased category, contributing 88,383 units sold.
Marketing Spend Analysis:

A direct correlation between marketing spend and revenue was noted; higher spends in Q4 led to significant revenue surges.
Online marketing had a higher return on investment compared to offline channels.
RFM Segmentation:

Customers were segmented into tiers using Recency, Frequency, and Monetary metrics.
High-value customers (low recency, high frequency, high monetary) made up ~14% of the customer base.
Customer Lifetime Value (CLTV):

CLTV was calculated for each customer, categorizing them into high (14%), medium (40%), and low (46%) value groups.
Cross-Selling Opportunities:

Frequent itemsets revealed strong associations between products like "Nest Learning Thermostat" and "Nest Cam Security Cameras," indicating effective bundling opportunities.
Approach in Detail:
Data Preprocessing:

Integrated datasets on customer demographics, transactions, discounts, and marketing spend.
Handled missing values, normalized transaction data, and created derived metrics like sales and invoice amounts.
Exploratory Data Analysis (EDA):

Visualized trends using bar charts and time-series plots.
Examined seasonal patterns, discount impacts, and product preferences.
Customer Segmentation:

Applied RFM analysis to classify customers into actionable tiers.
Used clustering (K-Means) for advanced segmentation with optimal cluster count of 4.
Predictive Modeling:

Built classification models (Decision Trees, XGBoost) to predict CLTV tiers with test accuracies of 77% (Decision Tree) and 75% (XGBoost).
Association Rule Mining:

Used the Apriori algorithm to identify cross-selling opportunities with confidence levels exceeding 90%.
Business Impact:
Optimized Marketing Strategies: Insights on seasonal trends and high-performing discounts can guide resource allocation.
Improved Customer Retention: RFM-based segmentation allows targeted retention campaigns for at-risk customers.
Revenue Growth: Identifying cross-selling opportunities enhances basket sizes and average order values.
Enhanced Decision-Making: Predictive models and customer profiling provide actionable intelligence for strategic planning.

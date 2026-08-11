Customer Shopping Behavior Analysis

An end-to-end Data Analytics and Business Intelligence projectanalyzing 3,900 customer transactions to uncover spending patterns,product preferences, subscription behavior, customer loyalty, discountusage, shipping behavior, and demographic trends.

📌 Project Overview

This project transforms raw customer transaction data into actionablebusiness insights using Python (Pandas), PostgreSQL, SQL, and PowerBI.

Business Questions

Which customer groups contribute the most revenue?

How do subscribers and non-subscribers differ?

Which products perform best?

Which products depend most heavily on discounts?

How does shipping type relate to purchase amount?

Which age groups generate the most revenue?

How can customers be segmented based on purchase history?

📊 Dataset

3,900 purchase records

18 original features

37 missing Review Rating values

Area                                Features

Demographics                        Age, Gender, Location, SubscriptionStatus

Purchase Details                    Item Purchased, Category, PurchaseAmount, Season, Size, Color

Shopping Behavior                   Discount Applied, PreviousPurchases, Frequency of Purchases

Experience                          Review Rating, Shipping Type

🛠️ Tech Stack

Python | Pandas | PostgreSQL | SQL | Power BI

Additional skills demonstrated: - Data Cleaning - Exploratory DataAnalysis - Feature Engineering - Customer Segmentation - DataVisualization - Business Intelligence

🔄 Analytics Workflow

Raw Data → Python/Pandas → Data Cleaning → Feature Engineering →PostgreSQL → SQL Analysis → Power BI → Business Insights

🧹 Data Cleaning & Feature Engineering

Explored data using df.info() and df.describe()

Identified 37 missing Review Rating values

Imputed missing ratings using category-level median values

Standardized columns to snake_case

Created age_group

Created purchase_frequency_days

Checked redundancy between discount and promo-code fields

Removed redundant promo_code_used

Loaded the cleaned dataset into PostgreSQL

🗄️ SQL Business Analysis

SQL was used to investigate:

Revenue by Gender

High-Spending Discount Users

Top 5 Products by Rating

Shipping Type Comparison

Subscribers vs. Non-Subscribers

Discount-Dependent Products

Customer Segmentation

Top 3 Products per Category

Repeat Buyers & Subscriptions

Revenue by Age Group

📈 Key Findings

Revenue by Gender

Gender       Revenue

Female      $75,191Male       $157,890

Revenue by Age Group

Age Group        Revenue

Young Adult     $62,143Middle-aged     $59,197Adult           $55,978Senior          $55,763

Subscription Analysis

Status             Customers   Average Spend     Revenue

Subscriber             1,053         $59.49    $62,645Non-Subscriber         2,847         $59.87   $170,436

Subscriber and non-subscriber average spending is almost identical,highlighting an opportunity to strengthen the subscription valueproposition.

Customer Segmentation

Loyal: 3,116

Returning: 701

New: 83

Top-Rated Products

Product     Avg. Rating

Gloves             3.86Sandals            3.84Boots              3.82Hat                3.80Skirt              3.78

Discount-Dependent Products

Product      Discount Rate

Hat                 50.00%Sneakers            49.66%Coat                49.07%Sweater             48.17%Pants               47.37%

839 customers used discounts while still spending above the overallaverage purchase amount.

Shipping Comparison

Standard Shipping average purchase: $58.46

Express Shipping average purchase: $60.48

📊 Power BI Dashboard

An interactive Power BI dashboard was developed to present customer andbusiness insights.

Main KPIs

3.9K Customers

$59.76 Average Purchase Amount

3.75 Average Review Rating

Dashboard analysis includes: - Subscription Status - Gender - Category -Shipping Type - Revenue by Category - Sales by Category - Revenue by AgeGroup - Sales by Age Group

💡 Business Recommendations

Subscription Strategy: Strengthen subscriber benefits and conversioncampaigns because subscriber spending currently does not materiallyexceed non-subscriber spending.

Customer Loyalty: Use personalized offers, referral incentives, andretention campaigns for the large loyal-customer segment.

Discount Optimization: Evaluate highly discounted products todetermine whether promotions generate sufficient incremental businessvalue.

Product Positioning: Highlight highly rated and frequently purchasedproducts in campaigns and recommendations.

Targeted Marketing: Use age and purchase-behavior segmentation formore focused marketing.

Shipping Strategy: Further investigate Express-shipping customersbecause their average transaction value is slightly higher.

⚠️ Analytical Limitations

Results are primarily descriptive and do not establish causality.

Product cost and profit data were unavailable for profitabilityanalysis.

Statistical significance testing was not performed for shippingdifferences.

Customer segmentation follows the purchase-history rules used inthis project.

🎯 Project Outcome

This project demonstrates an end-to-end analytics workflow coveringdata cleaning, exploratory analysis, feature engineering, databaseintegration, SQL analysis, dashboard development, and business decisionsupport.

👤 Author

Mehedi Hasan Zisan

Data Analytics Portfolio Project

⭐ If you find this project useful, consider starring the repository.

📊 Customer Behavior Analysis

🔍 Overview

In this project, I analyzed customer shopping behavior using data from around 3,900 transactions across different product categories. The main goal was to understand how customers shop — what they buy, how much they spend, and how factors like subscriptions or discounts affect their behavior.

The insights from this analysis can help businesses make better, data-driven decisions.

📁 Dataset Details

The dataset contains 18 features that cover different aspects of customer behavior, including:

Customer details: Age, Gender, Location, Subscription Status
Purchase information: Product, Category, Purchase Amount, Season, Size, Color
Behavioral data: Discount usage, Purchase frequency, Ratings, Shipping type

There were a few missing values in the Review Rating column, which I handled using the median rating for each product category.

🧹 Data Preparation (Python)

I used Python (Pandas) to clean and prepare the data before analysis:

Cleaned and structured the dataset
Standardized column names for better readability
Handled missing values
Created new useful features:
Age groups for better segmentation
Purchase frequency (in days)
Removed unnecessary or duplicate columns
Loaded the cleaned data into a SQL database for further analysis

🗄️ Data Analysis (SQL)

Using SQL, I explored the data to answer important business questions, such as:

How revenue differs between male and female customers
Which customers spend more even when using discounts
Which products have the highest ratings
Differences between standard and express shipping
Behavior of subscribers vs non-subscribers
Customer segmentation (New, Returning, Loyal)
Revenue contribution by different age groups
Products that rely heavily on discounts

📊 Data Visualization (Power BI)

I created an interactive Power BI dashboard to present the insights in a simple and visual way.

The dashboard includes:

Customer segmentation
Revenue trends
Product performance
Subscription insights

💡 Key Insights

Customers with subscriptions tend to contribute more to revenue
Loyal customers purchase more frequently and spend more
Some products rely heavily on discounts to drive sales
Age group and shipping preferences influence buying decisions

🚀 Recommendations

Based on the analysis:

Promote subscription plans with added benefits
Introduce loyalty programs to retain customers
Optimize discount strategies to maintain profit
Focus marketing on high-value customers and top products

🛠️ Tech Stack

Python (Pandas) – Data cleaning and preparation
SQL (MySQL/PostgreSQL) – Data analysis
Power BI – Data visualization

📌 Conclusion

This project shows how tools like Python, SQL, and Power BI can be used together to turn raw data into useful insights, helping businesses better understand their customers and improve decision-making.

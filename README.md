Customer Behaviour Analysis  
 1. Project Overview

This project focuses on analyzing customer shopping behavior to uncover meaningful business insights related to revenue generation, customer segmentation, product performance, and purchasing patterns. The analysis is designed to simulate a real-world data analytics task performed by a Data Analyst/Senior Data Analyst.

The goal is to transform raw transactional data into actionable insights that can support decision-making in marketing, sales, inventory planning, and customer retention.

 2. Business Objectives

The primary objectives of this analysis are:

* Identify key revenue-driving customer segments
* Determine best-selling products and categories
* Analyze the impact of age, gender, seasonality, and subscriptions on sales
* Understand customer loyalty and purchase frequency
* Evaluate operational factors such as shipping type and payment methods
 3. Dataset Description

The dataset contains approximately 3,900 customer-level records with the following attributes:

 3.1 Customer Information

* `customer_id`: Unique identifier for each customer
* `age`: Customer age
* `gender`: Customer gender
* `age_group`: Categorized age range
* `location`: Customer location

 3.2 Product & Transaction Details

* `item_purchased`: Product purchased
* `category`: Product category
* `size`: Product size
* `color`: Product color
* `purchase_amount`: Transaction amount
* `review_rating`: Customer review rating

 3.3 Behavioral & Operational Attributes

* `subscription_status`: Indicates whether the customer is subscribed
* `discount_applied`: Whether a discount was applied
* `payment_method`: Payment method used
* `shipping_type`: Shipping method selected
* `season`: Season of purchase
* `frequency_of_purchases`: Purchase frequency level
*  previous_purchases`: Number of previous purchases
* purchase_frequency_days`: Average days between purchases
4. Tools & Technologies Used

  Python – Data analysis and transformation
* Pandas – Data manipulation and aggregation
* Plotly– Interactive data visualization
* Jupyter Notebook – Analysis and documentation

---

5. Data Preparation Steps

1. Loaded dataset using Pandas
2. Validated column names and data types
3. Checked for missing and inconsistent values
4. Created grouped and aggregated datasets for analysis
5. Prepared data for visualization

---

 6. Analysis & Key Findings

 6.1 Gender-wise Revenue Analysis

* Male customers contribute a slightly higher share of total revenue compared to female customers.
* Indicates gender-based differences in purchasing behavior.

 6.2 Product Category Performance

* Clothing is the highest revenue-generating category.
* Other categories contribute less but provide cross-selling opportunities.

 6.3 Best-Selling Products

* Products such as Blouse, Jeans, and Sweater are the most frequently purchased.
* These items represent consistent customer demand.

6.4 Age-Based Spending Patterns

* Customers in the mid-age groups (approximately 26–45 years) show higher average spending.
* Younger and older age groups contribute comparatively less per transaction.

6.5 Seasonal Trends

* Revenue peaks during Winter and Spring seasons.
* Sales are lower in Summer and Fall.

 6.6 Subscription Impact

* Subscribed customers generate more consistent and higher revenue.
* Subscription status is strongly linked to customer loyalty.

6.7 Discount Effectiveness

* Discounts positively influence purchasing behavior without significantly reducing average order value.

 6.8 Payment Method Preferences

* Digital payment methods dominate transactions.
* Cash-based payments are less frequently used.

6.9 Customer Loyalty Analysis

* Customers with higher purchase frequency spend more on average.
* Loyal customers are key revenue contributors.

6.10 Shipping Type Influence

* Faster shipping options contribute more to total revenue.
* Delivery speed influences customer purchase decisions.

 7. Business Impact

The analysis provides insights that can help businesses:

* Improve targeted marketing strategies
* Optimize inventory and product planning
* Increase customer retention and lifetime value
* Enhance checkout and delivery experiences

8. Conclusion

This project demonstrates how exploratory data analysis and visualization can be used to extract valuable business insights from customer data. By identifying revenue drivers, customer segments, and behavioral patterns, the analysis supports data-driven decision-making across multiple business functions.

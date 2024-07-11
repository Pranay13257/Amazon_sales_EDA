# Amazon Sales Dataset

## Problem Statement:
I am working on a dataset containing Amazon product ratings and reviews. This dataset has the data of 1K+ Amazon Product's Ratings and Reviews as per their details listed on the official website of Amazon. The task involves data cleaning, visualizing trends and patterns, performing descriptive statistics, creating various charts and graphs, and identifying outliers. Additionally, I will address 12 industry-level data analytics questions to gain deeper insights into product popularity, pricing strategies, user behavior, and review sentiments.

## Objectives:
The objective of this project is to conduct a comprehensive data analysis of Amazon product ratings and reviews. The analysis aims to provide valuable insights into product performance, pricing strategies, user behavior, and review sentiments. Specifically, the project will:
1. Data Cleaning
2. Descriptive Statistics
3. Updating Dataset
4. Visualization
5. Chart and Graph Creation
6. Outlier Detection
7. Addressing Industry-Level Questions

## Assumptions:
- While treating null values, I have replaced them through product ratings on Amazon by searching the provided product_id on their official website (amazon.in).
- Products with the highest review counts within their categories might be considered potential top sellers, even without direct sales data.

## Data Analysis through Industry-Level Questions:

### Product Popularity Analysis

*Q1: Which products have the highest average ratings?*

*Observation:* The top three products, which have the highest average ratings of 5.0, are the Amazon Basics Wireless Mouse, REDTECH USB-C to Lightning Cable, and Syncwire LTG to USB Cable. Products related to electronics and household utilities such as the Oraletch Coffee Frother electric and the Instant Pot Air Fryer also have high ratings, close to 4.8. The lowest average rating among the top ten products is 4.7.

*Q2: How do product ratings correlate with the number of ratings?*

*Observation:* Yes, there is a positive correlation, but it is poorly correlated (0.11).

### Category Popularity Analysis

*Q3: What is the average rating for each product category?*

*Observation:* The output shows that most product categories have generally positive customer feedback, with average ratings above 3.50. However, some categories (e.g., 2 and 3) have lower ratings, suggesting potential areas for improvement. Further analysis of these categories could help identify specific reasons for lower feedback and identify potential solutions.

*Q4: What is the distribution of product categories based on review count?*

*Observation:* The output shows that the most reviewed Categories are Electronics, Computer & Accessories, and Home & Kitchen. Products with the highest review counts within their categories might be considered potential top sellers, even without direct sales data.

### Pricing and Discounts

*Q5: What is the distribution of discounted prices across different product categories?*

*Observation:* Products in the "Computers & Accessories" and "Electronics" categories tend to have higher discount prices compared to other categories. This suggests that these categories might use higher discounts to attract more buyers or clear out inventory.

*Q6: How do discount percentages affect the ratings of products?*

*Observation:* There is no clear correlation between discount percentages and product ratings. Products with various discount percentages show a wide range of ratings, indicating that other factors besides discounts significantly influence customer satisfaction and product ratings.

### User Behavior Analysis

*Q7: Which users have written the most reviews?*

*Observation:* The top users have written exactly 10 reviews each, indicating a cap or frequent limit of reviews per user in the dataset.

*Q8: What is the average number of reviews per user?*

*Observation:* The average number of reviews per user is approximately 6.7, suggesting moderate engagement from users in terms of providing feedback.

### Price Analysis

*Q9: How do actual prices compare to discounted prices across different categories?*

*Observation:* The scatter plot shows a clear correlation between actual prices and discounted prices, with discounted prices generally increasing as actual prices increase across categories.

*Q10: What is the average discount percentage offered in each category?*

*Observation:* Products with the highest review counts within their categories might be considered potential top sellers, even without direct sales data. The output shows that the average discount of a category ranges from 0.575 to 0.0.

### Sales Insights

*Q11: Are there certain price ranges where products receive more reviews?*

*Observation:* Products priced between 100 and 200 units receive the most reviews, suggesting higher consumer engagement in this price range.

*Q12: How do sales (inferred from rating_count) vary across different product categories?*

*Observation:* The Electronics category has the highest sales inferred from rating counts, indicating it is the most popular product category.

## Purpose:
The purpose of undertaking this project was to gain deep insights into customer behaviors and product performance on Amazon. By analyzing various aspects such as ratings, reviews, prices, and discounts, we aimed to uncover patterns and trends that could inform better decision-making for businesses.

## Impact:
From an industrial perspective, this project holds significant value:

*Enhanced Customer Understanding:* By analyzing customer ratings and reviews, businesses can better understand customer preferences and pain points. This enables them to tailor their products and services to meet customer needs effectively.

*Optimized Pricing Strategies:* The relationship between discount percentages and rating counts provides insights into how pricing strategies impact customer satisfaction and sales. Businesses can use this information to optimize their pricing models to maximize profits while maintaining high customer satisfaction.

*Product Development and Marketing:* Insights gained from the analysis can inform product development and marketing strategies. For instance, identifying the most popular product categories and features can guide businesses in developing new products or enhancing existing ones to align with market demand.

*Competitive Advantage:* Leveraging data-driven insights allows businesses to stay ahead of the competition by making informed decisions based on empirical evidence rather than intuition.

## Author
Pranay Khandagle

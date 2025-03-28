Customer Satisfaction Analysis in Simple Terms

What is Customer Satisfaction Analysis?

It is the process of understanding how happy customers are with a company’s products, services, and overall experience.

Businesses collect customer feedback through surveys, ratings, and reviews.

The goal is to improve customer experience, retain customers, and increase sales.

Dataset Used for Analysis
The dataset contains the following features:

CustomerID: Unique ID for each customer.

Age & Gender: Basic customer demographics.

PurchaseAmount & Frequency: How much and how often a customer buys.

Ratings (1-5 scale): Feedback on product quality, delivery, customer service, and website ease of use.

Return Rate & Discount Usage: How often a customer returns products and how much discount they use.

Loyalty Program Member: Whether the customer is a member or not.

Step 1: Load and Explore Data
We load the dataset using Python’s pandas library.

Checking the first few rows and summary statistics gives us an overview of the data.

Step 2: Understanding Data Through Summary Statistics
Key observations:

Average customer age: 44 years (range: 18-69).

Average purchase amount: $1065 (varies widely).

Purchase frequency: Customers buy about 14 times on average.

Average ratings: Around 3 out of 5, showing moderate satisfaction.

Return rate: 25% (some customers return up to 50% of their orders).

Discount usage: Varies significantly among customers.

Step 3: Data Visualization (Histograms)
We create graphs to understand trends:

Most customers spend less than $1000.

Purchase frequency varies, peaking around 10 and 20 purchases.

Ratings are spread out, but most cluster around 3 (neutral rating).

Return rates peak at 0.1 and 0.4, showing different levels of dissatisfaction.

Step 4: Customer Segmentation
We divide customers into groups based on:

Age Group & Gender

Young customers (18-29) give slightly higher product ratings.

Women aged 40-49 give the highest ratings, while men aged 60-69 give the lowest.

Delivery time satisfaction is fairly consistent across age groups.

Loyalty Program Membership

Members rate product quality, delivery, and customer service slightly higher than non-members.

Members use more discounts but return products at the same rate as non-members.

Step 5: Net Promoter Score (NPS) Calculation
NPS measures customer loyalty based on ratings from 0 to 10.

Customers are categorized as:

Promoters (9-10) → Happy customers

Passives (7-8) → Neutral customers

Detractors (0-6) → Unhappy customers

The NPS score in this case is -100 (extremely low satisfaction), meaning most customers are unhappy.

Step 6: Root Cause Analysis for Low Satisfaction
We analyze low ratings to find patterns:

Most dissatisfied customers are between 30-40 and 50-60 years old.

Low ratings are not just from low spenders; even frequent buyers report dissatisfaction.

High return rates are linked to low ratings, especially for product quality and website experience.

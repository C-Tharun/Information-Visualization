# Information-Visualization-Unveiling Sales Trends: A Visual Exploration of Customer Behavior and Product Performance

We have compiled two key datasets to perform an in-depth analysis of pizza sales, customer preferences, and order outcomes:

Dataset 1: Order Information
This dataset captures detailed information about pizza orders, including transaction specifics. Key variables include:

- pizza_id: Unique identifier for each pizza order.
- order_id: Identifier for each unique order.
- pizza_name_id: Identifier for each specific pizza.
- quantity: Number of pizzas ordered.
- order_date: The date of the transaction.
- order_time: The exact time of the transaction.
- total_price: The total price of the order.
- pizza_size: The size of the pizza (Small, Medium, or Large).
This dataset helps us understand customer ordering behavior, including the number of pizzas ordered, the time and date of transactions, and the corresponding total cost. It provides essential transactional data that serves as the backbone for exploring sales patterns.



Dataset 2: Pizza Details
This dataset offers detailed information about the pizzas themselves, including ingredients, pricing, and categories. Key variables include:

- pizza_name_id: Identifier for each specific pizza.
- unit_price: The price of a single pizza of the specified size.
- pizza_category: The category of the pizza (Classic, Supreme, Veggie, Chicken, etc.).
- pizza_ingredients: A list of ingredients that make up each pizza.
- pizza_name: The full name of each pizza.
This dataset provides insight into the variety of pizzas sold, their ingredient composition, and pricing, which can be used to analyze product performance across different categories.

Combining the Datasets
By merging Dataset 1 and Dataset 2 using the common identifier, pizza_name_id, we can create a complete view of the pizza ordering process. This combined dataset allows us to link transaction specifics (date, time, quantity) with detailed pizza characteristics (ingredients, price, category), providing a holistic picture of pizza sales and customer preferences.

Planned Analysis
We aim to conduct a comprehensive analysis of pizza sales trends, focusing on the following key aspects:

- Customer Preferences: Analyze which pizza categories, sizes, and ingredients are most popular among customers.
- Order Trends: Explore transaction patterns by time, date, and order size, identifying peak ordering times and popular pizza combinations.
- Pricing and Revenue Insights: Examine how pizza prices (unit and total) influence ordering behavior, and analyze revenue distribution across different pizza categories and sizes.
- Product Performance: Evaluate the performance of different pizza categories (Classic, Supreme, Veggie, Chicken) in terms of sales volume and customer preference.

Visualization and Insights
We will use a variety of visualizations, including:
- Bar Charts to represent the most popular pizza categories and their sales volumes.
- Pie Charts to show the distribution of pizza sizes ordered by customers.
- Line Charts to track order trends over time, identifying peak times for pizza orders.
- Heatmaps to uncover the correlation between order times, pizza size, and total price.
- Scatter Plots to visualize the relationship between pizza pricing and quantity ordered.

Objective
The goal of this analysis is to provide actionable insights into customer ordering behavior, product popularity, and sales patterns. By understanding these dynamics, businesses can make informed decisions regarding product offerings, pricing strategies, and marketing campaigns, ultimately enhancing customer satisfaction and maximizing sales potential.


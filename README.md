# Food-Hub-Data-Analysis
Analyzed FoodHub's customer order data to identify demand patterns across restaurants in New York. Provided actionable insights to enhance customer experience, optimize delivery operations, and improve service offerings. The analysis addressed key business questions, helping FoodHub refine its strategy and increase customer satisfaction.

# Context:
With the increasing number of restaurants in New York and the busy lifestyles of students and professionals, online food delivery services have become an essential part of daily life. FoodHub, a food aggregator company, offers users access to multiple restaurants through a single smartphone app. The app facilitates the entire order process, from placing an order to delivery, while the company earns revenue by collecting a fixed margin from each order.

# Project Overview:
In this project, I analyzed FoodHub's extensive dataset of customer orders to gain insights into the demand patterns across various restaurants. The goal was to understand these patterns to help FoodHub enhance its customer experience. By answering key business questions posed by the Data Science team, I provided actionable insights that could be used to improve the company's service offerings, optimize delivery operations, and ultimately increase customer satisfaction.

# Data Description
The data file (foodhub_order.csv)contains the different data related to a food order. The detailed data dictionary is given below.

# Data Dictionary
order_id: Unique ID of the order
customer_id: ID of the customer who ordered the food
restaurant_name: Name of the restaurant
cuisine_type: Cuisine ordered by the customer
cost: Cost of the order
day_of_the_week: Indicates whether the order is placed on a weekday or weekend (The weekday is from Monday to Friday and the weekend is Saturday and Sunday)
rating: Rating given by the customer out of 5
food_preparation_time: Time (in minutes) taken by the restaurant to prepare the food. This is calculated by taking the difference between the timestamps of the restaurant's order confirmation and the delivery person's pick-up confirmation.
delivery_time: Time (in minutes) taken by the delivery person to deliver the food package. This is calculated by taking the difference between the timestamps of the delivery person's pick-up confirmation and drop-off information

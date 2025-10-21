# FOODPANDA-DATASET-ANALYSIS
This repository contains a sample dataset representing customer orders from various food delivery services across different cities in Pakistan. It includes customer demographics, order history, payment methods, loyalty points, and delivery statuses.

 Dataset Overview

The dataset is structured to provide insights into customer behavior, order preferences, and delivery performance. It can be used for customer segmentation, churn analysis, loyalty prediction, and delivery performance analytics.

 File

food_delivery_data.csv – Main dataset file containing customer order information.

 Columns Description
Column Name	Description
customer_id	Unique identifier for the customer
gender	Gender of the customer (Male, Female, Other)
age	Age group (e.g., Adult, Senior)
city	City where the customer resides
signup_date	Date the customer signed up
order_id	Unique identifier for each order
order_date	Date when the order was placed
restaurant_name	Name of the restaurant
dish_name	Name of the ordered dish
category	Dish category (e.g., Italian, Dessert)
quantity	Number of items ordered
price	Total price of the order (PKR)
payment_method	Payment method used (e.g., Cash, Card, Wallet)
order_frequency	Number of times the customer ordered in total
last_order_date	Most recent order date
loyalty_points	Loyalty points earned by the customer
churned	Customer status (Active or Inactive)
rating	Customer rating (1–5)
rating_date	Date when the rating was given
delivery_status	Status of the delivery (e.g., Delivered, Cancelled, Delayed)
 Usage

You can use this dataset for:

Customer segmentation

Churn prediction

Delivery delay analysis

Restaurant performance tracking

Loyalty and reward program modeling 

 TOOLS FOR WORKING WITH THE DATASET
 1. Data Cleaning & Analysis

Use these tools to explore, clean, and analyze your dataset.

Tool	Description
Pandas	Python library for data manipulation and analysis (read_csv, filtering, grouping, etc.)
NumPy	Useful for numerical operations like aggregations, means, etc.
 2. Data Visualization

Visualize trends, customer behavior, or delivery status with:

Tool	Description
Matplotlib	Basic plotting library in Python
Seaborn	Statistical data visualization (heatmaps, boxplots, histograms)
Tableau / Power BI	Drag-and-drop tools for business dashboards and data storytelling

 License

This dataset is shared for educational and analytical purposes. Please attribute if used.
 Contributing

Contributions are welcome! If you want to enhance the dataset or perform analysis, feel free to fork this repository and submit a pull request.

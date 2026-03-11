# Olist E-commerce Data Analysis

## Project Overview
This project analyzes the Brazilian Olist E-commerce Public Dataset to explore sales trends, customer purchasing behaviour, and delivery performance across Brazil.  

The analysis integrates multiple relational datasets and produces an interactive Power BI dashboard that provides insights into marketplace activity, customer satisfaction, and operational performance.



## Objectives
- Clean and prepare raw e-commerce transactional data
- Integrate multiple relational tables into a single analytical dataset
- Perform exploratory data analysis (EDA)
- Identify patterns in customer behaviour and order activity
- Build an interactive Power BI dashboard for business insights



## Dataset
The dataset contains transactional data from the Olist marketplace including:

- Customers
- Orders
- Order Items
- Payments
- Products
- Sellers
- Customer Reviews
- Geolocation Data

Dataset Source:  
Brazilian E-commerce Public Dataset by Olist (Kaggle)

Kaggle Dataset Link:  
https://www./kaggle/input/datasets/organizations/olistbr/brazilian-ecommerce
https://www./kaggle/working/olist_master_cleaned.csv


## Data Preparation
Key preprocessing steps included:

- Handling missing values
- Converting date columns to datetime format
- Aggregating item-level transactions into order-level summaries
- Creating features such as delivery time and total order value
- Removing duplicate records
- Merging relational tables using `order_id` and `customer_id`



## Exploratory Data Analysis
EDA focused on identifying patterns in:

- Order activity over time
- Customer review scores
- Delivery performance
- Payment method usage
- Customer purchasing behaviour



## Key Insights
- Order activity shows seasonal variation across months
- Customer satisfaction is generally high across the marketplace
- Lower review scores appear more frequently when delivery time increases
- Most orders contain **1–2 items**, indicating focused purchasing behaviour
- Credit-based payment methods dominate transactions



## Dashboard Preview

![Power BI Dashboard](olist-eda-powerbi-dashboard-ecommerce-data-cleaning-analysis
/OlistDashboardImages
)



## Tools Used
- Python (Pandas)
- Kaggle Jupyter Notebook
- Power BI
- Data Cleaning
- Exploratory Data Analysis
- Data Visualization



## Repository Structure



## Author
Data Analysis Project by Chinthaka.##


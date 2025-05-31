# Retail-Transaction-Analysis-Extracting-Consumer-and-Sales-Insights
This project analyzes over 38,000 retail transactions to uncover insights into customer behavior, seasonal patterns, city-wise sales trends, and the impact of promotions and discounts. Implemented using Python, Pandas, Seaborn, and Matplotlib for effective data visualization and interpretation.

# Retail Transaction Analysis: Extracting Consumer and Sales Insights

This project explores a comprehensive dataset of retail transactions to analyze customer behavior, seasonal trends, and the effectiveness of promotions. By leveraging data visualization and exploratory data analysis techniques, the project offers insights that can inform marketing, inventory planning, and operational strategies.

## Dataset Overview

The dataset consists of over 38,000 transaction records with the following key features:

- **Transaction_ID** – Unique ID for each transaction
- **Date** – Timestamp of the transaction
- **Customer_Name** – Customer involved in the purchase
- **Total_Items** – Number of items purchased
- **Amount($)** – Total amount spent
- **Payment_Method** – Mode of payment used
- **City** – City of purchase
- **Store_Type** – Type of retail outlet
- **Discount_Applied** – Whether a discount was applied
- **Customer_Category** – Segment of the customer (e.g., Teenager, Homemaker)
- **Season** – Season in which the purchase occurred
- **Promotion** – Type of promotion offered, if any

## Project Objectives

- Analyze spending behavior across different store types and cities
- Identify customer segments with the highest average purchase values
- Evaluate the impact of seasonal changes on transaction volume and value
- Assess how promotions and discounts influence customer purchases
- Explore the most preferred payment methods

## Key Insights

- Convenience stores have a slightly higher average transaction value, but store type alone does not significantly influence spending.
- Certain customer categories (e.g., Teenagers) show higher responsiveness to promotional offers.
- Specific promotions, such as "Buy One Get One", are correlated with increased purchase quantities.
- Payment method preferences vary across cities and seasons.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- OpenPyXL (for Excel file reading)


## Installation and Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/raadsr15/RetailTransactionAnalysis.git
   cd RetailTransactionAnalysis

2. Install Dependencies
    ```bash
    pip install -r requirements.txt

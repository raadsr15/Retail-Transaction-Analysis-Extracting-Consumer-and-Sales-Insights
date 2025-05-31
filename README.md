# Retail-Transaction-Analysis-Extracting-Consumer-and-Sales-Insights
This project analyzes over 38,000 retail transactions to uncover insights into customer behavior, seasonal patterns, city-wise sales trends, and the impact of promotions and discounts. Implemented using Python, Pandas, Seaborn, and Matplotlib for effective data visualization and interpretation.



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

Convenience stores have the highest average transaction value, but overall differences between store types are minimal.

Convenience stores consistently show higher average spending across all seasons.

Summer yields the highest average transactions for Warehouse Clubs, Department Stores, Specialty Stores, and Convenience Stores.

Pharmacies dominate average transaction values only during winter.

Fall never records peak average spending for any store type.

Spring sees every store type (except Warehouse Clubs) reaching peak performance.

Debit cards are most commonly used in high-value transactions.

Mobile payments are popular in New York and Atlanta.

In Dallas, debit card usage is the highest while mobile payment usage is the lowest among all states.

Dallas exhibits the highest variation in payment method adoption (standard deviation: 48.98).

Miami and San Francisco show the lowest discrepancies in payment preferences.

San Francisco records the highest mean sales amount; Boston has the lowest.

Applying discounts results in $24,739 more in total sales, indicating strong effectiveness.

March has the highest recorded sales, a sharp rise from February.

Sales decline steadily from March to June, with the steepest drop between May and June.

July and August see a modest recovery in sales, though still below spring levels.

September marks the lowest sales volume of the year.

October to January shows a strong rebound in sales, peaking during the December to January transition (likely due to holidays like Black Friday and Christmas).

A sharp drop in sales occurs from January to February.

In February, May, July, and December, discounts do not significantly impact sales.

October is the only month where non-discounted sales surpass discounted sales.

In 9 out of 12 months, discounted products generate higher sales.

City-wise sales differences are minimal—only around 1% of total sales.

Houston and Miami show high fall-season sales; Chicago shows the lowest.

Miami has the greatest seasonal sales variation; it also records the lowest winter sales.

BOGO promotions slightly outperform selective discounts in total sales.

One-third of all transactions involved no promotions.

Total sales from BOGO and selective discounts differ by just 0.37%.

BOGO promotions perform best in summer.

Selective discounts are most effective in fall and spring.

All promotions perform poorly in winter and are less effective during that season.


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

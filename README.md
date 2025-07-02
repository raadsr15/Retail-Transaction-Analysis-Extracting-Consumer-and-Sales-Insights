
![Flux_Dev_A_clean_and_modern_digital_dashboard_showcasing_retai_2](https://github.com/user-attachments/assets/87976b36-6051-46fd-b055-23d66018d2c7)

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


##  Key Insights

- Convenience stores have the highest average transaction value, but differences among store types are minimal.
- Convenience stores consistently perform well across all seasons.
- Summer yields peak averages for Warehouse Clubs, Department Stores, Specialty Stores, and Convenience Stores.
- Pharmacies dominate average transaction amounts in winter.
- No store type reaches peak spending in fall.
- Spring is the dominant season for all store types except Warehouse Clubs.
- Debit cards are commonly used in high-value transactions.
- Mobile payments are popular in New York and Atlanta.
- Dallas shows the highest usage of debit cards and the lowest for mobile payments.
- Dallas has the highest variation in payment method adoption (std dev: 48.98).
- Miami and San Francisco have the lowest payment method discrepancies.
- San Francisco has the highest mean sales; Boston has the lowest.
- Discounts increase total sales by $24,739.
- March sees the highest sales, rising sharply from February.
- Sales drop from March to June, especially between May and June.
- July and August see a minor recovery, but remain below spring levels.
- September has the lowest sales volume.
- October to January period shows strong recovery, especially from December to January (likely due to holiday sales).
- Sales decline sharply again from January to February.
- In February, May, July, and December, discounts show no significant sales impact.
- October is the only month where non-discounted sales exceed discounted ones.
- In 9 of 12 months, discounts drive higher sales.
- City-wise sales differ by only about 1%.
- Houston and Miami have high fall sales; Chicago has the lowest.
- Miami shows the highest seasonal sales variance.
- Miami records the lowest sales during winter among the three compared cities.
- BOGO offers slightly outperform selective discounts in sales.
- One-third of all transactions have no promotion.
- Total sales from BOGO and selective discounts differ by only 0.37%.
- BOGO is most effective in summer; selective discounts work best in fall and spring.
- Promotions perform poorly in winter.

---


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

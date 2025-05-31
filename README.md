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

-The convenience store has the highest mean price but the mean prices of the different stores are very close to each other and we can say that the category of the stores have very little to dictate how the mean prices would vary.
-Convenient stores have higher average transaction amounts across all seasons compared to other store types.
-Average transaction amounts dominate during summer for Warehouse Club, Department Store, Speciality Store and Convenience Store.
-Only Pharmacy dominates the average transaction amounts during Winter
-The average transaction amount never reaches it's peak for any type of store during Fall.
-Other than the Warehouse Club every other store has a dominating position during Spring.
-Convenient stores have higher average transaction amounts across all seasons compared to other store types.
-Average transaction amounts dominate during summer for Warehouse Club, Department Store, Speciality Store and Convenience Store.
-Only Pharmacy dominates the average transaction amounts during Winter.
-The average transaction amount never reach it's peak for any type of store during Fall.
-Other than the Warehouse Club every other store has a dominating position during Spring.
-Debit cards are most commonly used in high value transactions.
-Mobile Payments are popular in New York and Atalanta
-Debit card recorded the highest usage as a payment method considering all states which is in the state of Dallas. Mobile payment recorded the lowest usage as a payment method considering all states which is in the state 
 of Dallas as well.
-Dallas has the overall higest discrepancy in the adoption of payment methods. It has a standard deviation of 48.98 which is almost twice as much as any other state.
-Miami and San Francisco has the overall lowest discrepancy in the adoption of payment methods.
-San Francisco has the highest mean amount of sales while Boston has the lowest mean amount of sales.
-Total Sales Amount is 24739 $ higher when discount is applied so it's a very significant amount.
-The highest sales recorded is during March which is a sharp increase from the month of February
-The sales amount drops drastically from March up till June and the sharpest transition takes place from May to June.
-During July and August the sales rise to a degree but still inferior compared the March to May prices.
-September marks the lowest sales recorded.
-The sales again show a significant rise for the October to January period. The sales show a sharp increase during the transition from December to January. There might be factors such as Black Friday or Christmas Sale 
 which impacts this.
-The sales significantly fall during the January to February Transition.
-During February, July, May and December the presence of discount does not have any significant impact on sales amounts.
-Only in the month of October the sales amount without discount is unexpectedly higher than the sales with discount.
-The 7 other months of the year, the sales amount with discount have been higher compared to without discounted products. But if we consider the extremes then 9 out of 12 months have more sales with discount applied than 
 without it.
-The Sales diffences between the cities are only around 1% of the total sales.
-Houston and Miami has significantly high sales amount during Fall whereas Chicago has the lowest during Fall.
-The deviation of sales amount is highest in Miami season wise.
-Compared to Chicago and Houston only Miami has the lowest sell in Winter.
-BOGO offers have slightly high amount of sales compared to discounts on selected items.
-One third of the total transactions have no kind of promotions.
-The total sales amount from BOGO and Selective discount is very identical with only 0.37% difference.
-BOGO offers have shown remarkable success during Summer seasons.
-Selective discounts boost sales remarkably during fall and spring.
-All kinds of promotions perform quite poor in winter. So they are not appropriate for winter sales.


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

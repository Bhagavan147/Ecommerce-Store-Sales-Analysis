# Ecommerce Store Sales Analysis


**Transaction Table**

| Column                 | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| HOUSEHOLD_KEY          | Unique identifier for each household                                         |
| BASKET_ID              | Unique identifier for each purchase occasion                                 |
| DAY                     | Day of the transaction                                                        |
| PRODUCT_ID             | Unique identifier for each product                                            |
| QUANTITY               | Number of products purchased in the transaction                              |
| SALES_VALUE            | Total dollar amount of the transaction                                        |
| STORE_ID               | Unique identifier for the store where the transaction occurred               |
| COUPON_MATCH_DISC      | Discount applied due to retailer matching a manufacturer coupon              |
| COUPON_DISC            | Discount applied due to a manufacturer coupon                                 |
| RETAIL_DISC            | Discount applied due to retailer's loyalty card program                      |
| TRANS_TIME             | Time of day when the transaction occurred                                    |
| WEEK_NO                | Week number of the transaction (1-102)                                        |


**Demographic Table**

| Column                 | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| HOUSEHOLD_KEY          | Unique identifier assigned to each household                                 |
| AGE_DESC               | Estimated age range for the primary resident(s)                              |
| MARITAL_STATUS_CODE    | Marital status of the primary resident(s), coded as A (Married), B (Single), or U (Unknown) |
| INCOME_DESC            | Estimated household income level                                             |
| HOMEOWNER_DESC         | Homeownership status (e.g., homeowner, renter, etc.)                         |
| HH_COMP_DESC           | Composition of the household (e.g., single person, couple, family with children, etc.) |
| HOUSEHOLD_SIZE_DESC    | Number of individuals in the household                                        |
| KID_CATEGORY_DESC      | Number of children in the household (up to 3+)                               |


**Product Table**

| Column                | Description                                                                 |
|-----------------------|-----------------------------------------------------------------------------|
| PRODUCT_ID            | Each product's unique ID number                                               |
| DEPARTMENT            | Category of similar products                                                 |
| COMMODITY_DESC        | Subcategory of similar products                                              |
| SUB_COMMODITY_DESC    | Specific type of product within a subcategory                               |
| MANUFACTURER          | The company that makes the product                                           |
| BRAND                 | Whether it's a store brand or a national brand                               |
| CURR_SIZE_OF_PRODUCT  | Size of the product package (not always available)                           |

The analysis of these three tables* *Transaction**, **Demographic**, and **Product** of an Ecommerce Store was conducted using SQL to gain insights of the store performance. By joining and aggregating data across these tables, key metrics such as sales value, quantity sold, and customer demographics were analyzed to identify trends and patterns. SQL queries helped to perform detailed segmentation, uncover purchasing behaviors, and evaluate product performance. 

The findings were then visualized in a Tableau dashboard, which provided an interactive view of the sales, customer demographics, and product data. The dashboard enabled users to drill down into specific metrics such as total sales, quantities, and customer characteristics by product category, region, and other factors, offering actionable insights for strategic decision-making.

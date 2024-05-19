## Retail Orders Data Analysis using Spark

### Answer the following questions using the [retails orders dataset](https://www.kaggle.com/datasets/ankitbansal06/retail-orders).
1. Find the top 10 highest revenue generating products.
2. Find the top 5 highest selling products in each region
3. Find the month over month growth comparison for 2022 and 2023 sales.
    E.g. : Growth Comparison of Jan 2022 vs Jan 2023
4. For each category which month had highest sales.
5. Which sub-category had the highest profit growth in 2023 as compare to 2022.

### Steps:

1. Download the retail orders dataset from Kaggle.
    Location: https://www.kaggle.com/datasets/ankitbansal06/retail-orders
2. Unzip the data file.
3. Data Clensing
    <ol>
    <li> Clean 'Ship Mode' column, replace 'Not Available', 'unknown' with null. </li>
    <li> Standardize Column Names - remove spaces and make them lower case.</li>
    </ol>
4. Derive New Columns : (1) Discount , (2) Sale Price and (3)Profit.
5. Answer the above questions using SQL.

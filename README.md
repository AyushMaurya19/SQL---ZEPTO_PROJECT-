# SQL---ZEPTO_PROJECT-
**📦 Download Data** <br>
The dataset is downloaded from Kaggle in .csv format.

**🎯 Objectives**<br>
1. ✅ Design a structured product database from raw Kaggle data.
2. ✅ Practice data import, table creation, and SQL data types.
3. ✅ Perform detailed data exploration and cleaning to ensure data quality.
4. ✅ Develop practical SQL queries to extract meaningful business insights.
5. ✅ Analyze product discounts, pricing, stock availability, and inventory distribution.
6. ✅ Provide actionable insights to support better inventory and pricing decisions.

**🛠️ Tools Used**<br>
1. Kaggle — To source and download the raw dataset in CSV format.
2. MySQL — For database creation, table design, data storage, and SQL query execution.
3. SQL Workbench / MySQL Workbench (or your SQL IDE of choice) — For writing, testing, and running SQL scripts.
   
**📊 Dataset**<br>
The dataset consists of retail transaction records for Zepto. It includes:


| Column Name                | Description                                               |
| -------------------------- | --------------------------------------------------------- |
| `CATEGORY`                 | The product category/type (e.g., Grocery, Dairy, Snacks). |
| `NAME`                     | The name of the product.                                  |
| `MRP`                      | Maximum Retail Price of the product (before discounts).   |
| `DISCOUNT_PERCENT`         | Percentage of discount applied to the MRP.                |
| `AVAILABLE_QUANTITY`       | Number of units available in stock.                       |
| `DISCOUNTED_SELLING_PRICE` | Final selling price after applying the discount.          |
| `WEIGHT_IN_GRAMS`          | Weight of the product in grams.                           |
| `OUT_OF_STOCK`             | Boolean flag: 1 if out of stock, 0 if available.          |
| `QUANTITY`                 | The total quantity detail per record.                     |

📈 Key Performance Indicators (KPIs)
The project measures and analyzes the following KPIs using SQL:
1. Top Discounts: <br>
.Identify products with the highest discount percentages to find best-value deals. 
2. High-Value Out-of-Stock Products:<br>
Spot expensive items that are out of stock to highlight lost revenue opportunities.
3. Estimated Revenue:<br>
Calculate the total potential revenue for each product category based on current stock and selling price. 
4. High MRP, Low Discount Products:<br>
Find premium-priced items with minimal discounts for margin analysis. (Q4)
5. Average Discount by Category:<br>
Determine which categories offer the highest average discounts to inform promotional strategies. 
6. Price per Gram:<br>
Compute the cost efficiency of products based on price per unit weight. 
7. Weight-Based Segmentation:<br>
Group products into weight categories: Low, Medium, and Bulk, for better inventory planning. 
8. Total Inventory Weight:<br>
Analyze the total weight of available stock per category to assess logistics and storage needs.

**🔍 .Business Insight Queries** <br>
Solved real-world business problems using SQL queries, including:<br>

Q1. Find the top 10 best-value products based on the discount percentage.<br>
Q2.What are the Products with High MRP but Out of Stock.<br>
Q3.Calculate Estimated Revenue for each category.<br>
Q4. Find all products where MRP is greater than 500 and discount is less than 10%.<br>
Q5. Identify the top 5 categories offering the highest average discount percentage.<br>
Q6. Find the price per gram for products above 100g and sort by best value.<br>
Q7.Group the products into categories like Low, Medium, Bulk.<br>
08.What is the Total Inventory Weight Per Category.<br>

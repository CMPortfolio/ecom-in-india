# E-commerce Data Analysis: Pricing and Discount Trends

## Project Overview:
This project analyzes e-commerce transaction data to provide insights into pricing trends, the effect of discounts on final prices, and the variation of prices across different product categories. The dataset represents e-commerce transactions, including details such as product ID, category, price, discounts, payment methods, and purchase dates.

### Business Questions:
1. **How do e-commerce prices vary by month?**
2. **What is the average price across different product categories?**
3. **How do discounts affect the final price of products?**

## Libraries Used:
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For data visualization, including bar charts and scatter plots.
- **NumPy**: For numerical operations and handling missing values.

## Dataset:
The dataset used in this project contains the following columns:
- **User_ID**: The ID of the user.
- **Product_ID**: Unique identifier for the product.
- **Category**: Product category.
- **Price (Rs.)**: Original price in INR.
- **Discount (%)**: Discount offered on the product.
- **Final_Price(Rs.)**: Final price after applying the discount.
- **Payment_Method**: Payment method used for the transaction.
- **Purchase_Date**: Date of the purchase.

## Data Preprocessing:
- **Handling Missing Values**: Missing values were handled by replacing them with appropriate methods such as median imputation or removal.
- **Conversion of Data Types**: Data types such as `Price (Rs.)` and `Final_Price(Rs.)` were converted into numeric types. The `Purchase_Date` column was converted to datetime format for easier analysis.
- **Currency Conversion**: Prices were converted from INR (Indian Rupees) to USD using a conversion rate of 1 INR = 0.01 USD.

## Analysis and Results:

### 1. Average Price by Month:
We analyzed the variation in average product prices across different months. The average price shows slight fluctuations throughout the year, with higher prices observed during certain months.

![Average Price by Month](path_to_image/avg_price_by_month.png)

### 2. Average Price by Category:
The analysis revealed that product categories such as **Beauty**, **Clothing**, and **Toys** tend to have higher average prices compared to others like **Books** and **Electronics**.

![Average Price by Category](path_to_image/avg_price_by_category.png)

### 3. Discount Effect on Final Price:
A scatter plot of **Discount (%)** vs. **Final Price (USD)** indicates that discounts have a significant impact on the final price, with certain discounts leading to larger reductions in price.

![Discount vs Final Price](path_to_image/discount_vs_final_price.png)

## Conclusion:
The analysis provides valuable insights for e-commerce businesses in India. Understanding the seasonal pricing trends, category-based price variations, and the relationship between discounts and final price can help businesses make informed decisions regarding pricing strategies and discount offers.


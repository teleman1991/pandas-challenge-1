# pandas-challenge-1

## Requirements

### Explore the Data (30 points)
1. View the column names. (4 points) - **Done**
2. Use the `describe` function. (4 points) - **Done**
3. Identify the category with the most entries. (4 points) - **Done**
4. Identify the subcategory with the most entries in that category. (5 points) - **Done**
5. Identify the 5 clients with the most entries. (5 points) - **Done**
6. Store the client IDs of the top 5 clients in a list. (4 points) - **Done**
7. Display the total units (from the `qty` column) ordered by the top client. (4 points) - **Done**

### Transform the Data (30 points)
1. Create a column for the subtotal using `unit_price` and `qty`. (6 points) - **Done**
2. Create a column for the shipping price: $7 per pound for orders over 50 pounds, $10 per pound for orders 50 pounds or under. (6 points) - **Done**
3. Create a column for the total price using the subtotal, shipping price, and a 9.25% sales tax. (6 points) - **Done**
4. Create a column for the cost using `unit_cost`, `qty`, and shipping price. (6 points) - **Done**
5. Create a column for the profit using the line cost and line price. (6 points) - **Done**

### Confirm Your Work (15 points)
1. Confirm that Order ID 2742071 had a total price of $152,811.89. (5 points) - **Done**
2. Confirm that Order ID 2173913 had a total price of $162,388.71. (5 points) - **Done**
3. Confirm that Order ID 6128929 had a total price of $923,441.25. (5 points) - **Done**

### Summarize and Analyze (25 points)
1. Calculate the total revenue from each of the top 5 clients. (5 points) - **Done**
2. Create a summary DataFrame showing total units purchased, total shipping price, total revenue, and total profit for the top 5 clients. (5 points) - **Done**
3. Create a function to change the currency to millions of dollars, format the data, rename columns for presentation, and sort the DataFrame by total profits in descending order. (5 points) - **Done**
4. Write a brief 2-3 sentence summary of your findings. (10 points) - **Done**

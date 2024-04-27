# HotWax
Q1. Check status of your order?
Ans. Let order id of your order be 'O1' then the query will be as follows

# SELECT status FROM orders WHERE order_id = 'O1';

Q2. Find total amount of your order ?
Ans. To find the total amount of each order, use the SQL SELECT statement along with the SUM() function to calculate the total amount for each order , then the SQL query will be:

# SELECT order_id, SUM(total) AS total_amount FROM orders GROUP BY order_id;

Q3. Update your city ?
Ans. To Update city , use the SQL  UPDATE statement along with SET , then the SQL query will be :

# UPDATE address SET city = 'Dewas' where pincode = 452001;

Q4. change product_description in product table ?
Ans. To change product description in product table , use the SQL  UPDATE statement along with SET , then the SQL query will be :

# UPDATE products SET product_description = 'this is a good phone' WHERE product_id = 'P1';

Q5. Display returnable products ?
Ans. To display returnable products , use the SELECT statement along with WHERE CLAUSE , then the SQL query will be :

# SELECT * FROM products WHERE product_returnable = 'Yes';

Q6. Generate er diagram ?
Ans. ER Diagram is attached with the repo
 

# Repo-Proyecto-4
“Repository containing a Data Analysis project with Pandas and included visualizations with Matplotlib.”

Instacart is a grocery delivery platform where customers can place an order and have it delivered, similar to Uber Eats and DoorDash.
The dataset provided has been modified from the original. We reduced its size to speed up calculations and introduced missing values and duplicates. We were careful to preserve the original data distributions when making these changes.

You must complete three steps. For each step, write a brief introduction clearly describing how you intend to solve it, and provide explanatory paragraphs that justify your decisions as you progress through your solution. Also include a conclusion summarizing your findings and choices.

There are five tables in the dataset, and you will need to use all of them to perform data preprocessing and exploratory data analysis. Below is a data dictionary listing the columns in each table and describing the information they contain.

instacart_orders.csv: 

* 'order_id': unique ID number identifying each order.

* 'user_id': unique ID number identifying each customer account.

* 'order_number': the number of times this customer has placed an order.

* 'order_dow': day of the week the order was placed (0 = Sunday).

* 'order_hour_of_day': hour of the day the order was placed.

* 'days_since_prior_order': number of days since the customer's previous order.

products.csv: each row corresponds to a unique product available for customers to purchase.

* 'product_id': unique ID number identifying each product.

* 'product_name': name of the product.

* 'aisle_id': unique ID number identifying each grocery aisle category.

* 'department_id': unique ID number identifying each grocery department.

order_products.csv: each row corresponds to an item included in an order.

* 'order_id': unique ID number identifying each order.

* 'product_id': unique ID number identifying each product.

* 'add_to_cart_order': sequential position in which each item was added to the cart.

* 'reordered': 0 if the customer has never ordered the product before, 1 if they have.

aisles.csv

* 'aisle_id': unique ID number identifying each grocery aisle category.

* 'aisle': name of the aisle.

departments.csv

* 'department_id': unique ID number identifying each grocery department.

* 'department': name of the department.
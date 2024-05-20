
# Overview🎯

The Look E-commerce Dataset provides a comprehensive view of online retail operations, encompassing various dimensions such as sales transactions, customer information, product attributes, website engagement metrics, logistics and additional metadata. This dataset serves as a valuable resource for analyzing and understanding the dynamics of e-commerce business activities.

Our goal is consumer behavior analysis by customer segmentation: segment customers based on demographics and purchasing behavior. This enables us to tailor marketing strategies and product offerings to different customer segments, enhancing customer satisfaction and loyalty.


## Tools💡

- BigQuery (SQL) to clean data and join some tables.🧽
- Power Bi to create dashboard.📊



## Dataset’s Tables and Relationships✨

1.	distribution_centers:
o	This table stores information about distribution centers.
o	Fields: id, name, latitude, longitude

2.	events:
o	This table records various events related to user interactions.
o	Fields: id, user_id, sequence_number, session_id, created_at, ip_address, city

3.	inventory_items:
o	This table maintains a record of inventory items.
o	Fields: id, product_id, created_at, sold_at, cost, product_category, product_name, product_brand, product_retail_price, product_department, product_sku, product_distribu

4.	order_items:
o	This table contains information about items included in orders.
o	Fields: id, order_id, user_id, product_id, inventory_item_id, status, created_at, shipped_at

5.	orders:
o	This table stores data related to orders placed by users.
o	Fields: order_id, user_id, status, gender, created_at, returned_at, shipped_at, delivered_at, num_of_item

6.	products:
o	This table contains information about products available for sale.
o	Fields: id, cost, category, name, brand, retail_price, department, sku, distribution_center

7.	users:
o	This table stores user information.
o	Fields: id, first_name, last_name, email, age, gender, state, street_address, postal_code, city, country

Relationships:
Using the Model view look for the relationship between the different tables


![The Relationships of tables](https://github.com/Raneem16/The_Look_E-Commerce/assets/133536932/0a817a0b-58d7-4c62-b5f2-6a5e96d411d9)

## Dashboard📊

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)



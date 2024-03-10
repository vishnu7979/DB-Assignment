 Answers to Database Assignment Questions :-

 Question 1: Relationship between "Product" and "Product_Category" entities

The relationship between the "Product" and "Product_Category" entities can be described as a one-to-many relationship. Each product can belong to only one product category, but a product category can have multiple products associated with it. This relationship is established through the foreign key category_id in the "Product" table, which references the primary key in the "Product_Category" table.

 Question 2: Ensuring Valid Category Assignment for Products

To ensure that each product in the "Product" table has a valid category assigned to it, the following steps can be taken:

1. Define a foreign key constraint in the database schema, linking the category_id column in the "Product" table to the primary key (category_id) in the "Product_Category" table.
2. Enforce referential integrity to ensure that each value in the category_id column of the "Product" table exists as a primary key value in the "Product_Category" table.
3. Implement data validation rules at the application level to prevent users from selecting non-existent categories and to double-check data integrity before database operations.
 


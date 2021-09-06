# Inventory-Management-System-for-Skill-India-AI-ML-internship
This repository includes the required code files needed to execute an inventory management system implemented using the concepts in python programming language

# Learning outcomes
This implementation will help understand the features of python programming language and their collaboration to build a project

# Features

## 1. IMS add products :
a) An inventory can be created and copied to a records.json file
b) The contents of records.json file can be accessed in the program
c) New products can be added/inserted into the inventory by preventing different products to have same ids
d) Existing products can be removed/deleted from the inventory
e) Values of attributes of the products can be updated by validating their new values
f) selected records can be displayed based on whether they satisfy certain constrainsts or not
g) records can be sorted based on the attribute values in ascending or descending order
h) total number of products along with the product with the highest quantity and the product with the least quantity present in the inventory can be displayed

## 2. IMS purchase products :
a) Customers can purchase different types of products having different attributes like name, cost price, MRP, selling price, discount, weight, type, manufacturing and expiry details present in the inventory only if they are not expired
b) Customer details can be saved
c) Customers can purchase more than one product at a time
d) Discount may or may not be applied based on whether he/she is a VIP customer or not
e) If purchase quantity exceeds the available the deficiency is noted and later on the quantity can be updated explicitly
f) If the quantity of a product becomes zzero in the inventory then it is notified
g) If a product is expired customer is notified and disallowed to buy it
h) The shopping cart is created
i) A final receipt with the billing amount is displayed highlighting the products, discount if applied, selling price, amount saved due to discount
j) Also the daily sales report is filed for each customer's purchases also indicating the deficiencies or unavailability of the products if any
k) Sales report can be reviewd for future references

## 3. records.json file :
a) It holds the record of the items wit htheir attribute values in the inventory
b) It is updated each time an item is inserted, deleted or if its quantity reduces on purchase

## 4. sales.json file:
a) It holds the purchases made by a customer

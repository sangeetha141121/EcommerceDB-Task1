# EcommerceDB-Task1
Database schema design for an E-commerce system with Customers, Products, Orders, Categories, Payments.
# EcommerceDB-Task1

## Overview
This project contains the schema design for an E-commerce system.  
It includes tables for Customers, Products, Orders, OrderDetails, Categories, and Payments.

## Entities
- **Customers**: Stores customer details
- **Products**: Items available for purchase
- **Orders**: Transactions made by customers
- **OrderDetails**: Line items in each order
- **Categories**: Groups products
- **Payments**: Payment info for each order

## Relationships
- One Customer → Many Orders
- One Order → Many Products (via OrderDetails)
- One Product → One Category
- One Order → One Payment

## Files in this Repository
- `schema.sql`: SQL script for creating the database schema
- `ERdiagram1.pdf`: ER diagram showing entities and relationships
- `README.md`: Documentation of the project

## Tools Used
- pgAdmin (for SQL script)
- dbdiagram.io (for ER diagram)
- GitHub (for version control and submission)

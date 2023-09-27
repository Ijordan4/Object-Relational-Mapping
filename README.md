##Ecommerce-BackEnd

## Description: This project is the back end for an e-commerce website built with Node.js, Express.js, Sequelize, and MySQL. It includes database models for products, categories, users, and orders, as well as routes for managing these resources.

##Installation:

## Clone the repository:


git clone https://github.com/ijordan4/Object-Relational-Mapping.git
## Navigate to the project directory:

cd Ecommerce-BackEnd
## Install dependencies:

npm install

## Usage:

Create a .env file in the project root directory and set your environment variables for database connection:

DB_NAME=your_database_name
DB_USER=your_database_user
DB_PASSWORD=your_database_password
Seed the database with initial data:

node seeds/index.js

## Start the server:
npm start

## API Endpoints:

GET /api/products: Get all products.
POST /api/products: Create a new product.
GET /api/products/:id: Get a specific product by ID.
PUT /api/products/:id: Update a specific product by ID.
DELETE /api/products/:id: Delete a specific product by ID.
Categories:

GET /api/categories: Get all categories.
POST /api/categories: Create a new category.
GET /api/categories/:id: Get a specific category by ID.
PUT /api/categories/:id: Update a specific category by ID.
DELETE /api/categories/:id: Delete a specific category by ID.
Users (authentication and authorization not implemented in this basic example):

POST /api/users: Create a new user.
GET /api/users/:id: Get a specific user by ID.
PUT /api/users/:id: Update a specific user by ID.
DELETE /api/users/:id: Delete a specific user by ID.
Orders:

GET /api/orders: Get all orders.
POST /api/orders: Create a new order.
GET /api/orders/:id: Get a specific order by ID.
PUT /api/orders/:id: Update a specific order by ID.
DELETE /api/orders/:id: Delete a specific order by ID.
Contributing:

If you'd like to contribute to this project, please open an issue or submit a pull request on GitHub.

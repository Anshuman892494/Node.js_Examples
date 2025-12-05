<img width="1098" height="684" alt="image" src="https://github.com/user-attachments/assets/7f99acdd-e886-4d3a-8064-c3782f623508" />

## Node.js_Examples
Product CRUD Application (Node.js + Express + MongoDB)

# This project is a simple CRUD (Create, Read, Update, Delete) application built using:

Node.js

Express.js

MongoDB + Mongoose

HTML form (Frontend)

Environment variables (.env)

It demonstrates how to build a complete backend web application with full database operations.

## Features
# 1. Create Product

Insert a new product with:

Name

Price

# 2. Read All Products

Display all stored products in a table format.

# 3. Update Product

Update an existing product using its MongoDB ID.

#4. Delete Product

Delete a product using its ID.

# Environment Variables

Create a .env file in the root folder:

PORT=3000
MONGO_URL=mongodb://localhost:27017/mydatabase


# Install dotenv:

npm install dotenv

## Installation & Setup
# 1. Clone the Repository
git clone <repo-url>
cd project

# 2. Install Dependencies
npm install

# 3. Start MongoDB

Ensure MongoDB is running locally on your system.

# 4. Start the Server
npm start


Server runs at:

http://localhost:3000

# Available Routes
GET /

# Returns the HTML form.

POST /add

# Creates a new product.

POST /read

# Lists all products.

POST /update

# Updates product by ID.

POST /delete

# Deletes product by ID.

Tech Stack
Technology	Purpose
Node.js	JavaScript runtime
Express.js	Web framework
MongoDB	Database
Mongoose	ODM for MongoDB
dotenv	Load environment variables
How to Use

# Open the home page.

Use the form to:

Add a product

Read all products

Update a product

Delete a product

# License

This project is free to use and modify.

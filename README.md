<h1><p align="center"><b><b>FunkyTee Ecommerse API Backend</b></b>
</p></h1>
This repository contains the backend API for a robust e-commerce platform developed using the MERN stack. The API provides essential functionalities for user authentication, category management, and product operations.


<p align="center">
  <img alt="Ecommerse Backend API BASED" src="https://github.com/chandrika1645/FunkyTee-App/blob/main/client/build/images/new-logo.png">
   <div align="center">
   <h1>
      FUNKYTEE
      ONLINE SHOPPING
   </h1>
   </div>
</p>


## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation & Setup](#installation--setup)
- [Starting the Application](#starting-the-application)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

To run this project, you'll need:

- A laptop or computer.
- [Node.js and NPM](https://nodejs.org/).
- Mongodb database.

## Installation & Setup

## 1. Clone the repository:
   bash
   git clone https://github.com/chandrika1645/FunkyTee-App.git
   


## 2. Install dependencies:
  
      npm install
  


## 3. Database Setup:
- Create a MongoDB database and take note of your connection configurations.
- Rename .env.example to .env and fill in your database details:

      MONGODB_URI=your_mongo_connection_uri
      JWT_TOKEN_SECRET=your_secret_key

# Starting the Application

## 1. Start the app:

     node app.js


The application should now be running on 'http://localhost:3000'.

# API Endpoints

## Authentication API Endpoints
• /register: Sign up a new user.
• /login: User authentication.
• /forgot-password: Reset password for existing users.
• /user-auth: User authentication middleware.
• /admin-auth: Admin authentication middleware.
• /profile: User profile management.
• /orders: Manage user-specific orders.
• /all-orders: Retrieve all orders.
• /order-status/:orderId: Check order status.

## Category Operations API Endpoints
• /create-category: Create a new category.
• /update-category/:id: Update an existing category.
• /get-category: Fetch all categories.
• /single-category/:slug: Fetch a single category.
• /delete-category/:id: Delete a category.

## Product Operations API Endpoints
• /create-product: Add a new product.
• /update-product/:pid: Update an existing product.
• /get-product: Get all products.
• /get-product/:slug: Get a single product by slug.
• /product-photo/:pid: Fetch product photo.
• /delete-product/:pid: Delete a product.
• /product-filters: Filter products.
• /product-count: Count total products.
• /product-list/:page: Paginated product list.
• /search/:keyword: Search products.
• /related-product/:pid/:cid: Retrieve related products.
• /product-category/:slug: Retrieve products by category.
• /braintree/token: Get Braintree token for payment.
• /braintree/payment: Process payments using Braintree.



# Contributing

- Wish to contribute? Feel free to open a pull request. For significant changes, kindly open an issue first to deliberate what you'd prefer to change.

# License

- This project is open-source and available under the MIT License
<h1></h1>
<p align="center">
  <img alt="Ecommerse Backend API BASED" src="https://github.com/chandrika1645/FunkyTee-App/blob/main/client/build/images/banner.jpg">
</p>

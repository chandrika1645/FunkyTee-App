This repository contains the backend API for FunkyTee, an e-commerce platform developed using the MERN stack. The application provides essential features such as user authentication, category management, product operations, and payment integration.

Although the frontend was initially built with React, only the production build files remain. When the backend runs on port 8080, it automatically serves the frontend.

Preview

Below are screenshots of different pages of the application located in the app-preview folder:

## Home Page

 <img src="https://raw.githubusercontent.com/chandrika1645/FunkyTee-App/main/app-preview/home-page.png" width="700">

 ## Header 
 
 <img src="https://raw.githubusercontent.com/chandrika1645/FunkyTee-App/main/app-preview/header.png" width="700">

## Product Page

 <img src="https://raw.githubusercontent.com/chandrika1645/FunkyTee-App/main/app-preview/all-products.png" width="700">

## Category Page

 <img src="https://raw.githubusercontent.com/chandrika1645/FunkyTee-App/main/app-preview/category-page.png" width="700">


## Checkout Page

 <img src="https://raw.githubusercontent.com/chandrika1645/FunkyTee-App/main/app-preview/checkout-page.png" width="700">


## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation & Setup](#installation--setup)
- [Starting the Application](#starting-the-application)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

    - Node.js and NPM
    - Mongodb database.

## Installation & Setup

## 1. Clone the repository:
    bash
    git clone https://github.com/chandrika1645/FunkyTee-App.git
   


## 2. Install dependencies:
  
    npm install
  


## 3. Database Setup:
Create a MongoDB database and update the .env file with your connection details:

    PORT=8080
    DEV_MODE=development
    MONGO_URL=<your-mongo-url>
    JWT_SECRET=<your-secret-key>
    BRAINTREE_MERCHANT_ID=<your-merchant-id>
    BRAINTREE_PUBLIC_KEY=<your-public-key>
    BRAINTREE_PRIVATE_KEY=<your-private-key>

# Starting the Application

## 1. Start the app:

    npm run start


The application should now be running on 'http://localhost:8080'.

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

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.


<h1></h1>
<p align="center">
  <img alt="Ecommerse Backend API BASED" src="https://github.com/chandrika1645/FunkyTee-App/blob/main/client/build/images/banner.jpg">
</p>

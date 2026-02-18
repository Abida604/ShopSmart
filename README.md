# ShopSmart
🛒 ShopSmart – Digital Grocery Store (MERN Stack)

Overview

ShopSmart is a full-stack digital grocery web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js).

The platform provides a seamless online grocery shopping experience for customers while offering powerful management tools for sellers and administrators.

It replicates real-world e-commerce platforms like:

Amazon

Flipkart

BigBasket

 Key Features
 Customer Module

Secure Registration & Login (JWT Authentication)

Browse & Search Grocery Products

Add to Cart & Checkout

View Order History

Track Orders

 Seller Module

Add / Edit / Delete Products

Manage Inventory

View Incoming Orders

 Admin Module

Approve / Reject Sellers

Manage Users

Monitor Orders

View Platform Analytics

 System Architecture
 Frontend

React.js

React Bootstrap

Axios

Context API

 Backend

Node.js

Express.js

RESTful APIs

 Database

MongoDB

Mongoose ODM

 Authentication & Security

JSON Web Tokens (JWT)

Password hashing using bcrypt

Role-Based Access Control (RBAC)

Protected Routes

 Workflow

User registers and logs in.

Authentication token is generated using JWT.

User browses products and adds items to cart.

Orders are stored in MongoDB.

Admin and Sellers manage operations through dedicated dashboards.

 Database Collections

Users

Products

Orders

Sellers

 Deployment

Frontend: GitHub Pages

Backend: Render

 Challenges Faced

Managing global state across multiple components

Implementing secure role-based authentication

Handling cart synchronization

Designing scalable API architecture

 Future Enhancements

AI-based product recommendation system

Online payment gateway integration

Real-time order tracking

Inventory prediction using Machine Learning

Cloud-native deployment with CI/CD

Why MERN Stack?

The MERN stack was chosen because:

JavaScript is used throughout the application

Efficient for scalable full-stack development

Strong community support

Fast development cycle


ShopSmart demonstrates a complete real-world e-commerce workflow with secure authentication, structured database design, and role-based access control.

The project highlights strong full-stack development skills and practical implementation of modern web technologies.

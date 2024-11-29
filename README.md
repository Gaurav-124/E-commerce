E-commerce Platform
An advanced e-commerce platform with features for user authentication, authorization, and role-based access control (RBAC). This project demonstrates secure access management, role-specific functionalities, and scalable design.

Features
User Authentication:

Secure registration and login using hashed passwords (bcrypt).
JSON Web Token (JWT) for session management.
Role-Based Access Control (RBAC):

User roles include Admin, Seller, and Customer.
Each role has specific permissions:
Admin: Full control over users and products.
Seller: Manage products they own.
Customer: Browse and purchase products.
Authorization:

Middleware ensures restricted access to protected routes based on roles.
Unauthorized actions are logged and blocked.
Product Management:

Add, update, delete, and view products with role-based restrictions.
Getting Started
Prerequisites
Node.js installed
MongoDB running locally or on a cloud
Package manager: npm

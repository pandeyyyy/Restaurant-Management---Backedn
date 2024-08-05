# Restaurant-Management---Backend

This is a RESTful backend service for managing restaurant operations, built using Golang. The project aims to provide a comprehensive solution for managing various aspects of restaurant operations such as menu management, order processing, and user authentication.

Features
User Authentication: Secure user registration and login functionality using JWT (JSON Web Tokens).
Role-Based Access Control: Different access permissions for admins, staff, and customers.
Menu Management: CRUD operations for managing restaurant menus.
Order Management: Create, read, update, and delete orders with status tracking.
Table Management: Assign and manage tables for different customers.
Payment Integration: Support for integrating with various payment gateways.
API Documentation: Detailed API documentation with Swagger.
Technologies Used
Golang: The main programming language used for the backend.
Gin: A web framework for building fast and scalable web applications in Golang.
Gorm: An ORM library for Golang.
JWT: Used for securing endpoints with JSON Web Tokens.
PostgreSQL: The database used for storing all application data.
Swagger: For API documentation.
API Endpoints
The following are some of the key API endpoints available:

User Authentication

POST /auth/register - Register a new user
POST /auth/login - Login and obtain a JWT
Menu Management

GET /menus - Get all menu items
POST /menus - Add a new menu item
PUT /menus/:id - Update a menu item
DELETE /menus/:id - Delete a menu item
Order Management

GET /orders - Get all orders
POST /orders - Create a new order
PUT /orders/:id - Update an order
DELETE /orders/:id - Delete an order
Table Management

GET /tables - Get all tables
POST /tables - Add a new table
PUT /tables/:id - Update a table
DELETE /tables/:id - Delete a table

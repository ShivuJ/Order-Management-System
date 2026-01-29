# Order-Management-System
🧠 Project Overview

This project is a backend system that simulates a real-world e-commerce order and inventory workflow. It provides RESTful APIs to manage users, products, and orders, with business logic to validate stock and calculate order totals.

The project starts as a monolithic Spring Boot application and is later refactored into microservices using Spring Cloud components such as Eureka and API Gateway.

🚀 Features
🔹 User Management

Create, update, and soft delete users

Fetch user details

🔹 Product & Inventory Management

Add and update products

Manage stock levels

Pagination and sorting

🔹 Order Management

Place orders

Validate stock before order

Calculate total price

Order status tracking

🔹 Microservices Architecture (Phase 2)

User Service

Product Service

Order Service

API Gateway

Service Discovery (Eureka)

🛠️ Tech Stack

Language: Java 17

Framework: Spring Boot, Spring Cloud

Database: PostgreSQL

ORM: Spring Data JPA

Build Tool: Maven

Testing: JUnit, Mockito

API Testing: Postman

Documentation: Swagger / OpenAPI

🎯 Learning Objectives

REST API design best practices

Layered architecture (Controller → Service → Repository)

Database integration with JPA

Microservices fundamentals

Inter-service communication (OpenFeign)

API Gateway and Service Discovery

Exception handling and validation

Interview-ready backend concepts

💡 Why This Project?

This project demonstrates real-world backend engineering patterns used in e-commerce platforms and is designed to showcase REST and microservices skills for Java backend developer interviews.

📂 Project Structure
ordermanagement/
 ├── controller
 ├── service
 ├── repository
 ├── entity
 ├── dto
 ├── exception
 └── config

🧪 How to Run

Clone the repository

Configure PostgreSQL in application.yml

Run the Spring Boot application

Test APIs using Postman

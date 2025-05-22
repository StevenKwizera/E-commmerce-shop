 E-commerce Web Application 


This is a mini project for the **Web Technology & Internet (INSY-413)** course at the Faculty of Information Technology. The application is an e-commerce platform developed using Spring Boot for the backend and Thymeleaf for the frontend. It allows customers to browse products, manage their shopping carts, and place orders, while providing admin functionalities for product and order management.

**GitHub Repository:https://github.com/StevenKwizera/E-commmerce-shop  

 User Stories

- **As a customer**, I want to:
  - Browse products and view their details.
  - Add products to my shopping cart.
  - View my shopping cart and proceed to checkout.
  - Register/login to the application to manage my orders.
- **As an admin**, I want to:
  - Add new products to the store and manage existing products.
  - View orders and update their status.

 Project Overview

This project implements a simple e-commerce web application with the following features:
- User authentication and authorization with roles (USER, ADMIN).
- Product browsing, cart management, and order placement for customers.
- Admin panel for product and order management.
- Responsive frontend with Thymeleaf and Bootstrap styling.
- RESTful APIs for backend-frontend communication.
- Error handling and validation.
- Deployment on a cloud platform (Heroku).

## Technologies Stack

### Backend
- **Spring Boot**: Core framework for building the application.
- **Spring Data JPA**: For database interactions.
- **Spring Security**: For user authentication and authorization.

### Frontend
- **Thymeleaf**: Template engine for dynamic HTML rendering.
- **Spring MVC**: For handling frontend requests.
- **Bootstrap**: For responsive and styled UI components.

### Database
- **MySQL** or **PostgreSQL** (configurable).

### Deployment
- **Heroku**: Cloud platform for hosting the application.

## Setup Instructions

### Prerequisites
- Java JDK 17 or higher.
- Maven or Gradle (for dependency management).
- MySQL or PostgreSQL (for database).
- Git (for version control).
- Heroku CLI (for deployment).

### Steps to Run the Project

1. **Clone the Repository**
   ```bash
   git clone <your-repository-url>
   cd shopping-cart-spring-boot
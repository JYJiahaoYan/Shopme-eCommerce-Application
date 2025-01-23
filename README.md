# ShopMe eCommerce Application

## Overview
ShopMe is a comprehensive eCommerce web application developed using modern technologies like **Java**, **Spring Boot**, **Thymeleaf**, **Bootstrap**, **jQuery**, and **MySQL**. This project demonstrates how to build a fully functional online shopping platform with both admin and customer-facing applications.

## Features

### **Admin Application**
The admin portal is designed for managing the business side of the platform, with the following features:
- User management
- Category and brand management
- Product catalog management
- Customer and order management
- Sales reporting and analytics using Google Charts

### **Shopping Application**
The shopping platform allows customers to browse and purchase products easily:
- Browse products with responsive and mobile-friendly design
- Add items to a shopping cart
- Secure checkout with PayPal and credit card payment integration via the **PayPal Checkout API**
- Customer registration with email confirmation and order notifications

### **Technology Highlights**

#### **Back-End**
- **Spring Boot 3.2.0**: Provides a robust and modern framework for application development
- **Spring Data JPA with Hibernate**: Simplifies database interactions
- **Spring Security 6.2.0**: Ensures authentication and role-based authorization
- **Spring RESTful Webservices**: Enables smooth integration between client-side JavaScript (jQuery) and the server
- **Spring Mail**: Sends automated emails for user registration and order confirmation
- **Spring OAuth**: Supports single sign-on (SSO) with Facebook and Google

#### **Front-End**
- **Thymeleaf Template Engine**: Renders dynamic HTML views
- **Bootstrap and jQuery**: Creates responsive, mobile-friendly interfaces

#### **Testing**
- Comprehensive unit and integration tests using **JUnit**, **Spring Test**, **AssertJ**, and **Mockito**

#### **Deployment**
- Deployable on the **Heroku cloud platform**
- File upload support using **Amazon S3**

#### **Additional Features**
- **Google Charts**: Visualizes sales reports
- **PayPal Checkout API**: Enables seamless payment processing  

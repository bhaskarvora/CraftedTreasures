# CraftedTreasures  Application
# Backend Part Made Using Spring Boot 

## Frontend Part using Angular : https://github.com/bhaskarvora/CraftedTreasures-Frontend-Part-

## Overview

CraftedTreasures is an innovative project designed to showcase and promote handcrafted treasures from artisans around the world. The project aims to create a vibrant online marketplace that connects skilled crafters with enthusiasts who appreciate unique, artisanal products.

This is a comprehensive application built using Spring Boot. It includes features for user authentication, product management, cart management, and order processing. The application utilizes JWT for secure authentication and integrates with Razorpay for handling payments.

## Features

### User Authentication and Authorization
- **JWT Authentication**: Secure login with JSON Web Tokens (JWT).
- **Role-Based Access**: Differentiated access for users and admins.

### User Management
- **User Registration**: Register with username, password, and personal details.
- **Role Assignment**: Users are assigned roles such as "Admin" or "User".

### Product Management
- **Add Product**: Admins can add new handmade products.
- **View Products**: Users can browse handmade products.
- **Search Products**: Search for products by name or description.
- **Product Details**: Detailed view of individual products.
- **Delete Product**: Admins can remove products from the system.

### Cart Management
- **Add to Cart**: Add products to the shopping cart.
- **View Cart**: View cart contents.
- **Checkout**: Finalize purchases from the cart or single product checkout.

### Order Management
- **Single Product Checkout**: Purchase individual products.
- **Cart Checkout**: Purchase all items in the cart.

### Security and Protection
- **Token-Based Authentication**: Stateless authentication using JWT.
- **Password Encryption**: Secure password storage with BCrypt.

### Integration
- **Razorpay**: Payment integration for processing transactions.

## Setup and Installation

### Prerequisites
- Java 8 or higher
- Maven
- MySQL

### Cloning the Repository

git clone https://github.com/bhaskarvora/CraftedTreasures.git


## Configuring Application Properties
Edit the src/main/resources/application.properties file to configure the following:
Server Port
Database Connection
JPA Settings
## Example configuration:


- server.port=9091
- spring.datasource.url=jdbc:mysql://localhost:3306/db
- spring.datasource.username=root
- spring.datasource.password=root@123
- spring.datasource.platform=mysql
- spring.jpa.hibernate.ddl-auto=create (change to update after initial setup)
- spring.jpa.show-sql=true
- spring.jpa.properties.hibernate.format_sql=true



## Building and Running the Application
Build the Project

- mvn clean install
  
Run the Application

- mvn spring-boot:run


## Project Structure
- com.bhaskar: Main package containing application classes.
- util: Contains utility classes like JwtUtil for handling JWT operations.
- service: Contains service classes for managing business logic.
- dao: Contains Data Access Objects for database operations.
- src/main/resources/application.properties: Configuration file for the application.
- pom.xml: Maven build configuration file.

## Dependencies
- Spring Boot: Provides the core framework for the application.
- Spring Security: For handling authentication and authorization.
- Spring Data JPA: For database interactions.
- MySQL: Database for storing application data.
- Razorpay: Payment gateway integration.
- JJWT: Library for handling JSON Web Tokens.

## Contributing
- Fork the repository.
- Create a new branch (git checkout -b feature-branch).
- Make your changes.
- Commit your changes (git commit -am 'Add new feature').
- Push to the branch (git push origin feature-branch).
- Create a new Pull Request.

## Screenshots

![Home Page Crafted](https://github.com/user-attachments/assets/c8cef9fa-c762-4a69-9747-4781c6f81d87)
Home Page User Side

![Screenshot 2024-09-09 192846](https://github.com/user-attachments/assets/1e9100be-121f-41aa-9f80-17ce871c83d2)
Home Page Admin Panel

![Cart Page Crafted](https://github.com/user-attachments/assets/7a6062da-16f2-4378-9757-e9ac737ad62f)
Cart Page 

![Checkout Page Crafted](https://github.com/user-attachments/assets/b557b42b-ee5e-40b5-b6f4-3a63c9087c91)
Checkout Page 

![Search Filter Crafted](https://github.com/user-attachments/assets/b8f6e8d4-7a42-438b-a7c6-5b40ec61b467)
Search Filter 

![Database db for Crafted ](https://github.com/user-attachments/assets/6516f044-4474-4c18-b561-429e4dde6353)
Database db

![Add HandMade Items](https://github.com/user-attachments/assets/1dce92bc-37e4-4218-9ce9-e0b3020b79ae)
Add Handmade Items 

![Show Ptoduct Details Crafted](https://github.com/user-attachments/assets/8fd38dd8-7a1a-4f9c-b117-ec6c65281b90)
Show Product Details 


![Order Information All](https://github.com/user-attachments/assets/43548b3e-75fe-4994-8ace-21db6670a315)
Order Information All

![Order Information Filter Placed](https://github.com/user-attachments/assets/1f8f8b61-21f2-43f6-9f7a-828955687fef)
Order Information Filter Placed 

![Order Information  Delivered Filter](https://github.com/user-attachments/assets/6cf29e1c-e4d2-43fb-b228-264f048c9e47)
Order Information Filter Delivered

![OrderConfirmation Page Crafted](https://github.com/user-attachments/assets/a1a7b1da-9f87-4df6-962f-699ffdc343c5)
Order Confirmation Page 

![Razorpay Payment Integration](https://github.com/user-attachments/assets/179d8775-48b6-400f-ad9a-6b568c2281b0)

Razorpay Payment Integration

![Payment Integration Crafted](https://github.com/user-attachments/assets/90f95d99-ff8a-4a59-8268-8719e055e4dd)

Payment Integration



Feel free to adjust any details or add any additional sections as needed!


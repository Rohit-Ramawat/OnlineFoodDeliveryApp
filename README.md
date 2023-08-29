
# REST API Online Food Delivery Application: FoodJet
* We have developed this REST API for Online Food Delivery Application. This API performs all the fundamental CRUD Operations of any Food Delivery Application platform which user validation at every step.
* This project is developed by a team of 4 Back-end Developers during project week in Masai School.

## Tech Stack
* java
* Spring Framework
* Spring Boot
* Hibernate
* MySQL

## Project Schema:
![Online Food Delivery Application ReadMe](https://github.com/rameshy9891/sharp-head-9647/assets/119414002/e7dc2a80-bfc4-4049-a51a-f36850f33b63)

## Modules
* Login, Logout Module
* Admin Module
* User Module
* Food Cart Module
* Item Module
* OrderDetail Module
* Restaurant Module
* Category Module
* Bill Module

## Features
* User and Admin Authentication & Validation with session uuid.
* Admin Features
  * Administrator of the entire Application.
  * Only registered admin with valid session token can add/update/delete all the modules from main database.
  * Admin can access the details of different users.
* user Features
  * Registering themselves with the application and logging in to get a valid session token
  * Viewing list of Available Restaurant and Category.
  * Only logged in user can access his Order details, order status, profile updation and other features

## contributors 
* @Ramesh Yadav
* @Salman Khan
* @Rohit Ramawat
* @Nitish Mandal

## Installation & Run 
* Before running the API server, you should update the database config inside the application.properties file.
* Update the port number, username and password as per your local database config.

```
spring.datasource.url=jdbc:mysql://localhost:3306/database
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.datasource.username=root
spring.datasource.password=root

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

## Conclusion
FoodJet REST API is a comprehensive and efficient solution for an online food delivery application. Developed by a team of skilled back-end developers, this project encompasses all the fundamental CRUD operations necessary for a food delivery platform, with user validation at every step. Leveraging the tech stack of Java, Spring Framework, Spring Boot, Hibernate, and MySQL, this API ensures seamless functionality and robust database management.
The project follows a modular approach, with distinct modules for login, admin management, user management, food cart, items, order details, restaurants, categories, and billing. This allows for a well-structured and organized codebase that enhances maintainability and scalability.

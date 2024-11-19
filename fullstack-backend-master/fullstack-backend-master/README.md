# FullStackApp

FullStackApp is a web application built with Spring Boot for the backend and React for the frontend. It provides a seamless full-stack development experience for building modern web applications.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)

## Features

- **Spring Boot Backend:**
  - RESTful API endpoints.
  - Database integration with Spring Data JPA.

- **React Frontend:**
  - Responsive and dynamic user interface.
  - State management using React Hooks.
  - Integration with backend APIs.

- **Full Stack:**
  - Seamless integration between the backend and frontend.
  - Modern and efficient development workflow.

## Prerequisites
## Project Description

Before you begin, ensure you have met the following requirements:

- Java Development Kit (JDK) installed.
- Node.js and npm installed.
- IDE with support for Spring Boot and React development.

## Project Description
This backend application is developed using Spring Boot and provides CRUD (Create, Read, Update, Delete) operations for managing user registrations. It uses MySQL as the database and JPA for ORM functionality.

Database Queries
1. Create the Database
sql
Copy code
CREATE DATABASE RegistrationDB;
2. Use the Database
sql
Copy code
USE RegistrationDB;
3. Create the Registration Table
sql
Copy code
CREATE TABLE Registration (
    ID INT AUTO_INCREMENT PRIMARY KEY,
    Name VARCHAR(100) NOT NULL,
    Email VARCHAR(100) UNIQUE NOT NULL,
    DateOfBirth DATE NOT NULL,
    PhoneNumber VARCHAR(15),
    Address VARCHAR(255),
    CreatedAt TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    UpdatedAt TIMESTAMP DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP
);

Author
Name: Kuladeep



Spring Boot Address Book Application

Welcome to the Address Book application built with Spring Boot. 
This project demonstrates the use of REST APIs to perform CRUD operations 
for managing contacts.

Table of Contents:
- Overview
- Technologies Used
- Features
- Project Structure
- API Endpoints

Overview:
The Address Book backend allows you to store, update, retrieve, 
and delete contact information such as:
- Name
- Address
- City
- State
- Zip Code
- Phone Number

This application is designed to demonstrate Spring Boot principles 
including layered architecture, input validation using DTOs, 
and data persistence using an in-memory H2 database.

Technologies Used:
- Java 17+
- Spring Boot
- Spring Web
- Lombok
- H2 Database (In-Memory)
- Maven

Features:
- Add, update, delete, and retrieve contacts
- Input validation using annotations in DTOs
- RESTful API implementation using @RestController
- Layered architecture with Controller, Service, and Repository layers
- In-memory H2 database for easy storage and testing

Project Structure:
- model – Contains the Contact entity class
- dto – Holds Data Transfer Objects with validation
- controller – Defines REST API endpoints
- service – Implements business logic for contact handling
- repository – Manages in-memory storage using H2 database

API Endpoints:
- GET    /contacts          – Retrieve all contacts
- GET    /contacts/{id}     – Retrieve a contact by ID
- POST   /contacts          – Add a new contact
- PUT    /contacts/{id}     – Update an existing contact
- DELETE /contacts/{id}     – Delete a contact by ID

Thank you!


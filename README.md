# Projects
This repository contains your project instructions

## Project 1 - Simple SpringBoot REST API

### Project Description
For this project you will work alone to build a backend-only REST API using Java + Spring Boot with an in-memory H2 database. Your project should have the following:
- User / Account registration
- n:1 Records associated with a user
- Other unique functionality

For Example, a "Simple Social Media API" should include:
- User Registration & Login
- User Account Management
- Content Management for a generic “content” entity (CRUD)
- Basic Social Functionality (e.g., follow/unfollow, friend requests, likes—choose one or two based on time)

Tools Used:
- Java
- Spring Boot
- Spring Web (REST Controllers)
- (Recommended) Spring Data JPA (persistence layer)
- H2 Database (in-memory)
- Maven or Gradle
- Postman (or similar API client)

Architecture
- 3-tier architecture
- Presentation Layer (Controllers)
- Service Layer (Business Logic)
- Data Layer (Repositories / Data Access)

### Week During Training: Week 1

### API Requirements
#### User Entity
- Register a new user account with username and password
- Authenticate a user with username and password
- Retrieve user information by ID
- Retrieve all users with optional filtering
- Update user account information
- Delete a user account

#### Content Entity
- Create new content
- Retrieve content by ID
- Retrieve all content with optional filtering
- Update existing content
- Delete content

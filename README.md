# Animals API

This project is a RESTful API for managing animal records. It allows you to create, read, update, delete, and search animals by different attributes (ID, species, name). The API is built using Spring Boot with JPA for data persistence and MySQL as the database.

## Features
- Get all animals
- Get an animal by ID
- Add a new animal
- Update an existing animal
- Delete an animal
- Search animals by name
- Get animals by species

## Prerequisites
Before running the project, ensure you have the following installed:

1. **Java Development Kit (JDK)**: Version 17 or higher
2. **Maven**: Dependency management tool for Java projects
3. **MySQL**: Used as the database for storing animals' data
4. **Spring Boot**: Integrated within the project
5. **Postman** (optional): For testing API requests

### Database Setup
1. Install MySQL if it's not already installed.
2. Create a new MySQL database called `animaldb` by running the following SQL command:
   ```sql
   CREATE DATABASE animaldb;

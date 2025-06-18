# Quarks Backend Assignment

## Description
This is a simple REST API that manages users with in-memory storage. It allows you to create users and retrieve them by ID.

## Technologies
- Java
- Spring Boot

## How to Run
1. Build the project using Maven or Gradle.
2. Run the Spring Boot application.
3. Open Swagger UI at: [http://localhost:8080/swagger-ui/index.html](http://localhost:8080/swagger-ui/index.html)
4. Use the endpoints:
   - POST `/users` to create a user
   - GET `/users/{id}` to get a user by ID

## Example CURL Requests

### Create User
```bash
curl -X POST "http://localhost:8080/users" -H "Content-Type: application/json" -d '{"name":"alice","email":"alice@gmail.com"}'

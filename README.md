# Task 1 - Spring Boot Application

## Description
First Spring Boot application built with Spring MVC pattern, 
using Thymeleaf for the view layer.

## Technologies Used
- Java
- Spring Boot
- Spring MVC
- Thymeleaf
- Maven

## How to Run
1. Clone the repository
2. Open in IntelliJ IDEA
3. Run `Task1SpringApplication.java`
4. Open browser at `http://localhost:8080`

## Endpoints

### GET /
Returns a simple text message.
- URL: `http://localhost:8080/`
- Method: GET
- Response: `Hello! This is my first Spring controller.`

### GET /greeting
Returns an HTML page with a personalized greeting.
- URL: `http://localhost:8080/greeting?name=YourName`
- Method: GET
- Parameter: `name` (optional, defaults to "World")
- Response: HTML page with greeting message

## Screenshots
### Home endpoint (localhost:8080/)
<img width="596" height="281" alt="image" src="https://github.com/user-attachments/assets/78b680f0-4050-4dc5-b5a6-aeee6c6b75f8" />


### Greeting endpoint (localhost:8080/greeting?name=Djenna)
<img width="672" height="254" alt="image" src="https://github.com/user-attachments/assets/f319944b-33f0-4ba5-9dce-925558dcd295" />

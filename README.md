# Student Management System

**Tech stack:** Core Java • Spring Boot • H2 (in-memory) • Maven

## Project summary
Minimal Student Management System backend to demonstrate CRUD operations for students and courses,
using Spring Boot and an in-memory H2 database for easy local testing.

## Run locally
1. Install JDK 17+ and Maven.
2. Build and run:
```bash
mvn clean package
mvn spring-boot:run
```
3. The API base: `http://localhost:8080/api/`

## Endpoints (examples)
- `GET  /api/students` — list students
- `POST /api/students` — add student (JSON)
- `GET  /api/students/{id}` — get student by id
- `PUT  /api/students/{id}` — update student
- `DELETE /api/students/{id}` — delete student

## Notes
- This project uses H2 in-memory database for simplicity. For production, change datasource in application.properties.
- Replace package `com.example.sms` if desired.

## Author
Enugula Manasa

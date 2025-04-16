# Travels Java API

A backend RESTful API for managing travel bookings and trip information.  
This project is built using **Java**, **Spring Boot**, and **PostgreSQL**, and showcases core backend development skills including CRUD operations, pagination, filtering, validation, and API documentation.

> 🚀 Developed and maintained by **Shriram Ghotekar**

---

## 📌 Features

This API provides endpoints to:

- Create, update, and delete trips
- Fetch trip details by ID or order number
- Filter specific fields from the response
- Get trip reports within a time range (with pagination & sorting)
- View overall travel statistics (total, average, max, min, count)

---

## 🔧 Technologies Used

- Java 11
- Spring Boot 2.3.7
- Spring Admin Client
- Spring Data JPA
- PostgreSQL
- Flyway (for DB migrations)
- Swagger 3.0.0
- ModelMapper
- EhCache
- Bucket4j (Rate Limiting)
- Maven
- JUnit 5

---

## 🔄 API Endpoints Overview

| Method | Endpoint | Description |
|--------|----------|-------------|
| `POST` | `/api-travels/v1/travels` | Create a new trip |
| `PUT` | `/api-travels/v1/travels/{id}` | Update a trip |
| `DELETE` | `/api-travels/v1/travels/{id}` | Delete a trip |
| `GET` | `/api-travels/v1/travels/{id}` | Get trip by ID |
| `GET` | `/api-travels/v1/travels/byOrderNumber/{orderNumber}` | Get trip by order number |
| `GET` | `/api-travels/v1/travels?startDate=...` | Filter trips by date, paginate & sort |
| `GET` | `/api-travels/v1/statistics` | View travel statistics |

---

## 🧪 How to Run

### 📁 PostgreSQL Setup

Create a database named `travels`:

```sql
CREATE DATABASE travels;
spring.datasource.username=
spring.datasource.password=

🧑‍💻 Author
Shriram Ghotekar
Java Backend Developer
GitHub Profile


---



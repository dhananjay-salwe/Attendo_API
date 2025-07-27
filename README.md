# 📘 Attendo

**Attendo** is a Spring Boot REST API project designed to streamline and automate the management of student attendance in educational institutions. It allows faculty members to record attendance for specific subjects and provides endpoints for viewing and managing these records. The application focuses on reducing paperwork, improving accuracy, and enhancing administrative workflows.

---

## 🎯 Objective

* ✅ Automate attendance tracking through RESTful APIs to streamline integration with existing educational systems.
* ✅ Ensure data accuracy with automated validation and structured storage of attendance records.
* ✅ Facilitate seamless integration with institutional platforms to support faculty and administrative operations.

---

## 🔍 Scope of the Project

Attendo provides a robust backend system to manage:

* Student records
* Subject allocation
* Faculty details
* Attendance tracking and reporting

The system is designed with a modular, scalable architecture using a layered design pattern.

---

## 🏗️ Project Architecture

Attendo follows a **Layered Architecture**, separating concerns across three core layers:

### 1. **Controller Layer**

* Handles incoming HTTP requests
* Validates inputs and delegates processing to the service layer
* Formats and returns HTTP responses

### 2. **Service Layer**

* Implements business logic and application rules
* Coordinates interactions between controllers and DAOs
* Manages data validation, transformation, and transactions

### 3. **DAO (Data Access Object) Layer**

* Handles all direct interactions with the database
* Performs CRUD operations
* Translates method calls to SQL queries using Hibernate
* Abstracts database logic from other layers

---

## ⚙️ Technology Stack

| Component            | Technology        |
| -------------------- | ----------------- |
| Backend Framework    | Spring Boot 2.5.6 |
| Database             | MySQL 8           |
| ORM                  | Hibernate 5.6     |
| Programming Language | Java (JDK 1.8)    |
| Build Tool           | Maven             |
| IDE                  | Eclipse           |
| API Testing          | Postman           |

---

## 📦 Modules in the Project

1. **Student Module** – Manage student data
2. **Subject Module** – Define and assign subjects
3. **Faculty Module** – Manage faculty details and their assigned subjects
4. **Attendance Module** – Record and retrieve attendance per subject
5. **User Module** – Manage API access and authentication (if implemented)

---

## 🚀 Getting Started

To run the project locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/attendo.git
   cd attendo
   ```

2. Configure your `application.properties` with your local MySQL credentials.

3. Use **Postman** or any REST client to test the endpoints once the app is running.

---

## 📝 License

This project is open-source and free to use for educational purposes.

---


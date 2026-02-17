# 🎓 Student Management System

A CRUD-based web application developed using **Java, Spring Boot, Spring MVC, and MySQL** to manage student records efficiently.
This project demonstrates the implementation of **MVC architecture**, database integration using **Spring Data JPA (Hibernate)**, and core full-stack development concepts.

---

## 🚀 Features

* ➕ Add new student details
* 📋 View all student records
* ✏️ Update existing student information
* ❌ Delete student records
* 🗄️ MySQL database integration
* 🏗️ MVC layered architecture
* ✅ Form handling and validation using Spring MVC

---

## 🛠️ Tech Stack

| Technology                  | Usage                 |
| --------------------------- | --------------------- |
| Java                        | Backend Development   |
| Spring Boot                 | Application Framework |
| Spring MVC                  | Web Layer             |
| Spring Data JPA (Hibernate) | Database Operations   |
| MySQL                       | Database              |
| HTML/CSS                    | Frontend              |
| Maven                       | Build Tool            |

---

## 📂 Project Structure

```
student-management-system-springboot
│
├── controller        → Handles user requests
├── service           → Business logic layer
├── repository        → Database interaction (JPA)
├── model/entity      → Student entity class
├── resources
│   ├── templates     → HTML pages
│   └── application.properties
└── main class        → Spring Boot starter
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/student-management-system-springboot.git
```

### 2️⃣ Open in IDE

Open the project using **Eclipse / IntelliJ IDEA / Spring Tool Suite**.

### 3️⃣ Configure Database

Create a MySQL database:

```sql
CREATE DATABASE student_db;
```

Update `application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/student_db
spring.datasource.username=your_username
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

### 4️⃣ Run the Application

Run the main class:

```
StudentManagementSystemApplication.java
```

### 5️⃣ Open in Browser

```
http://localhost:8080/
```

---

## 📸 Functional Modules

* Student Registration Form
* Student List Dashboard
* Edit Student Details
* Delete Student Record

---

## 🎯 Learning Outcomes

* Understanding of **Spring Boot project structure**
* Implementation of **MVC architecture**
* Working with **JPA & Hibernate ORM**
* Database connectivity with MySQL
* Building real-world CRUD applications

---

## 👩‍💻 Developed By

**Archana Aruljothi**
Java Full Stack Developer
(Trained at QSpiders)

---

## 📌 Future Enhancements

* Search & filter students
* Pagination
* Login authentication (Spring Security)
* REST API integration (planned)

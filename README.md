# 📝 eSoft OOP Task Manager

## 📌 Overview
This project was developed as part of the **Object-Oriented Programming (OOP) course** at university.  
It is a **Task Manager** built using Java and Spring Boot, designed to apply OOP principles in a real-world scenario.  
The system allows users to create, manage, and organize tasks efficiently while demonstrating key OOP concepts.

---

## 🚀 Features
- 📝 **Create, Read, Update, Delete (CRUD)** tasks  
- 🎯 **Task Prioritization** based on user-defined parameters  
- 📅 **Due Date Management** for better scheduling  
- 🔎 **Filtering and Sorting** by status, priority, and deadline  
- 📊 **User-friendly API** with REST endpoints  
- 🗄️ **Database Integration** using PostgreSQL  

---

## 📦 Tech Stack
| Category         | Technology        |
|-----------------|------------------|
| **Backend**      | Java, Spring Boot |
| **Database**     | PostgreSQL       |
| **API**         | RESTful API       |
| **Build Tool**   | Maven            |
| **Version Control** | Git & GitHub |

---

## 🔧 Installation & Setup

### 1️⃣ Clone the repository

### 2️⃣ Configure the Database
Make sure you have **PostgreSQL installed** and create a database:
```sql
CREATE DATABASE task_manager;
```
Edit the `application.properties` file inside `src/main/resources/` to set up your database connection:
```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/task_manager
spring.datasource.username=your_username
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
```

### 3️⃣ Build & Run the Project
```sh
mvn clean install
mvn spring-boot:run
```

---

## 📡 API Endpoints
### 📌 Task Management
| Method | Endpoint | Description |
|--------|----------|-------------|
| `GET`  | `/tasks` | Get all tasks |
| `POST` | `/tasks` | Create a new task |
| `PUT`  | `/tasks/{id}` | Update a task |
| `DELETE` | `/tasks/{id}` | Delete a task |

---

## 📌 To Do
✅ Improve API Documentation  
✅ Add Unit Tests using JUnit  
✅ Implement Authentication (JWT)  

---

## 🤝 Contributing
Feel free to open issues and submit pull requests to improve the project!

## 📜 License
This project is licensed under the MIT License.

# 📝 eSoft OOP Task Manager

## 📌 Overview
This project was developed as part of the **Object-Oriented Programming (OOP) course** at university.  
It is a **Task Manager** built using **Java** and **Spring Boot**, designed to apply OOP principles in a real-world scenario.  
The system allows users to create, manage, and organize tasks efficiently while demonstrating key OOP concepts.

---

## 🚀 Features
- 📝 **Create, Read, Update, Delete (CRUD)** operations for tasks  
- 🎯 **Task Prioritization** based on user-defined parameters  
- 📅 **Due Date Management** for better scheduling  
- 🔎 **Filtering and Sorting** by status, priority, and deadline  
- 🔐 **User Authentication** and **Authorization** using JWT  
- 🌐 **RESTful API** for seamless integration  
- 🗄️ **Database Integration** using PostgreSQL  

---

## 📦 Tech Stack
- **Backend:** Java, Spring Boot
- **Database:** PostgreSQL
- **API:** RESTful API
- **Authentication:** JWT (JSON Web Token)
- **Build Tool:** Maven
- **Version Control:** Git & GitHub

---

## 🔧 Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/LucasCatuyama/esoft-oop-task-manager.git
```

### 2️⃣ Configure the Database
Ensure you have **PostgreSQL** installed and create a database named `task_manager`.

Edit the `application.properties` file located in `src/main/resources/` to set up your database connection:
```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/task_manager
spring.datasource.username=your_username
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
```

### 3️⃣ Build & Run the Project
Navigate to the project's root directory and execute:
```bash
mvn clean install
mvn spring-boot:run
```

---

## 📡 API Endpoints

### 🧾 Authentication
- `POST /auth/register` : Register a new user  
- `POST /auth/login` : Login and receive JWT token  

### 📋 Task Management (Requires JWT)
- `GET /tasks` : Retrieve all tasks  
- `POST /tasks` : Create a new task  
- `PUT /tasks/{id}` : Update an existing task  
- `DELETE /tasks/{id}` : Delete a task  

---

Se quiser, posso gerar o `.md` para você baixar diretamente. Deseja isso?


# ✅ Spring Boot To-Do Application

A simple and efficient **To-Do List application** built with **Spring Boot**. It allows users to manage their daily tasks with features like adding, updating, retrieving, and deleting to-do items via a RESTful API.

---

## 🚀 Features

- ➕ Add new to-do tasks
- 📋 View all tasks
- ✅ Mark tasks as completed
- 📝 Update task details
- ❌ Delete tasks
- 🧩 RESTful API design
- 🗃️ Integration with a relational database (H2/MySQL)

---

## 🛠 Tech Stack

| Layer     | Technology                       |
|----------:|----------------------------------|
| Backend   | Spring Boot, Spring Web, Spring Data JPA |
| Database  | H2 (in-memory) or MySQL (optional) |
| Build     | Maven                            |
| Language  | Java                             |

---

## 📂 Project Structure

\`\`\`
spring-boot-todo-application/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/example/todo/
│   │   │       ├── controller/
│   │   │       ├── model/
│   │   │       ├── repository/
│   │   │       └── service/
│   │   └── resources/
│   │       ├── application.properties
├── pom.xml
\`\`\`

---

## ⚙️ Configuration

Example \`application.properties\`:

\`\`\`properties
spring.datasource.url=jdbc:h2:mem:testdb
spring.datasource.driverClassName=org.h2.Driver
spring.datasource.username=sa
spring.datasource.password=

spring.jpa.database-platform=org.hibernate.dialect.H2Dialect
spring.jpa.hibernate.ddl-auto=update

server.port=8080
\`\`\`

---

## ▶️ How to Run

\`\`\`bash
mvn clean install
mvn spring-boot:run
\`\`\`

API will be available at:  
🔗 \`http://localhost:8080\`

---

## 📡 Sample API Endpoints

| Method | Endpoint         | Description              |
|--------|------------------|--------------------------|
| GET    | /api/todos       | Get all to-do items      |
| POST   | /api/todos       | Create a new to-do       |
| PUT    | /api/todos/{id}  | Update a to-do           |
| DELETE | /api/todos/{id}  | Delete a to-do           |

---

## 🙋‍♂️ Author

Bharani Kumar  
[GitHub Profile](https://github.com/J0shethan)

---

## 📄 License

This project is open-source and free to use.

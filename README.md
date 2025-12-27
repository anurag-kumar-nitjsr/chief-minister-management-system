🏛️ Chief Minister Management System

A Spring Boot–based web application to manage Chief Minister records with full CRUD functionality. The system stores details such as name, state, political party, tenure period, and current status in a structured and user-friendly way.

🚀 Features

➕ Add Chief Minister details

📋 View all Chief Ministers

✏️ Edit existing records

❌ Delete records

⏳ Support for “Present” as tenure end date

🧭 Clean and responsive UI using Bootstrap

🛠️ Tech Stack
Layer	Technology
Backend	Spring Boot
Frontend	Thymeleaf, HTML, CSS, Bootstrap
Database	MySQL
ORM	Spring Data JPA
Build Tool	Maven
📂 Project Structure
src
 └── main
     ├── java
     │   └── com.example.cm
     │       ├── controller
     │       ├── service
     │       ├── repository
     │       └── model
     └── resources
         ├── templates
         └── application.properties

⚙️ Setup & Run

Clone the repository

git clone https://github.com/your-username/chief-minister-management-system.git


Configure MySQL in application.properties

spring.datasource.url=jdbc:mysql://localhost:3306/cm_db
spring.datasource.username=root
spring.datasource.password=root


Run the application

mvn spring-boot:run


Open in browser

http://localhost:8080

📌 Use Case

Spring Boot CRUD practice

MVC architecture demonstration

Resume and interview showcase

👨‍💻 Author

Anurag Kumar
Senior Executive | Java & Spring Boot Developer

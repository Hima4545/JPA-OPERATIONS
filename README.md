# 🛒 E-Commerce Web Application

A full-stack e-commerce web application built using **Spring Boot** (backend) and **Angular** (frontend), with **MySQL** as the database. This was my certification capstone project from the Full Stack Java Program at Coding Hub Innovations Pvt. Ltd.

---

## 🚀 Features

- 🔐 User Authentication (Login / Register)
- 📦 Product listing with CRUD operations
- 🛒 Add to cart and order management
- 🔗 RESTful API integration between frontend and backend
- 🗄️ MySQL database with JPA/Hibernate ORM
- 📱 Responsive Angular UI

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Backend | Java, Spring Boot, Spring Data JPA |
| Frontend | Angular 16, TypeScript, HTML5, CSS3 |
| Database | MySQL |
| API | REST APIs |
| Tools | Maven, Git, VS Code, STS |

---

## 📁 Project Structure

```
├── src/
│   ├── main/
│   │   ├── java/          # Spring Boot backend (controllers, services, repos)
│   │   └── resources/     # application.properties, DB config
├── angular/               # Angular frontend source
│   ├── src/app/
│   │   ├── components/    # Product, Cart, Auth components
│   │   └── services/      # API service calls
└── pom.xml                # Maven dependencies
```

---

## ⚙️ How to Run

### Prerequisites
- Java 17+
- Node.js & npm
- MySQL
- Maven

### Backend (Spring Boot)
```bash
# Clone the repository
git clone https://github.com/Hima4545/JPA-OPERATIONS.git

# Navigate to project
cd JPA-OPERATIONS

# Configure MySQL in src/main/resources/application.properties
# spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce_db
# spring.datasource.username=your_username
# spring.datasource.password=your_password

# Run the application
mvn spring-boot:run
```

### Frontend (Angular)
```bash
# Install dependencies
npm install

# Start Angular dev server
ng serve

# Open browser at
http://localhost:4200
```

---

## 📚 Key Concepts Demonstrated

- REST API design with Spring Boot controllers
- JPA Repositories for database operations
- Dependency Injection and IoC with Spring
- Angular components, services, and routing
- HTTP client integration between Angular and Spring Boot
- MySQL CRUD with relationships

---

## 👩‍💻 Author

**Himavarsha Reddy Pulla**
- LinkedIn: [himavarsha-reddy-pulla-034404229](https://linkedin.com/in/himavarsha-reddy-pulla-034404229)
- Email: himavarshareddy474@gmail.com

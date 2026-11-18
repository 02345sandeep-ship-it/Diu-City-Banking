# 🏦 DIU CITY BANK

### Smart Banking Management System

\<p align="center">   A Full-Stack Banking Management System built with Spring Boot and modern web technologies. \</p>

\<p align="center">   \<img src="[https://img.shields.io/badge/Java-21-orange?style=for-the-badge&logo=openjdk](https://img.shields.io/badge/Java-21-orange?style=for-the-badge\&logo=openjdk)" />   \<img src="[https://img.shields.io/badge/Spring%20Boot-4.1.1-brightgreen?style=for-the-badge&logo=springboot](https://img.shields.io/badge/Spring%20Boot-4.1.1-brightgreen?style=for-the-badge\&logo=springboot)" />   \<img src="[https://img.shields.io/badge/Maven-Build-red?style=for-the-badge&logo=apachemaven](https://img.shields.io/badge/Maven-Build-red?style=for-the-badge\&logo=apachemaven)" />   \<img src="[https://img.shields.io/badge/Database-MySQL-blue?style=for-the-badge&logo=mysql](https://img.shields.io/badge/Database-MySQL-blue?style=for-the-badge\&logo=mysql)" /> \</p>

---

## 📌 About The Project

**DIU City Bank** is a Banking Management System developed to simplify and digitize banking operations. The project provides a centralized platform for managing banking activities through a web-based application.

The backend is developed using **Java and Spring Boot**, providing REST APIs, authentication, security, and database connectivity. The frontend communicates with the backend through APIs.

This project is developed as an academic project for MCA.

## ✨ Key Features

- 🔐 **Authentication & Security** – Secure login and authentication.
- 👤 **User Management** – Manage customer information and accounts.
- 🏦 **Bank Account Management** – Handle banking account operations.
- 💸 **Money Transactions** – Manage financial transactions.
- 📊 **Dashboard** – Access banking information through a dashboard.
- 🛡️ **Role-Based Access** – Separate access for admin and users.
- 📄 **PDF Generation** – Generate downloadable PDF documents.
- 📧 **Email Integration** – Email-related functionality.

*Note: Features depend on the modules implemented and configured in the project.*

## 🛠️ Technology Stack

| Technology            | Purpose                        |
| --------------------- | ------------------------------ |
| Java 21               | Backend programming            |
| Spring Boot           | Backend framework              |
| Spring Data JPA       | Database operations            |
| Spring Security       | Application security           |
| MySQL                 | Relational database            |
| Maven                 | Dependency management          |
| JWT                   | Token-based authentication     |
| REST API              | Frontend-backend communication |
| HTML, CSS, JavaScript | Frontend technologies          |

## 📂 Project Structure

```text
Diu-City-Bank/
│
├── src/
│   └── main/
│       ├── java/
│       │   └── com/dcb/
│       │       ├── controller/
│       │       ├── service/
│       │       ├── repository/
│       │       ├── entity/
│       │       ├── config/
│       │       └── ...
│       │
│       └── resources/
│           └── application.properties
│
├── frontend/
│
├── db/
│
├── pom.xml
├── mvnw
├── mvnw.cmd
├── .gitignore
└── README.md
```

## ⚙️ Installation & Setup

### 1. Clone Repository

```bash
git clone https://github.com/YOUR-USERNAME/Diu-City-Bank.git
```

### 2. Open Project

```bash
cd Diu-City-Bank
```

### 3. Backend Configuration

Open:

```text
src/main/resources/application.properties
```

Configure your MySQL database connection and other required settings.

Example:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/diu_city_bank
spring.datasource.username=root
spring.datasource.password=YOUR_PASSWORD

spring.jpa.hibernate.ddl-auto=update
```

Make sure MySQL is installed and running, and the database exists.

### 4. Run Spring Boot Backend

For Windows:

```bash
mvnw.cmd spring-boot:run
```

For Linux/macOS:

```bash
./mvnw spring-boot:run
```

### 5. Run Frontend

Open a new terminal:

```bash
cd frontend
npm install
```

Run the frontend using the script configured in `frontend/package.json`.

## 🔗 Backend Architecture

The backend follows a layered architecture:

```text
Frontend Application
        |
        | HTTP Requests / REST APIs
        |
        v
   Controller Layer
        |
        v
    Service Layer
        |
        v
  Repository Layer
        |
        v
    MySQL Database
```

- **Controller:** Handles incoming API requests.
- **Service:** Contains business logic.
- **Repository:** Communicates with the database.
- **Entity:** Represents database tables.
- **Security:** Handles authentication and authorization.

## 📸 Screenshots

Add your project screenshots here.

| Login Page           | Admin Dashboard          |
| -------------------- | ------------------------ |
| Add login screenshot | Add dashboard screenshot |

| User Dashboard      | Transactions               |
| ------------------- | -------------------------- |
| Add user screenshot | Add transaction screenshot |

## 🔮 Future Enhancements

- Online fund transfers.
- Improved transaction tracking.
- Advanced analytics and reports.
- Enhanced security features.
- Mobile-friendly user experience.

## 👨‍💻 Development Team

**Project Name:** DIU City Bank
**Project Type:** MCA Academic Project
**Backend:** Spring Boot
**Database:** MySQL

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a Pull Request.

## 📜 License

This project is developed for academic and educational purposes.

---

\<p align="center">
&#x20; \<b>DIU CITY BANK\</b>\<br/>
&#x20; Smart Banking. Simple Management. Secure Transactions. 🏦
\</p>

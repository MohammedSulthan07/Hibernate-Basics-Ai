# Hibernate-Basics-Ai

A collection of Java Hibernate projects developed for learning and practicing **Hibernate ORM (Object Relational Mapping)** with MySQL. This repository demonstrates how to map Java objects to relational database tables using Hibernate and follows best practices for building console-based database applications.

---

## 📂 Repository Structure

```
Hibernate-Basics-Ai/
│
├── Demo02/
├── Hibernate/
├── Student-Task-Hibernate/
├──Maven-Demo2/
├── untitled/
│
├── Student-Task-Hibernate-Output.png
└── Student-Task-Hibernate-Output.txt
```

---

## 📚 Projects Included

### 1. Demo02

A beginner-friendly Hibernate project created to understand the basic workflow of Hibernate.

**Features:**

- Hibernate Configuration
- Entity Mapping
- Session Management
- CRUD Operations
- MySQL Integration

---

### 2. Hibernate

Core Hibernate practice project covering various ORM concepts.

**Features:**

- Entity Creation
- Annotations-Based Mapping
- SessionFactory
- Session Management
- Transactions
- CRUD Operations
- One-to-One Mapping
- One-to-Many Mapping
- Many-to-One Mapping
- Many-to-Many Mapping
- Enum Mapping
- Date Handling
- Lazy and Eager Fetching

---

### 3. Student-Task-Hibernate

A console-based Student Management System implemented using Hibernate ORM.

**Features:**

- Add Student
- Fetch Student Details
- Update Student Information
- Delete Student
- Manage Course Details
- Entity Relationships
- Transaction Management
- Hibernate Session Handling

Sample output screenshot and console output are included in the repository.

---

### 4. untitled

Additional Hibernate practice project used for experimenting with different Hibernate concepts and implementations.

---

# 🛠 Technologies Used

- Java
- Hibernate ORM
- JPA (Jakarta Persistence API)
- MySQL
- Maven
- Eclipse IDE / IntelliJ IDEA
- Git
- GitHub

---

# 📋 Requirements

Before running the projects, ensure the following are installed:

- JDK 17 or above
- MySQL Server
- MySQL Workbench (Optional)
- Maven
- Eclipse IDE or IntelliJ IDEA

---

# ⚙ Database Configuration

Update the database configuration inside **hibernate.cfg.xml** or **hibernate.properties**.

Example:

```xml
<property name="hibernate.connection.url">
    jdbc:mysql://localhost:3306/your_database
</property>

<property name="hibernate.connection.username">
    root
</property>

<property name="hibernate.connection.password">
    your_password
</property>
```

Ensure that:

- MySQL Server is running.
- The required database has been created.
- Necessary tables are available (or allow Hibernate to generate them automatically).

---

# ▶ Running the Project

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/Hibernate-Basics-Ai.git
```

### 2. Open the project

Import the project into Eclipse or IntelliJ IDEA.

### 3. Configure Hibernate

Update the database credentials in:

- `hibernate.cfg.xml`
- or `hibernate.properties`

### 4. Build the project

If using Maven:

```bash
mvn clean install
```

### 5. Run the Main Class

Execute the application's main class to start the console application.

---

# 📖 Hibernate Concepts Covered

This repository includes examples demonstrating:

- Hibernate Architecture
- ORM Fundamentals
- SessionFactory
- Session
- Transactions
- Entity Lifecycle
- Entity Mapping
- Primary Keys
- Auto-generated IDs
- CRUD Operations
- Annotation-Based Configuration
- Hibernate Configuration File
- Enum Mapping
- Date and Time Mapping
- Relationships
  - One-to-One
  - One-to-Many
  - Many-to-One
  - Many-to-Many
- Lazy Loading
- Eager Fetching
- Cascade Types
- Exception Handling
- Maven Project Structure

---

# 📸 Sample Outputs

Repository includes:

- Student Task Console Output
- Student Task Output Screenshot

These outputs demonstrate the execution and functionality of the Hibernate applications.

---

# 🎯 Learning Objectives

This repository is intended for students learning:

- Hibernate ORM
- Java Persistence
- Database Programming
- Object Relational Mapping (ORM)
- MySQL Integration
- Console-Based Applications
- Maven Project Development

---

# 🚀 Future Improvements

- Hibernate Criteria API
- HQL (Hibernate Query Language)
- JPQL
- Named Queries
- Pagination
- Second-Level Cache
- Spring Data JPA
- Spring Boot Integration
- REST APIs
- Validation using Hibernate Validator
- Logging with Log4j/SLF4J

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes.
4. Push the branch.
5. Create a Pull Request.

---

# 👨‍💻 Author

**Mohammed Sulthan**

GitHub: https://github.com/MohammedSulthan07

---

# ⭐ Support

If you found this repository useful, please consider giving it a **Star ⭐** on GitHub.

Happy Coding! 🚀

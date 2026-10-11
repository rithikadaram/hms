# Hospital Management System

A desktop-based Hospital Management System developed using **Java, MySQL, and JDBC** to manage patient records, appointments, and billing information.

## Features

- Patient record management
- Add, update, search, and delete patient records
- Appointment management
- Billing management
- MySQL database integration
- CRUD operations
- JDBC-based database connectivity
- Exception handling for database operations

## Technologies Used

- **Java** — Application development
- **MySQL** — Database
- **JDBC** — Database connectivity
- **SQL** — Data management

## System Architecture

```text
User
  ↓
Java Desktop Application
  ↓
JDBC
  ↓
MySQL Database
```

## Database

The application uses MySQL to store:

- Patient details
- Appointment details
- Billing information

The SQL database script is available in the `database` folder.

## How to Run

### 1. Clone the repository

```bash
git clone YOUR_REPOSITORY_URL
```

### 2. Create the database

Open MySQL and execute:

```text
database/hospital_management.sql
```

### 3. Configure the database connection

Update the database URL, username, and password in the database connection class.

```java
String url = "jdbc:mysql://localhost:3306/hospital_management";
String username = "YOUR_USERNAME";
String password = "YOUR_PASSWORD";
```

### 4. Add MySQL JDBC Driver

Make sure the MySQL Connector/J driver is included in the project dependencies.

### 5. Run the application

Run the main Java class to start the Hospital Management System.

## Learning Outcomes

Through this project, I gained practical experience in:

- Java programming
- Object-Oriented Programming
- SQL and relational databases
- JDBC
- CRUD operations
- Exception handling
- Database-driven application development

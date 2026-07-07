# College Management System

A small Java Swing desktop application for managing student records. The project uses Maven for build management and MySQL for storing student data.

## Features

- Login screen for admin access
- Admin dashboard
- Add student records
- Search student records
- Update student details
- Delete student records

## Technologies Used

- Java
- Swing
- Maven
- MySQL
- MySQL Connector/J

## Requirements

- JDK 26 or compatible version
- Maven
- MySQL Server
- NetBeans, IntelliJ IDEA, Eclipse, or any Java IDE

## Database Setup

Create a MySQL database named `college` before running the application.

The project currently connects to MySQL using:

```text
Host: 127.0.0.1
Port: 3306
Database: college
Username: root
Password: Aman@123
```

Update the database username or password in the Java source files if your local MySQL setup is different.

## How to Run

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git
cd YOUR_REPOSITORY_NAME
```

Build the project:

```bash
mvn clean install
```

Run the application from your IDE by opening the project and running:

```text
com.mycompany.college.Login
```

## Admin Login

Default login credentials:

```text
Username: Aman
Password: Aman@123
```

## Project Structure

```text
src/main/java/com/mycompany/college/
```

This folder contains the Swing forms and Java classes for login, admin dashboard, and student record operations.

## License

This project is licensed under the terms included in the `LICENSE` file.

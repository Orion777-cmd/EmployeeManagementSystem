# Employee Management System (Java Servlet Project)

This is a simple Employee Management System web application developed using Java Servlets, HTML, Bootstrap, and MySQL with JDBC connection. The application supports CRUD operations (Create, Read, Update, Delete) for managing employee records.

## Features

- **Add Employee:**
  - Allows users to add a new employee to the system.

- **View Employees:**
  - Displays a list of all employees in the system.

- **Edit Employee:**
  - Enables users to edit existing employee details.

- **Delete Employee:**
  - Allows users to delete an employee from the system.

## Technologies Used

- Java Servlets
- HTML
- Bootstrap (for styling)
- MySQL Database with JDBC Connection

## Setup and Deployment

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/employee-management-system.git

## Database Schema
CREATE TABLE employee (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100),
    designation VARCHAR(50),
    salary FLOAT
);


# Employee Management System (Python + MySQL)

A console-based Employee Management System developed using Python and MySQL.  
This application allows users to perform CRUD operations (Create, Read, Update, Delete) on employee records stored in a MySQL database.

------------------------------------------------------------

## 🚀 Features

- Add new employee records
- View all employees
- Update employee details
- Delete employee records
- MySQL database connectivity using mysql-connector
- Config-based database setup using JSON file

------------------------------------------------------------

## 🛠 Tech Stack

- Python 3
- MySQL
- mysql-connector-python
- JSON

------------------------------------------------------------

## 📂 Project Structure
```
employee-management-SQL/
│
├── main.py              # Main application logic
├── sqlClient.py         # Database connection and query handling
├── config.json          # Database configuration file
├── requirements.txt     # Required dependencies
├── screenshots/         # Project screenshots (optional)
└── README.md
```
------------------------------------------------------------

## ⚙ Installation & Setup

1. Clone the repository:
   git clone https://github.com/Riteshmelkani/employee-management-SQL.git

2. Navigate into the project folder:
   cd employee-management-SQL

3. Install required dependencies:
   pip install -r requirements.txt

4. Create MySQL database:
   CREATE DATABASE employees_db;

5. Update config.json file with your MySQL credentials:
   {
     "host": "localhost",
     "user": "your_username",
     "pass": "your_password",
     "database": "employees_db"
   }

6. Run the application:
   python main.py

------------------------------------------------------------

## 🗄 Example Database Table

CREATE TABLE employeedetails (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100),
    department VARCHAR(100),
    salary FLOAT,
    joiningDate DATE
);

------------------------------------------------------------

## 📌 Learning Outcomes

- Database connectivity in Python
- MySQL authentication handling
- Implementing CRUD operations
- Error handling in SQL queries
- Git & GitHub version control workflow

------------------------------------------------------------

## 👨‍💻 Author

Ritesh Melkani  
GitHub: https://github.com/Riteshmelkani

------------------------------------------------------------

If you found this project useful, feel free to star the repository.
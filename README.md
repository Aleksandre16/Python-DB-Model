                                                                                            Employee Management System

Overview:
This repository contains an Employee Management System implemented in Python using SQLite as the database backend. The system allows you to manage employees' information, including their name, surname, and age. It provides functionalities such as creating, retrieving, updating, and deleting employee records.

Installation:
1. Clone the repository to your local machine:
   git clone https://github.com/Aleksandre16/Python-DB-Model

2. Navigate to the project directory:
   cd Python-DB-Model

3. Install the required dependencies (assuming Python and pip are already installed):
   pip install -r requirements.txt

4. Run the main program:
   python main.py

Usage:
Employee Class:
- The Employee class represents an employee and provides methods for managing employee records.
  
  Attributes:
  - name: The employee's first name.
  - surname: The employee's last name.
  - age: The employee's age.
  - id (optional): The unique identifier of the employee record in the database.

  Class Methods:
  - get(pk): Retrieves an employee record by its primary key (ID).
  - get_list(**kwargs): Retrieves a list of employee records based on the specified filter criteria.
  - delete(): Deletes the employee record from the database.
  - save(): Saves changes to the employee record in the database.

  Comparison Operators:
  - The Employee class overloads several comparison operators (<, <=, ==, !=, >, >=) based on the age attribute, allowing you to compare employee objects based on their ages.
 
  - This File Is Home Work For Academy!
    
By Aleksandre Kolbini

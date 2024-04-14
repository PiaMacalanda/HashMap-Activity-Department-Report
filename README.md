# HashMap-Activity-Department-Report

This repository contains the source code for an Department Report implemented in Java. It includes classes for managing departments, employees, and generating the overall department salary.

## Description

The Department Report System consists of the following components:

- `Department`: Represents a department within the organization. It manages employees assigned to the department and provides functionality to print department details.

- `Employee`: Represents an employee with attributes such as employee number, last name, first name, job title, and salary.

- `DepartmentDA`: Manages the loading and processing of department data from a CSV file (`deptemp.csv`). It loads department data along with employee details, assigns salaries to employees, and generates department reports.

- `EmployeeDA`: Manages the loading of employee data from a CSV file (`emp.csv`). It loads employee data and provides methods to retrieve employee objects by their employee number.

- `DepartmentReport`: Contains the main method to initiate the processing of department data and generate department reports.

## Usage

To use the Employee Management System, follow these steps:

1. Ensure you have Java installed on your system.
2. Clone this repository to your local machine.
3. Make sure the required CSV files (`deptemp.csv` and `emp.csv`) are available in the project directory with the appropriate data.
4. Compile the Java files using `javac`.
5. Run the `DepartmentReport` class to generate department reports.

## Credits

This project is part of Sir Jerry Esperanza's lab assignment 5, focusing on the implementation of HashMap data structures for managing departments and employees in an object-oriented programming paradigm.

## Programmer's Name

- [Pia V. Macalanda]

# 12 SQL: Employee Tracker

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


## Table of Contents
* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)
* [Deployment](#deployment)
* [References](#references)
* [License](#license)

## Description

This command-line application is to manage a company 's employee database using Node.js, Inquirer, and MySQL.  This would enable the user to organise the business cashflows and budget.

###### User Story
```md
AS A business owner
I WANT to be able to view and manage the departments, roles, and employees in my company
SO THAT I can organize and plan my business
```
###### Acceptance Criteria

```md
GIVEN a command-line application that accepts user input
WHEN I start the application
THEN I am presented with the following options: view all departments, view all roles, view all employees, add a department, add a role, add an employee, and update an employee role
WHEN I choose to view all departments
THEN I am presented with a formatted table showing department names and department ids
WHEN I choose to view all roles
THEN I am presented with the job title, role id, the department that role belongs to, and the salary for that role
WHEN I choose to view all employees
THEN I am presented with a formatted table showing employee data, including employee ids, first names, last names, job titles, departments, salaries, and managers that the employees report to
WHEN I choose to add a department
THEN I am prompted to enter the name of the department and that department is added to the database
WHEN I choose to add a role
THEN I am prompted to enter the name, salary, and department for the role and that role is added to the database
WHEN I choose to add an employee
THEN I am prompted to enter the employee’s first name, last name, role, and manager, and that employee is added to the database
WHEN I choose to update an employee role
THEN I am prompted to select an employee to update and their new role and this information is updated in the database 
```
## Installation

  * Node.js is installed from the website, https://www.nodejs.org. 

 * Node Package Manager (npm) is a software manager and installer which puts the modulesin 
   place so that the node project can utilize it, and also, it manages dependency conflicts intelligently.

 * The application is initialized using <strong>npm init</strong>.
   During the installation process, the user will be asked to input some information about the project.  The package.json will be generated in our folder after initialization of npm.  This package.json file contains all the details of the application in which the user have inputted during the npm initialization.


## Usage




## Deployment


The URL of the GitHub respository is https://github.com/stellalph/EMPLOYEE_DBMS_TRACKER.git and the repository name of the project is EMPLOYEE_DBMS_TRACKER.


## License
  
This project is licensed under the terms of the MIT license.

## References
 
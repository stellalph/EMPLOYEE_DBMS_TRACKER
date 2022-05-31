# 12 SQL: Employee Tracker

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


## Table of Contents
* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)
* [Video](#video)
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

  * This application will need the installation of node.js and npm install (install a package and 
    its dependencies)

       - npm init
       - npm install

  * This also uses the inquirer dependencies which need to be installed. 

       - npm i inquirer

  * This will collect the input from the user and the application will be invoked by using the
    the following command:-

      - npm start

  * This application also uses MySQL2 package to connect to the database and perform queries. To 
    install the package, at the command prompt, type in :-

      - npm install --save mysql2

  * Console.table package was installed to print MySQL rows to the table and asciiart-logo was 
    was also installed to render a splash screen in text console.

      - npm i asciiart-logo
      - npm install console.table --save

  * For protection of credentials, dotenv was installed.  Dotenv is a zero-dependency module that
    loads environment variables from a .env file into process.env. 


      - npm install dotenv --save
   
    
## Usage

* The application uses this design of the database schema as shown which contains three tables:-
       - department
       - role
       - employee

![Database schema includes tables labeled “employee,” role,” and “department.”](./assets/img13.png)

* The output when executing the mysql query:-

![Database schema includes tables labeled “employee,” role,” and “department.”](./assets/Img01.png)


 ![Database schema includes tables labeled “employee,” role,” and “department.”](./assets/Img02.png) 



## Video

The link to the video to show the walkthrough of the application being used from the command line.
Please click on the link <strong> VIDEO </strong> below to access the video.

 * [VIDEO](https://drive.google.com/file/d/1G1eQdf6OhjKUZF3yHGe9jfU5-wD1NFjx/view)




The URL of the GitHub respository is https://github.com/stellalph/EMPLOYEE_DBMS_TRACKER.git and the repository name of the project is EMPLOYEE_DBMS_TRACKER.


## License
  
This project is licensed under the terms of the MIT license.

## References
 
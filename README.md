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

* The output when executing the mysql> source db/schema.sql; and mysql> source db/seeds.sql and the 
  following commands as shown.

![Database schema includes tables labeled “employee,” role,” and “department.”](./assets/img01.png)


 ![Database schema includes tables labeled “employee,” role,” and “department.”](./assets/img02.png) 

 * Below shows the steps of the command-line application:

   <em>1. At npm start, the user will be presented with the following options as shown below:-</em>

  ![User to select options](./assets/img03.png) 

  <em>2. Select option 1 and 2 will enable the user to view all departments and all roles</em>.

  ![User to select options](./assets/img04.png) 

  <em>3. Select option 3 will enable the user to view all employees</em>.
 
  ![User to select options](./assets/img05.png) 

  <em>4. Select option 4 will enable the user to add a department </em>.

  ![User to select options](./assets/img06.png) 

  <em>5. Select option 5 will enable the user to add a role </em>.

  ![User to select options](./assets/img07.png) 

  <em>6. Select option 6 will enable the user to add an employee </em>.

  ![User to select options](./assets/img08.png) 

  <em>7. Select option 7 will enable the user to update employee role </em>.

  ![User to select options](./assets/img15.png) 

  <em>8. Select option 8 will enable the user to update employee manager</em>.

  ![User to select options](./assets/img16.png) 

  <em>9. Select option 9 will enable the user view employees by manager and department</em>.

  ![User to select options](./assets/img14.png) 

   <em>10. Select option 10, 11 and 12 will enable the user to delete department, role and employees</em>.

  ![User to select options](./assets/img09.png)

  ![User to select options](./assets/img10.png)

  ![User to select options](./assets/img11.png)

  <em>11. Select option 13 will enable the user to view the total utilized budget of a department</em>.
  ![User to select options](./assets/img12.png)

  * Finally, option 14 is to exit out of the application and thank you for looking through 
    and please click on the video to see the walkthrough of the functionality of my Employee database management system tracker.       

## Video

The link to the video to show the walkthrough of the application being used from the command line.
Please click on the link <strong> VIDEO </strong> below to access the video.

 * [VIDEO](https://drive.google.com/file/d/1G1eQdf6OhjKUZF3yHGe9jfU5-wD1NFjx/view)


The URL of the GitHub respository is https://github.com/stellalph/EMPLOYEE_DBMS_TRACKER.git and the repository name of the project is EMPLOYEE_DBMS_TRACKER.


## License
  
This project is licensed under the terms of the MIT license.

## References
 
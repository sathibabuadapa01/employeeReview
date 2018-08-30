# employeeReview
Aim:
-----------------------
Design a web application that allows employees to submit feedback toward each other’s performance review.
Admin view
Add/remove/update/view employees
 Add/update/view performance reviews
 
 
Employee view
----------------------
List of performance reviews requiring feedback
 Submit feedback
Technologies:
Database:Mysql
API:Nodejs.
Frontend technologies:ejs

Database shema :
----------------------
create database  as employeereview

CREATE DATABASE employeereview;

Create table as employee
CREATE TABLE employee (
   id INT NOT NULL AUTO_INCREMENT,
    name VARCHAR(255) ,
    department VARCHAR(50),
    mail VARCHAR(50),
    review VARCHAR(50),
    PRIMARY KEY (ID)
);

description:
 Admin view
 ____________
 1)Admin can add the employee details to employee list
 2)Admin can upadte the employee details in employee records
 3)admin can give review to employee.
 4)admin can delete the particular employee records from employee records list.
 5)admin can view list of employee'
 Employee view:
 ---------------
 1)employee can view details of employee's in employee's list.
 2)employee can only give review to other employee and remaining all fields are non editable fields.
 ----------------
 
 


1.First, create the student and user tables using the script db_student_users.sql
2. After creating the tables, run the following queries in MySQL: 

To check the users table:

USE lms;
SELECT * FROM lms.users;

To check the student table:
USE lms;
SELECT * FROM lms.student;

Run each query separately to make sure both tables are working correctly.

NOTE*: Update the project’s database connection string with your own MySQL credentials.
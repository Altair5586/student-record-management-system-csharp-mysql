A C# Windows Forms application for managing student records with a MySQL backend. This project provides a user-friendly interface to perform CRUD operations on student data and includes secure login functionality for admins.

Features:
1. Admin login system (credentials stored in the users table).
2. Add new student records.
3. View all student records.
4. Update existing student information.
5. Delete student records.
6. Data Validation
7. Database Integration
8. Error Handling

Prerequisites:
1. MySQL Server installed and running
2. .NET Framework 
3. Visual Studio (recommended) 

Database setup:
1.First, create the student and user tables using the script db_student_users.sql
2. After creating the tables, run the following queries in MySQL: 

To check the users table:
USE lms;
SELECT * FROM lms.users;

To check the student table:
USE lms;
SELECT * FROM lms.student;

Run each query separately to make sure both tables are working correctly.

NOTE: Update the project’s database connection string with your own MySQL credentials.Ensure MySQL server is running before starting the application

How to Run:
1. Clone or download the project files
2. Open the solution file in Visual Studio (SRMS.sln)
4. Run the application
5. Login using the admin credentials stored in the users table.

Screenshots:
Login:
<img width="380" height="353" alt="image" src="https://github.com/user-attachments/assets/3ce37400-55ae-4c6a-ae5a-c7098c26578d" />
Dashboard:
<img width="697" height="518" alt="image" src="https://github.com/user-attachments/assets/31e8369e-c352-4eeb-9921-639f3e584c68" />


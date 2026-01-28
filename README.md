# Course Registration and Grade Tracking System

This project is a Course Registration and Grade Tracking System developed to manage university course enrollment and grading processes in a secure and structured manner.

The system supports three different user roles: Admin, Student, and Instructor. Each role can only perform actions within its authorization scope, ensuring role-based access control and data security.

## Technologies
- ASP.NET Core MVC
- C#
- SQL Server
- Entity Framework Core
- HTML, CSS, Bootstrap

## Database Design
The system uses a custom-designed SQL Server database created specifically for this project. All tables and relationships were designed manually, and the application accesses the database through Entity Framework Core.

## User Roles and Features

### Admin
- Add, update, and delete students
- Add, update, and delete instructors
- Add courses
- Assign instructors to courses
- Manage departments
- View student and instructor lists

### Student
- View available courses
- Register for courses related to their department
- View grades (midterm, final, average, letter grade)
- Duplicate course registration is not allowed

### Instructor
- View assigned courses
- View enrolled students
- Enter and update student grades

## CRUD Operations
- **Create:** Student creation, course registration  
- **Read:** Student listing, grade viewing  
- **Update:** Grade updates  
- **Delete:** Student deletion  

## Installation
To run the project locally, follow these steps:

1. Clone the repository or download it as a ZIP file.
2. Update the `ConnectionStrings` section in the `appsettings.json` file according to your local SQL Server configuration.
3. Open the **Package Manager Console** in Visual Studio.
4. Run the following command to create the database:
5. Run the project.

## Screenshots
![Login Screen](screenshots/login.png)
![Admin Dashboard](screenshots/admin.png)
![Student Panel](screenshots/student.png)

## Project Purpose
This project was developed to demonstrate MVC architecture, database design, role-based authorization, and real-world CRUD operations using ASP.NET Core and SQL Server.

## Note
This project was developed for educational purposes.

# CUET E-Testhub: Online Examination System

## Overview
CUET E-Testhub is an innovative web-based application developed using PHP, CodeIgniter, and MySQL Database, specifically designed for Chittagong University of Engineering and Technology (CUET). This project aims to streamline exam processes and enhance academic assessment by providing an efficient and user-friendly online examination platform. The system caters to three user roles: Administrator, Lecturer/Faculty, and Student.

## Features and Functionalities

### Administrator
- **Dashboard Page:** Display summary of the list.
- **Department, Class, Course Management:** Add, list, edit/update, delete, import, print, export, and copy functionalities for each category.
- **Lecturer and Student Management:** Add, list, edit/update, delete, generate system credentials, import, print, export, and copy functionalities.
- **Relation Management:** Set multiple classes for lecturers and multiple departments for classes.
- **Question Management:** Add, list, edit/update, delete, view details, add files per question, add files per question option.
- **Reports:** List all exams, view exam results, print or download exam results.
- **User Management:** List, edit/update, delete, import, print, export, copy, update account details/credentials, and clear all data in the database (except admin user).
- **Login and Logout**

### Lecturer/Faculty
- **Login**
- **Exam Set Management:** Add, list, edit, delete, re-generate exam token.
- **View Exam Results**
- **Download or Print Exam Result**
- **Update System Account Credential**
- **Logout**

### Student
- **Login**
- **Exam List:** List all available exam sets.
- **Take Exam:** Mark questions as doubt for reviewing before submitting.
- **View Exam Result**
- **Exam Timer:** Countdown display.
- **Update System Account Credential**
- **Logout**

## System Installation/Setup

### Requirements:
- Download and Install XAMPP or any local web server.
- Download the provided source code zip file.

### Installation Steps:
1. Start Apache and MySQL in XAMPP.
2. Extract the source code zip file.
3. Copy the folder to XAMPP's "htdocs" directory.
4. Open PHPMyAdmin, create a new database named 'onlinexaminationci'.
5. Import 'exam_db.sql' from the database folder.
6. Browse the application in a browser (http://localhost/CUET_E-TestHub/).

### Default Admin Access:
- Email: admin@mail.com
- Password: admin123

## Contributors

1. [Pinki Akter](https://github.com/pinkfloyed)
2. [Maayeesha Farzana](https://github.com/maayeesha)





# college-student-office-management-system
Python Tkinter + MySQL Student Office Management System


**🎓 College Student Office Management System**

A Desktop Student Office Management System built using Python (Tkinter) and MySQL.
This application allows administrators and students to manage and access academic records, fee details, marksheets, and other administrative information through a simple graphical interface.

📌 Project Overview

The College Student Office Management System is designed to simplify the management of student records in a college environment.

The system provides two types of users:

Admin – manages students, marks, fees, and exam records

Student – views personal academic and administrative information

The project demonstrates the use of:

Python GUI development

Relational database design

CRUD operations

Authentication systems

🛠 Technologies Used
Technology	Purpose
Python	Application logic
Tkinter	Desktop GUI framework
MySQL	Database management
SQL	Database queries
mysql-connector-python	Python-MySQL integration
📂 Project Structure
college-student-office-management-system
│
├── app.py                # Main Python application
├── setup.sql             # Database setup script
├── README.md             # Project documentation
└── requirements.txt      # Python dependencies
🗄 Database Schema

The project uses a MySQL database named:

bvp_student_office
Tables

Admins

Students

Marksheets

FeeReceipts

ExamStatus

MiscellaneousRecords

These tables are connected using foreign keys to maintain relational integrity.

👨‍💼 Admin Features

Admins can perform full management operations including:

Add new students

Update student details

Delete students

Add student marks

Manage fee receipts

Add exam results

Record administrative notes

View all records in table format

👨‍🎓 Student Features

Students can login and view:

Personal profile

Academic records

Marksheets

Fee payment history

Exam results

Miscellaneous administrative records

🔐 Login System

The application includes a secure login system for both users.

Demo Admin Login
Admin ID: ADM001
Password: adminpass
Demo Student Login
Student ID: STU001
Password: studpass

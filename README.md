# Enrollment System
[![Ask DeepWiki](https://devin.ai/assets/askdeepwiki.png)](https://deepwiki.com/SamuelAlac/Enrollment-System)

## Overview

The Enrollment System is a comprehensive desktop application developed in Java Swing designed to manage the academic enrollment process for a university. It provides a multi-user environment with distinct functionalities for administrators, staff (employees), and students, streamlining tasks from course management to student registration.

## Key Features

The system is tailored to three primary user roles, each with a dedicated dashboard and set of permissions.

### 1. Administrator
The administrator has full control over the system's core data and user management.

*   **Data Management:** Full Create, Read, Update, and Delete (CRUD) capabilities for:
    *   Colleges
    *   Courses
    *   Subjects
    *   Course-Subject Assignments
    *   Sections
    *   Student Records
    *   Employee Records
*   **User Account Management:** Manage the status of student and employee accounts.
*   **System Monitoring:** View detailed logs of student and employee activities within the system.

### 2. Staff / Employee
Employees, such as faculty members, have a focused dashboard to manage their academic responsibilities.

*   **Subject Viewing:** Check and view the list of subjects they are assigned to handle for the semester.

### 3. Student
Students can manage their enrollment and registration process through a dedicated portal.

*   **Enrollment:** Enroll in available subjects for a specific year level and semester.
*   **Registration:** Register for a specific section.
*   **View Certificate of Registration (COR):** Generate and view a printable Certificate of Registration detailing their enrolled subjects, schedule, and other relevant information.

### General Features
*   **Secure Login:** Role-based authentication for students, staff, and administrators.
*   **Password Recovery:** A "Forgot Password" feature that sends a temporary password to the user's registered email.
*   **Account Configuration:** Allows users to update their password after using a temporary one.

## Technology Stack

*   **Programming Language:** Java 20
*   **User Interface:** Java Swing with AbsoluteLayout
*   **Database:** Microsoft SQL Server
*   **Database Connectivity:** JDBC
*   **Reporting:** JasperReports, OpenPDF
*   **Build Automation:** Apache Ant
*   **IDE:** NetBeans

## Screenshots

### User Login & Role-Based Dashboards
A central login form authenticates users and directs them to the appropriate dashboard.

![Guest - Login](https://github.com/user-attachments/assets/8bfde12a-6e2a-49db-b367-575786769f7e)

### Student Enrollment Process
Students can select their section, year level, and semester to view and enroll in subjects.

![Enrollee - Registering to Section, Year Level and Semester](https://github.com/user-attachments/assets/3e4e30c2-f313-48be-848f-d668fb022d21)
![Enrollee - Enrollment](https://github.com/user-attachments/assets/1302d6d5-d079-4a7b-9c98-c4298f1af5e5)

### Staff Dashboard
Staff members can view the subjects they are assigned to teach.

![Employee - Checking subjects handled](https://github.com/user-attachments/assets/c5348361-fbcb-4dfc-b90f-b39b1d22a886)

### Administrator Dashboard & Management Panels
The admin has access to comprehensive management panels for all system entities.

**College Management (CRUD & Print)**
![College Create, Read, Update, Delete and Print](https://github.com/user-attachments/assets/b8a75f5c-4ab4-4368-bb55-1c804155bc1b)

**Course Management**
![Course CRUD](https://github.com/user-attachments/assets/0db8af4e-3937-4da8-8321-b73072c09619)

**Subject Management**
![Subject CRUD](https://github.com/user-attachments/assets/8b13ed94-bcb8-4516-bae4-6c645ad0f905)

**Course Subject Management**
![Course Subject CRUD](https://github.com/user-attachments/assets/c34bd256-d1bd-4d7b-837d-c51845c1afb9)

**Section Management**
![Section Management](https://github.com/user-attachments/assets/88a413b8-7303-490a-bfe7-8fd4505ccee1)

**Student Record Management**
![Student Management](https://github.com/user-attachments/assets/9eef85e9-1c1f-4f69-a158-539165dda1d0)

**Employee Record Management**
![Employee Management](https://github.com/user-attachments/assets/4fa01872-fddc-4025-8299-4b6b5de8e6bb)

**Activity Log Monitoring**
![Student Logs](https://github.com/user-attachments/assets/4602f3c6-84ce-4645-bc38-adfa63bd823d)
![Employee Logs](https://github.com/user-attachments/assets/f07c3cc7-d998-4454-b306-336d6aa76e2c)

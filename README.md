**Student Management System**
==========================

Overview
--------

This is a simple web-based Student Management System built using Java, JSP, and MySQL. The system allows users to create, read, update, and delete (CRUD) student records.

Features
--------

*   Create new student records
*   View all student records
*   Delete existing student records

Files and Folders
-----------------

*   `index.jsp`: The main page of the application, displaying all student records.
*   `create.jsp`: The page for creating new student records.
*   `delete.jsp`: The page for deleting existing student records.
*   `mystyle.css`: The stylesheet for the application.

Database
--------

The application uses a MySQL database named `sms27dec24` with the following credentials:

*   Host: `localhost`
*   Port: `3306`
*   Username: `root`
*   Password: `halloween`

The database contains a single table named `student` with the following columns:

*   `roll`: The roll number of the student (primary key)
*   `name`: The name of the student
*   `marks`: The marks of the student

Functionality
-------------

### Create Student Record

1.  Navigate to `create.jsp`
2.  Fill in the form with the student's roll number, name, and marks
3.  Click the "Save" button to create the new record

### View Student Records

1.  Navigate to `index.jsp`
2.  All student records will be displayed in a table

### Delete Student Record

1.  Navigate to `delete.jsp`
2.  Enter the roll number of the student to delete
3.  Click the "Delete Student" button to delete the record

Note
----

This is a basic implementation and may not include all the features and security measures required for a production-ready application.

-------------------------

*   Use consistent indentation (4 spaces)
*   Use meaningful variable names
*   Keep functions short and focused
*   Use comments to explain complex logic
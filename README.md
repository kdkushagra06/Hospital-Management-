# Hospital Management System (Python – Console Based)

This project is a console-based Hospital Management System developed in Python, designed to manage essential hospital operations through a clean menu-driven interface and user-defined modules. All records are stored using Python dictionaries, functioning as an in-memory database without using SQL or GUI frameworks.


---

Modular System Architecture

The project is structured into separate modules for improved organization and clarity:

Patient Management

Doctor Management

Appointment Management

Main Controller (Menu)


Each module contains independent functions that perform specific operations while interacting with a shared data structure.


---

Data Storage

All data is stored using dictionaries, with an auto-incrementing unique ID assigned to each patient, doctor, and appointment. 

This model enables fast Create, Read, Update, Delete (CRUD) operations.


Core Functionalities

Patient & Doctor Management

Both modules support:

Add new records

View all records in formatted list form

Search by unique ID

Update selected fields

Delete existing entries


These operations run live inside the console, with success and error messages guiding the user clearly.


---

Appointment Management

The Appointment system connects patients and doctors using their IDs.
Users can:

Book an appointment by selecting Patient ID, Doctor ID, date, and time

View all existing appointments

View appointments of a specific patient

Cancel appointments using Appointment ID


Every appointment record links both patient and doctor details for clarity.


---

Project Aim

This project demonstrates:

Modular programming in Python

Practical use of dictionaries as a lightweight database

Real-world workflow simulation inside the console

Complete CRUD-based record management

Clean separation of logic across multiple Python files



---

Conclusion

This Hospital Management System provides a functional demonstration of structured coding and data management without using graphical interfaces or external databases. It is a strong academic example of building a real application using only core Python, dictionaries, and user-defined modules.

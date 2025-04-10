# HospitalManagementSystem

A Java-based Hospital Management System that allows users to manage patients, doctors, and appointments. This project uses JDBC for connecting to a MySQL database, handling CRUD operations for patients and doctors, and supporting appointment bookings. The application is designed with an easy-to-use command-line interface (CLI).

Key Features:
Add, View, and Search Patients: Store and display patient information like name, age, and gender.

View Doctors and Their Specializations: Display doctors' details and their specialties.

Appointment Booking: Book appointments between patients and doctors, ensuring no scheduling conflicts.

Database-Driven: All patient, doctor, and appointment data is stored in a MySQL database.

Technologies Used:
Java (JDBC for database connectivity)
MySQL (Database)
CLI Interface (No GUI)

Setup and Installation:
1)Clone this repository to your local machine.
git clone https://github.com/your-username/hospital-management-system.git
2)Make sure you have MySQL installed and running.
3)Create a database named hospital and import the required schema (you can find this in the database.sql file, if provided).
4)Update the database connection details in the HospitalManagementSystem.java file (URL, username, and password).
5)Compile and run the project:
javac HospitalManagementSystem.java
java HospitalManagementSystem

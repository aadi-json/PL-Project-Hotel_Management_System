🏨 HOTEL MANAGEMENT SYSTEM (SQL & PL/SQL PROJECT)
📌 PROJECT OVERVIEW

This project is a PL/SQL-based Hotel Management System designed to manage hotel operations such as customer registration, room management, bookings, payments, services, employees, and reviews.
The system demonstrates the practical use of SQL and PL/SQL concepts including tables, constraints, indexes, stored procedures, triggers, cursors, and audit mechanisms.

The main goal of this project is to show how business rules and automation can be enforced at the database level using PL/SQL.

🎯 OBJECTIVES

To design a normalized relational database for hotel operations

To automate tasks using stored procedures and triggers

To maintain data integrity and consistency

To implement audit logging for important operations

To demonstrate real-world usage of PL/SQL features

🧱 DATABASE STRUCTURE

The project includes the following main tables:

CUSTOMER – Stores hotel guest details

ROOM_TYPE – Stores room categories and pricing

ROOMS – Manages physical room availability

BOOKING – Handles room reservations

PAYMENTS – Stores payment information

SERVICES – Stores optional hotel services

SERVICE_USAGE – Tracks services used during a stay

EMPLOYEE – Stores employee information

REVIEW – Stores customer feedback

REVIEW_AUDIT – Maintains audit history of reviews

⚙️ PL/SQL FEATURES USED
🔹 STORED PROCEDURES

Fetch customer details

Display room price information

Show booking details

🔹 TRIGGERS

BEFORE triggers for validation (phone number, payment amount, room rules)

AFTER triggers for automation and logging

Audit triggers to store review history

🔹 OTHER FEATURES

SYS_REFCURSOR

SEQUENCES

DBMS_OUTPUT

FOREIGN KEY & CHECK constraints

INDEXES (B-Tree, Bitmap, Reverse Key)

🔐 DATA INTEGRITY & SECURITY

Prevents invalid data insertion using BEFORE triggers

Blocks unauthorized deletion of critical records

Maintains audit logs for tracking user actions

Ensures consistency between related tables

🛠️ TOOLS & TECHNOLOGIES

ORACLE DATABASE

SQL

PL/SQL

SQL*PLUS / SQL DEVELOPER

🚀 HOW TO RUN THE PROJECT

Create a database user

Execute table creation scripts

Create sequences

Create stored procedures

Create triggers

Insert sample data

Test procedures and triggers using INSERT / UPDATE / DELETE

📈 FUTURE ENHANCEMENTS

Front-end integration (Web or Mobile)

Role-based access control

Automated billing system

Advanced reports and analytics

Multi-hotel support

👨‍💻 AUTHOR

Aditya Gawande
SQL | PL/SQL | Database Programming

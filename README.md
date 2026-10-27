# MediTrack-Hospital-Management
Hospital management database project using MySQL with Patients, Doctors, Appointments, Prescriptions, Billing, and an ER diagram.
# MediTrack – Hospital Management Database

## Project Overview
MediTrack is a hospital management database project developed using MySQL. It organizes patient records, doctor information, appointments, prescriptions, and billing details.

## Technologies Used
- MySQL 8.0
- SQL
- ER Diagram / Database Design

## Database Tables
1. **Patients** – Stores patient information.
2. **Doctors** – Stores doctor details and specialization.
3. **Appointments** – Connects patients and doctors.
4. **Prescriptions** – Stores prescribed medicines and dosage.
5. **Billing** – Stores payment and billing information.

## Relationships
- Patients → Appointments (One-to-Many)
- Doctors → Appointments (One-to-Many)
- Appointments → Prescriptions (One-to-Many)
- Appointments → Billing (One-to-Many in the current schema)

## Key SQL Concepts
- CREATE TABLE
- INSERT INTO
- SELECT
- WHERE
- Primary Keys and Foreign Keys
- Table Relationships

## How to Run
1. Install MySQL Server.
2. Open MySQL Workbench or MySQL Shell.
3. Create or select the `meditrack` database.
4. Run the SQL script from the `sql` folder.
5. Execute queries to explore the database.

## Project Purpose
This project demonstrates relational database design, SQL queries, and data management for a hospital management system.

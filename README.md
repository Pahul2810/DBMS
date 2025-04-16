# Hospital Management System (DBMS Project)

This project is a Hospital Management System developed as part of a Database Management System (DBMS) course. It simulates hospital operations and manages activities such as patient records, doctor information, appointments, room allocations, treatments, and billing. The backend is implemented using MySQL.

## Table of Contents

- Overview  
- Features  
- Technologies Used  
- Database Design  
- ER Diagram  
- Installation & Usage  
- Sample Queries  
- Project Structure  
- Report  

## Overview

The Hospital Management System is designed to streamline the daily operations of a hospital by automating tasks related to patient admissions, appointments, treatment tracking, and billing. It uses SQL queries to perform Create, Read, Update, and Delete (CRUD) operations on the database.

## Features

- Add, update, and delete patient details  
- Store and manage doctor records and specializations  
- Schedule appointments between patients and doctors  
- Allocate and manage hospital rooms and wards  
- Track treatments and maintain medical records  
- Generate bills and discharge patients  
- Execute relational queries for data analysis  

## Technologies Used

- Database: MySQL  
- Language: SQL  
- Tools: MySQL Workbench, phpMyAdmin  
- Platform: Windows or Linux  

## Database Design

The system includes the following tables:

1. patients – Stores patient details  
2. doctors – Stores doctor info and specialization  
3. appointments – Links patients and doctors  
4. rooms – Manages room types and availability  
5. treatments – Logs treatment records  
6. billing – Tracks bills and payments  
7. staff – Stores non-doctor hospital staff

All tables are normalized and connected using primary and foreign keys.

## ER Diagram

The ER Diagram displays all major entities and their relationships. Refer to the ER_Diagram image provided in the project files.

## Installation & Usage

1. Clone or download the repository.

2. Open MySQL Workbench or phpMyAdmin.

3. Import the following SQL files in order:  
   - Tables_Creation.sql  
   - Insert_Queries.sql  
   - Select_Queries.sql

4. Run the queries to explore the data and operations.

5. Check the Sample_Output_Screenshots folder to view results of the queries.

## Sample Queries

- View all appointments for a specific doctor  
- List all patients  
- Generate bill for a patient  
- Get treatment history by patient ID  
- Update or delete patient records  

## Project Structure

Hospital-Management-System/  
├── ER_Diagram.png  
├── Table_Relations.png  
├── Tables_Creation.sql  
├── Insert_Queries.sql  
├── Select_Queries.sql  
├── Sample_Output_Screenshots/  
├── hospital_management_report.pdf  
└── README.md

## Report

The project report includes:  
- Introduction  
- Tools and Techniques Used  
- System Configuration  
- ER Diagram  
- Table Relationships  
- Table Format and Structure  
- SQL Queries with Output  
- Summary and Conclusion

Refer to hospital_management_report.pdf for the complete report.

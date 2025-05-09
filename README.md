# 🏥 Clinic Booking System

## 📘 Project Description

The **Clinic Booking System** is a MySQL-based relational database designed to manage the core operations of a healthcare clinic. It provides structured storage for patients, doctors, appointments, and prescriptions, ensuring efficient booking and record-keeping. The system supports one-to-many and many-to-many relationships, enforces data integrity using primary and foreign keys, and captures key interactions such as diagnoses, treatments, and specialties.

### 🔑 Key Features

- Patient registration and information storage  
- Doctor management with support for multiple specialties  
- Appointment booking between patients and doctors  
- Prescriptions records tied to specific appointments  
- Relational integrity and normalized data structure

---

## 🛠 How to Run / Setup the Project

### Prerequisites

- **MySQL Server** (version 8.0)
- A MySQL client such as **MySQL Workbench**, **phpMyAdmin**

### Steps to Import the SQL File

1. **Clone or Download the Repository**
   git clone https://github.com/Nebert11/database.git
   cd clinic-booking-system

2. Open MySQL Workbench (or another client)

3. Run the SQL Script

    Open the file clinic_booking.sql

    Execute the script to create all tables and relationships

4. Verify the Tables
    Run this SQL command to confirm:

    SHOW TABLES;

**ERD Diagram**
![image](https://github.com/user-attachments/assets/5e6319c2-948d-4f21-a9b9-9b7b845a62ef)



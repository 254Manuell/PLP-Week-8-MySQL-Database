
## 🏥 Clinic Booking System

### 📌 Project Title

**Clinic Booking System - MySQL Database**

---

### 🧾 Description

This project implements a fully functional **Clinic Booking System** using MySQL. It models key components of a healthcare facility, including:

* Patient registration
* Doctor specialization
* Appointment scheduling
* Treatment management
* Billing and payments

The schema includes real-world relational features such as 1:1, 1\:M, and M\:M relationships, full constraint usage, and normalized structure for scalability.

---

### 🛠️ How to Set Up the Project

#### Step 1: Import the SQL File

1. Open your MySQL environment (Workbench, CLI, phpMyAdmin, etc.).
2. Run the provided SQL script `answers.sql` to create and initialize the full database schema.

```sql
SOURCE path/to/answers.sql;
```

> 💡 The script will create a new database called `clinic_booking_system`. Make sure no database with this name exists before running.

---

### 🖼️ ERD Diagram

The Entity Relationship Diagram (ERD) visualizes the database structure and relationships among all tables.

📎 **Link to ERD**:
![Clinic Booking ERD](ERD.png)

> The ERD shows primary keys, foreign keys, and all relationships between tables, generated via PlantUML.

---

### 📁 Repository Contents

```
📦 ClinicBookingSystem
 ┣ 🗃️ answers.sql           -- Full SQL schema (well-commented)
 ┣ 🖼️ ERD.png               -- Entity Relationship Diagram
 ┗ 📄 README.md              -- Project overview and setup guide
```


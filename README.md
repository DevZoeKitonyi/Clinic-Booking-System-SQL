1.Clone This Resopitory


https://github.com/DevZoeKitonyi/Clinic-Booking-System-SQL.git
cd Clinic-Booking-System-SQL-


### 2. Open MySQL and Import the Database

You can import the SQL schema and data using the MySQL command-line tool or any GUI like MySQL Workbench.

#### Option A: Using MySQL CLI

```shellscript
mysql -u root -p &lt; clinic_booking_system.sql
```

#### Option B: Using MySQL Workbench

1. Open MySQL Workbench
2. Connect to your server
3. Open `clinic_booking_system.sql`
4. Execute the full script


## 🔒 Roles & Permissions

The system uses MySQL roles to manage permissions:

| Role | Permissions
|-----|-----
| admin | Full access to the database
| developer | Full access (for development/testing purposes)
| doctor | Read patients and appointments, write prescriptions
| receptionist | Register patients and appointments


## 👥 Sample Users

- Developer: `dev_user` / `DevPass123!`
- Admin: `admin_user` / `AdminPass123!`
- Doctor: `dr_smith` / `DocPass123!`
- Receptionist: `reception_user` / `ReceptionPass123!`


## 📁 Contents

- `clinic_booking_system.sql` — Full schema, sample data, user roles, and privileges
- [ER Diagram]
#https://drive.google.com/file/d/1DzEtk63rOepB4Gbvvjsh_tURLAEgRVtJ/view?usp=sharing Clinic-Booking-System-SQL

## 📊 Database Schema

The database includes the following tables:

- Patients
- Doctors
- Appointments
- Prescriptions
- Medical Records
- Users
- Roles


## 🔍 Features

- Patient registration and management
- Appointment scheduling and tracking
- Doctor availability management
- Prescription records
- Role-based access control
- Comprehensive reporting


## 📝 License

MIT License. Use freely with attribution.





































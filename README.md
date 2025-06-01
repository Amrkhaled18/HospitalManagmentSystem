# 🏥 Hospital Management System

A desktop-based Hospital Management System built using **Windows Forms (.NET Framework)** and **Microsoft SQL Server**. This application provides essential administrative and operational features for hospitals and clinics, including patient registration, appointment scheduling, staff management, and billing.

---

## 📌 Features

- 🧾 **Patient Registration & Records**
- 📅 **Appointment Scheduling**
- 🧑‍⚕️ **Doctor and Staff Management**
- 💊 **Medical History and Prescription Tracking**
- 💳 **Billing and Payment Handling**
- 🔐 **User Login and Role-Based Access (Admin, Doctor, Receptionist)**

---

## 🛠️ Technologies Used

| Layer         | Technology            |
|---------------|------------------------|
| Frontend      | Windows Forms (WinForms) |
| Backend       | C# (.NET Framework)   |
| Database      | Microsoft SQL Server  |
| ORM/DB Access | ADO.NET or Entity Framework (depending on version) |

---

## 🏗️ Architecture

This system follows a **3-tier architecture**:
- **Presentation Layer**: Windows Forms UI
- **Business Logic Layer (BLL)**: Handles core logic and validation
- **Data Access Layer (DAL)**: Manages interaction with SQL Server

---

## 💾 Database Setup

1. Open **SQL Server Management Studio (SSMS)**.
2. Run the `HospitalDB.sql` script located in the `/Database` folder to create tables and seed initial data.
3. Update your database connection string in `App.config` or the code as needed.

Example connection string:
```xml
<connectionStrings>
  <add name="HospitalDB"
       connectionString="Data Source=.\SQLEXPRESS;Initial Catalog=HospitalDB;Integrated Security=True"
       providerName="System.Data.SqlClient"/>
</connectionStrings>
```

---

## ▶️ Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/HospitalManagementSystem.git
   ```
2. Open the solution in **Visual Studio 2022**.
3. Build the solution to restore dependencies.
4. Make sure the SQL Server is running and the connection string is valid.
5. Run the application.

---

## 🔒 User Roles

| Role        | Access Level                        |
|-------------|-------------------------------------|
| Admin       | Full access to all modules          |
| Doctor      | View/edit patients, add prescriptions |
| Receptionist| Register patients, book appointments |

---

## 📸 Screenshots

*Add screenshots here (Patient form, Dashboard, Login, etc.)*

---

## 📄 License

This project is open-source and free to use under the [MIT License](LICENSE).

---

## 🙋‍♂️ Author

**Your Name**  
[LinkedIn](https://linkedin.com/in/yourprofile) | [GitHub](https://github.com/yourusername)

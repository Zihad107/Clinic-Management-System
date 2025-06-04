

# 🏥 Clinic Management System

This **Clinic Management System** helps clinics manage patient appointments, medical records, billing, and admin tasks all in one place. It improves communication between patients, doctors, and staff for a smoother healthcare experience.

### 🤝 Collaboration

This project was built together by a team of four contributors:

* [Nusrat Jaben Aurnima](https://github.com/NushratJabenAurnima)
* [Md Shahrukh Hossain Shihab](https://github.com/shihab372)
* [Zihad Khan](https://github.com/collaborator3)
* [Shairin Akter Hashi](https://github.com/Shairin207)

Thanks to everyone for their hard work and dedication.

---

## 📌 Project Summary

This project is a **Software Requirements Specification (SRS)** for a system that manages:

* Patient registration and profiles
* Scheduling appointments
* Storing medical records
* Billing and payments
* Role-based access for patients, doctors, and admins

---

## 🚀 Features

* **User Login:** Secure login and registration with roles (patient, doctor, admin)
* **Patient Management:** Register, update profile, view prescriptions and history
* **Doctor Management:** Manage patient records, update schedules, approve/cancel appointments
* **Appointment Booking:** Easy booking and cancellation with notifications for doctors
* **Billing:** Automated billing and online payments, view billing history
* **Admin Dashboard:** Manage doctors, monitor activities, track finances
* **Security:** Strong authentication and data validation

---

## 📂 Modules

| Module             | What It Does                         |
| ------------------ | ------------------------------------ |
| Authentication     | Login, registration, and user roles  |
| Patient Module     | Book appointments, view records      |
| Doctor Module      | View appointments, manage patients   |
| Admin Module       | Manage doctors, users, and billing   |
| Billing Module     | Create invoices and process payments |
| Appointment Module | Schedule and manage appointments     |

---

## 🔧 Technologies

* Frontend: HTML, CSS, Bootstrap
* Backend: PHP (OOP)
* Database: MySQL
* Security: Session management

---

## 🗄 Database

Main tables include:

* Users (patients, doctors, admins)
* Appointments
* Medical Records
* Billing & Payments
* Doctor Schedules

---

## 🛠 Setup Instructions

1. Clone the repo:

   ```bash
   git clone https://github.com/your-username/clinic-management-system.git
   cd clinic-management-system
   ```

2. Set up the database:

   * Open phpMyAdmin
   * Create a database named `clinic_management`
   * Import the provided SQL files to create tables and insert data

3. Run the project:

   * Start a local server (XAMPP, WAMP, etc.)
   * Open your browser and go to:
     `http://localhost/clinic-management-system`

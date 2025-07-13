# 🏥 Hospital Management System (PHP & MySQL)

A web-based Hospital Management System (HMS) built using **PHP**, **MySQL**, **HTML**, **CSS**, and **JavaScript**. This system streamlines operations like patient registration, doctor appointments, billing, and more for small- to mid-scale hospitals.

---

## 🚀 Features

- 👩‍⚕️ Admin, Doctor & Patient Login
- 📝 Patient Registration & Profile Management
- 🩺 Doctor Management & Specialization Setup
- 📅 Appointment Booking & Scheduling
- 🧾 Billing & Invoice Generation
- 📄 Medical Records & Reports
- 🔒 Secure Role-based Access Control
- 📊 Dashboard with Key Stats (patients, appointments, revenue)

---

## 🧑‍💻 Tech Stack

| Layer       | Technology Used            |
|-------------|-----------------------------|
| Frontend    | HTML5, CSS3, JavaScript     |
| Backend     | PHP                         |
| Database    | MySQL                       |
| Admin Panel | Bootstrap, FontAwesome      |

---

## 🖥️ Screenshots

> *(Insert relevant screenshots of dashboard, login, appointment booking, etc. here)*

---

## 📁 Project Structure

```

Hospital-Management-System/
├── admin/
├── doctor/
├── patient/
├── assets/
├── includes/
├── dbconfig.php
├── index.php
├── login.php
└── logout.php

````

---

## ⚙️ Installation & Setup

1. **Clone the repo**
   ```bash
   git clone https://github.com/your-username/Hospital-Management-System-PHP.git
````

2. **Import Database**

   * Create a database in MySQL (e.g., `hmsdb`)
   * Import the `hmsdb.sql` file (located in `/database/` or root)

3. **Configure Database**

   * Open `dbconfig.php` and update your DB credentials:

     ```php
     $conn = new mysqli("localhost", "root", "", "hmsdb");
     ```

4. **Run the App**

   * Start Apache and MySQL via XAMPP/WAMP
   * Visit: `http://localhost/Hospital-Management-System-PHP/`

---

## 👥 User Roles & Credentials (Demo)

| Role    | Username | Password |
| ------- | -------- | -------- |
| Admin   | admin    | admin123 |
| Doctor  | doctor1  | doc123   |
| Patient | patient1 | pat123   |

> *(Update or remove default credentials in production)*

---

## ✅ To-Do (Enhancements)

* Add prescription module
* SMS/Email notification for appointments
* Role-based dashboards
* Data export (PDF/Excel)

---

## 🤝 Contributing

Contributions are welcome! Follow these steps:

1. Fork the repo
2. Create your feature branch: `git checkout -b feature/YourFeature`
3. Commit your changes: `git commit -m 'Add your message here'`
4. Push to the branch: `git push origin feature/YourFeature`
5. Open a Pull Request

---

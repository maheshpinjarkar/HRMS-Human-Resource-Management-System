# HRMS – Human Resource Management System

A modern and responsive **Human Resource Management System (HRMS)** built with **Python, Flask, SQLite, HTML, CSS, and JavaScript**.

This project provides an admin dashboard for managing employees, attendance, payroll, notifications, reports, analytics, and employee profiles from a centralized system.

## 🚀 Features

### 👨‍💼 Employee Management

* Add new employees
* View employee list
* Employee profile management
* Employee status management
* Profile photo upload
* Employee details and KYC information

### 📅 Attendance Management

* Track employee attendance
* Attendance status management
* Employee-wise attendance records

### 💰 Payroll Management

* Manage employee payroll
* Basic salary
* Bonus
* Deductions
* Total salary calculation
* Payroll records

### 📊 Dashboard & Analytics

* HR dashboard
* Employee statistics
* Attendance overview
* Payroll overview
* Analytics and reports

### 🔔 Notification System

* Create notifications
* View notifications
* Unread notification counter
* Mark notifications as read

### ⚙️ Admin Settings

* Admin profile settings
* Password change
* Theme settings
* Secure admin authentication

### 🔐 Authentication

* Admin login system
* Session-based authentication
* Password hashing
* Protected admin routes

---

## 🛠️ Technologies Used

| Technology | Purpose                     |
| ---------- | --------------------------- |
| Python     | Backend programming         |
| Flask      | Web framework               |
| SQLite     | Database                    |
| HTML5      | Frontend structure          |
| CSS3       | UI styling                  |
| JavaScript | Frontend functionality      |
| Jinja2     | Template rendering          |
| Werkzeug   | Security & password hashing |

---

## 📂 Project Structure

```text
HRMS/
│
├── app.py
├── database.db
├── requirements.txt
│
├── templates/
│   ├── base.html
│   ├── login.html
│   ├── dashboard.html
│   ├── employees.html
│   ├── add_employee.html
│   ├── employee_profile.html
│   ├── attendance.html
│   ├── payroll.html
│   ├── analytics.html
│   ├── reports.html
│   ├── notifications.html
│   ├── add_notification.html
│   └── settings.html
│
└── static/
    ├── css/
    │   └── app.css
    └── uploads/
```

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

### 2. Open the project

```bash
cd HRMS
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
python app.py
```

### 5. Open in browser

```text
http://localhost:8000
```

---

## 🔑 Demo Login

**Username:** `admin`

**Password:** `1234`

> For production use, change the default password and configure a secure `FLASK_SECRET_KEY`.

---

## 🔒 Security

The project includes:

* Password hashing using Werkzeug
* Session-based authentication
* Protected admin routes
* Secure filename handling for uploaded profile images
* Environment-based Flask secret key support

> This project is intended for learning, demonstration, and portfolio purposes. Additional security hardening is recommended before production deployment.

---

## 🎯 Purpose of the Project

The main goal of this project is to demonstrate how a complete HR management application can be developed using **Python Flask and SQLite**.

It demonstrates practical implementation of:

* CRUD operations
* Database management
* Authentication
* Session management
* File uploads
* Form handling
* Dashboard development
* HR workflows
* Backend and frontend integration

---

## 👨‍💻 Author

**Mahesh**

B.Tech Cyber Security Engineer

---

## ⭐ Future Improvements

* Employee self-service portal
* Role-based access control
* Email notifications
* Leave management
* Performance management
* Advanced payroll processing
* REST API integration
* PostgreSQL/MySQL support
* Cloud deployment
* Docker support

---

## 📄 License

This project is available for educational and portfolio purposes.

```
<img width="1906" height="911" alt="Screenshot 2026-05-10 100944" src="https://github.com/user-attachments/assets/8b356e0b-e90c-4e5e-ac94-d0dc6a51d70b" />
<img width="1600" height="771" alt="WhatsApp Image 2026-08-07 at 12 47 22 PM (5)" src="https://github.com/user-attachments/assets/d0b31e00-cba2-4209-a646-f11ecfe91c31" />
<img width="1600" height="766" alt="WhatsApp Image 2026-08-07 at 12 47 21 PM" src="https://github.com/user-attachments/assets/d2e8b272-2661-45c2-a104-b670bac60830" />
<img width="954" height="800" alt="WhatsApp Image 2026-08-07 at 12 47 22 PM (3)" src="https://github.com/user-attachments/assets/ae1a549d-e320-444f-a1b7-4b9398c98e97" />
<img width="1600" height="764" alt="WhatsApp Image 2026-08-07 at 12 47 22 PM (7)" src="https://github.com/user-attachments/assets/43e5c4b4-9ac9-4e34-be46-60a9c70759da" />
<img width="1600" height="767" alt="WhatsApp Image 2026-08-07 at 12 47 22 PM (4)" src="https://github.com/user-attachments/assets/b96e1129-8f6b-4039-90ee-7b1bd72abf09" />


## 👨‍💻 Author

Mahesh Pinjarkar

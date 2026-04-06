# Institutional Club Management System 🏛️

A comprehensive full-stack web application designed to digitize and streamline the administration, recruitment, and event management processes for campus clubs. This project replaces traditional manual paperwork with a centralized digital hub for both administrators and students.

## 🚀 Features

The system is split into two specialized interfaces to cater to different user roles:

### **1. Admin Interface (Management & Oversight)**
* **Event Hosting:** Create and manage institutional events with ease.
* **Mentor Assignment:** Assign dedicated mentors to specific clubs for better guidance.
* **Membership Control:** Review student applications with the ability to **Accept** or **Reject** memberships.
* **Club Oversight:** Monitor club activities and roster growth.

### **2. Student Interface (Engagement & Discovery)**
* **Club Browsing:** Explore all active clubs within the institution.
* **Registration:** Apply to join clubs directly through the portal.
* **Event Signup:** Register for upcoming events and workshops hosted by various clubs.

---

## 🛠️ Tech Stack

This project utilizes a robust **LAMP-style** architecture:

* **Frontend:** HTML5, CSS3 (Responsive Design)
* **Backend:** PHP (Server-side logic)
* **Database:** SQL (Structured data management for users, clubs, and events)
* **Server:** Apache (Local environment via XAMPP/WAMP)

---

## 📋 Database Schema

The SQL database is structured to handle relational data between:
* **Users:** (Admins, Students, Mentors)
* **Clubs:** (Club details, assigned mentors)
* **Applications:** (Joining requests and their statuses)
* **Events:** (Schedules and participant lists)

---

## ⚙️ Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/](https://github.com/)[Shashankh Varma ]/[College Club Enrollment System].git
    ```
2.  **Set up the Database:**
    * Open your MySQL admin tool (e.g., phpMyAdmin).
    * Create a new database named `club_management`.
    * Import the provided `.sql` file located in the `/database` folder.
3.  **Configure Connection:**
    * Update your PHP connection file (usually `db_connect.php` or similar) with your local database credentials (host, username, password).
4.  **Run the Project:**
    * Move the project folder to your server directory (e.g., `htdocs` for XAMPP).
    * Access the project via `localhost/[folder-name]`.

---

## 🤝 Contributing
This is a student project developed to improve campus life. Feel free to fork the repository and submit pull requests for any feature enhancements!

## 👤 Author
**[Shashankh Varma Vegesna]**

---
*Developed as part of the [Your Course/Institution Name] curriculum.*

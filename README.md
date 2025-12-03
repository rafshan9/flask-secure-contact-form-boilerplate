# 🚀 Flask Contact Form Starter Kit (Admin Panel + Database)

> **🛑 STOP CODING FROM SCRATCH.**
>
> **[Download the Full Source Code Here (Gumroad)] (https://rafshan1342.gumroad.com/l/mgiegf)**

---

A secure, production-ready Flask application with a database, email notifications, and an admin dashboard.

## Features
- 🚀 **Modern UI:** Clean interface using Bootstrap 5.
- 💾 **Database:** Automatically saves all leads to a SQLite database.
- 📧 **Email Alerts:** Sends an email to the admin instantly when a user submits the form.
- 🔒 **Admin Dashboard:** View all messages in a password-protected panel.
- 🛡️ **Security:** Protected against CSRF attacks; uses Environment Variables for secrets.

---

## Quick Start Guide

### 1. Install Requirements
Make sure you have Python installed. Then run:
```bash
pip install -r requirements.txt

### 2. Configure Settings
Rename `.env.example` to `.env` and open the file.
Set your specific variables:
- `SECRET_KEY`: Set this to a random string (e.g. "sd8923h89").
- `ADMIN_PASSWORD`: Set the password for the Dashboard.
- `MAIL_USERNAME`: Your Gmail address.
- `MAIL_PASSWORD`: Your Gmail App Password.

### 3. Run the App
```bash
python app.py
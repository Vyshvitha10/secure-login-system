# Secure Login System

## Overview

This project is a Secure Login Web Application developed using Python, Flask, SQLite, and bcrypt.

The application allows users to register and log in securely using hashed passwords while protecting against common security risks such as SQL Injection.

---

## Features

✔ User Registration  
✔ Secure Login Authentication  
✔ Password Hashing using bcrypt  
✔ SQL Injection Protection  
✔ Session Management  
✔ Logout Functionality  
✔ Basic Input Validation  
✔ Secure User Credential Storage  

---

## Technologies Used

- Python
- Flask
- SQLite
- bcrypt
- HTML

---

## Project Structure

```
Secure-Login-System/
│
├── app.py
├── users.db
├── templates/
│   ├── register.html
│   ├── login.html
│   └── dashboard.html
├── requirements.txt
└── README.md
```

---

## Installation

Install dependencies:

```bash
pip install flask bcrypt
```

---

## How to Run

Start the application:

```bash
python app.py
```

Open in browser:

```
http://127.0.0.1:5000
```

---

## Workflow

### User Registration
- User enters username and password
- Password is encrypted using bcrypt
- User information is stored securely

### Login
- Credentials are validated
- Password hash is verified
- User session is created

### Dashboard
- Logged-in users can access protected pages

### Logout
- Session is cleared securely

---

## Security Features

### Password Hashing
Passwords are encrypted using bcrypt before storage.

### SQL Injection Protection
Parameterized SQL queries are used to prevent malicious database attacks.

### Session Management
Sessions ensure authenticated access and secure logout.

---

## Expected Output

The application should:

- Register new users
- Authenticate login credentials
- Maintain secure sessions
- Allow logout
- Prevent unauthorized access

---

## Future Improvements

- Two-Factor Authentication (2FA)
- Email Verification
- Password Reset
- CAPTCHA Integration
- Improved UI Design

---

## Author

Developed as part of an internship/project task submission.

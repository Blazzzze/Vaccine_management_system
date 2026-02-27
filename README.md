# 💉 Vaccine Management System (C++)

A file-based Vaccine Management and Account Control System built in C++ using Object-Oriented Programming principles and persistent flat-file storage.

This project simulates a vaccination center platform supporting **Admin** and **User** roles with authentication, record management, and vaccination state tracking.

---

## 🚀 Features

### 👤 User Capabilities
- Create new user account
- Secure login with username & password
- View account details
- Check vaccination status (Dose 1 / Dose 2)

### 🛡 Admin Capabilities
- Secure admin creation (protected via supervisor key)
- Admin authentication system
- Search user records
- View total users/admin count
- Update vaccination status
- Delete admin accounts
- Display all registered users

---

## 🏗 Architecture

### Object-Oriented Design

- **Abstract Base Class:** `account`
- **Derived Classes:** `admin`, `user`
- Runtime polymorphism via virtual functions
- Hierarchical inheritance
- Encapsulation of credentials and metadata

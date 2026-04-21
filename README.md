# 🚀 Subscription & Hidden Expense Tracker

A modern desktop application built using **Python + CustomTkinter + MongoDB** that helps users manage their subscriptions, track expenses, and avoid unnecessary spending.

---

## 📌 Overview

Managing subscriptions can get messy — from OTT platforms to software tools. This application provides a **simple and interactive interface** to:

* 🔐 Sign up and log in securely
* 📊 Store and manage subscriptions
* 💰 Calculate total monthly & yearly expenses
* 🔔 Track upcoming renewals
* ⚠️ Identify unused subscriptions

---
## dashboard
<img width="1573" height="886" alt="image" src="https://github.com/user-attachments/assets/6f0ba7cf-2abd-4dbb-a58f-e06369908c11" /> 
<img width="1570" height="881" alt="image" src="https://github.com/user-attachments/assets/8176d9a3-cb64-4806-b4a2-ac75c1865266" /> 
<img width="1561" height="885" alt="image" src="https://github.com/user-attachments/assets/207a1dc3-8edc-46af-92eb-e7d15f8199d7" />

---
## ✨ Features

* 🔑 **Secure Authentication**

  * Password hashing using PBKDF2
  * Salt-based encryption for better security

* 📂 **Subscription Management**

  * Add, view, and manage subscriptions
  * Store renewal and usage details

* 📈 **Expense Tracking**

  * Automatic calculation of total spending
  * Monthly and yearly cost insights

* ⏰ **Smart Insights**

  * Detect unused subscriptions
  * Track renewal dates

* 🎨 **Modern UI**

  * Built using CustomTkinter
  * Clean and user-friendly interface

---

## 🧱 Project Structure

```
python-project/
│
├── main.py                # Entry point of the application
├── db.py                  # MongoDB connection setup
├── auth.py                # Authentication logic (login/signup)
├── models.py              # Data model (Subscription class)
├── tracker.py             # Business logic (calculations, tracking)
│
├── ui/                    # User Interface (Tkinter screens)
│   ├── ui.py
│   ├── login_screen.py
│   ├── dashboard.py
│   ├── add_subscription_screen.py
│   ├── view_subscriptions_screen.py
│
└── README.md
```

---

## 🗄 Database Configuration

* **Database Name:** `subscription_tracker`
* **Collections:**

  * `users`
  * `subscriptions`

Default MongoDB URI:

```
mongodb://localhost:27017/
```

---

## ⚙️ Requirements

Make sure you have:

* Python 3.x
* MongoDB (running locally)

Install required libraries:

```bash
pip install pymongo customtkinter
```

---

## ▶️ How to Run

1. Start MongoDB locally
2. Open terminal in project folder
3. Run:

```bash
python main.py
```

---

## 📅 Date Format

Use the following format for all date fields:

```
YYYY-MM-DD
```

Example:

```
2026-04-21
```

---

## 🔐 Security Implementation

* Passwords are **not stored directly**
* Uses:

  * Salt generation
  * PBKDF2 hashing
  * Secure comparison using `hmac`

---

## 🧠 Concepts Used

* Object-Oriented Programming (OOP)
* GUI Development (Tkinter / CustomTkinter)
* Database Integration (MongoDB)
* Authentication & Cryptography
* Modular Programming

---

## 🚀 Future Improvements

* Email reminders for renewals
* Data visualization (charts & graphs)
* Cloud database integration
* Mobile version of the app

---

## 👩‍💻 Author

Developed as part of a Python project focusing on **real-world application development and data handling**.

---

## ⭐ Final Note

This project demonstrates how Python can be used to build **secure, scalable, and user-friendly applications** by combining UI, backend logic, and database systems.

---

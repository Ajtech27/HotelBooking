# 🏨 HotelBooking

A full-stack hotel booking system built with Flask and PostgreSQL. Guests can browse rooms, check real-time availability, and book rooms for specific dates. The system prevents double-booking through conflict detection, lets users manage their reservations, and gives admins a dashboard to manage rooms and monitor bookings.

[![Python](https://img.shields.io/badge/Python-3.11%2B-blue)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-3.1.3-000000)](https://flask.palletsprojects.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-4169E1)](https://www.postgresql.org/)
[![Render](https://img.shields.io/badge/Render-Deployed-46E3B7)](https://render.com)

---
**[HotelBooking live](https://hotel-booking-vdfu.onrender.com)**

## ✨ Features

- **Authentication** — Register, login, logout with hashed passwords and role-based access (User / Admin)
- **Room Browsing** — View all available rooms with pricing, capacity, and descriptions
- **Booking System** — Select check-in and check-out dates with automatic conflict detection to prevent double-booking
- **My Bookings** — View upcoming and past bookings, and cancel with rules (e.g., 24-hour notice)
- **Admin Dashboard** — Add, edit, and delete rooms; view all bookings and users

---

## 🛠️ Tech Stack

- **Backend:** Python, Flask, SQLAlchemy, Flask-Login, Flask-Bcrypt, Flask-WTF
- **Database:** PostgreSQL (production), SQLite (development)
- **Frontend:** HTML, CSS, Bootstrap 5, Jinja2
- **Deployment:** Render, Gunicorn

---

## 🚀 Run Locally

```bash
git clone https://github.com/Ajtech27/HotelBooking.git
cd HotelBooking/backend
python -m venv venv
venv\Scripts\activate   # Windows
pip install -r requirements.txt
python seed.py          # Create tables + sample data
python run.py
```

---

## 👨‍💻 Author
 **Joseph Afolayan**

- [GitHub](https://github.com/Ajtech27)
- [LinkedIn](https://linkedin.com/in/afolayan-joseph)
- [Portfolio](https://ajtechportfolio.vercel.app)

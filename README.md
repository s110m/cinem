# Cinematwo 🎬

Cinematwo is a Django-based web application for managing and exploring cinema-related content.  
This project is an early-stage Django website structured with reusable apps and ready for further development.

---

## 📌 Features

- Built with **Django**
- Modular project structure
- Separate application (`web`) for core functionality
- SQLite support by default (Django standard)
- Ready for expansion into:
  - Movie listings
  - Reviews
  - User authentication
  - Booking system
  - Search and filtering
  - Admin dashboard

---

## 📁 Project Structure

```bash
cinematwo/
│── manage.py
│── requirement.txt
│── .gitignore
│
├── cinematwo/          # Main Django project settings
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── settings.py.sample
│   ├── urls.py
│   └── wsgi.py
│
└── web/               # Main application
    ├── migrations/
    ├── __init__.py
    ├── admin.py
    ├── apps.py
    ├── models.py
    ├── tests.py
    └── views.py

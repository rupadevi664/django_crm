# 🎓 Django Teacher Management System (CRUD)

A simple Django-based Teacher Management System that performs **CRUD (Create, Read, Update, Delete)** operations.
This project demonstrates Django's MVT architecture, ORM, URL routing, template rendering, and image upload functionality.

---

## 🚀 Features

- ➕ Add Teacher
- 👀 View Teacher List
- ✏️ Update Teacher Details
- 🗑️ Delete Teacher
- 🖼️ Upload Teacher Profile Image
- 📱 Responsive UI with Bootstrap

---

## 🛠️ Tech Stack

- Python
- Django
- SQLite
- HTML5
- CSS3

---

## 📂 Project Structure

```
Django_CRM-main/
│── manage.py
│── db.sqlite3
│── school/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│── teachers/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── admin.py
│   └── migrations/
│── templates/
│── static/
└── media/
```

---

## 🔄 Project Workflow

```
User
   ↓
URL (urls.py)
   ↓
View (views.py)
   ↓
Model (models.py)
   ↓
SQLite Database
   ↓
Template (HTML)
   ↓
Browser
```

---

## 📋 CRUD Operations

- **Create** – Add a new teacher
- **Read** – Display all teachers
- **Update** – Edit teacher details
- **Delete** – Remove a teacher

---

## 🗄️ Teacher Model

The project stores the following information:

- Name
- Subject
- Contact Number
- Email
- Profile Image

---

## ▶️ Installation

```bash
git clone https://github.com/rupadevi664/Django_CRM.git

cd Django_CRM-main/school

python -m venv venv

# Activate virtual environment

pip install -r requirements.txt

python manage.py migrate

python manage.py runserver
```

Open:

```
http://127.0.0.1:8000/
```

---

## 📚 Django Concepts Used

- Django MVT Architecture
- Models
- Views
- URL Routing
- Templates
- Django ORM
- CRUD Operations
- Static Files
- Media Files
- Image Upload
- SQLite Database

---

## 💡 Future Improvements

- User Authentication
- Student Management
- Attendance Management
- Dashboard
- Search & Pagination
- REST API Integration
- Role-Based Access Control

---

## 👩‍💻 Author

**Rupa Devi**

- Python Full Stack Developer
- Django Developer
- Passionate about Web Development & AI

---

## ⭐ If you found this project useful, please give it a star!

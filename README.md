<<<<<<< HEAD
# StudentManagement
=======
# 🎓 Student Management System

A web-based Student Management System built with Django that allows administrators and faculty to manage student records efficiently. It includes core functionalities such as student registration, database operations, and template-based views using Django’s MVC (MTV) architecture.

---

## 🚀 Tech Stack

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
</div>

---

## ✨ Features

- Add, update, and delete student records
- Template rendering using Django views
- SQLite database integration
- Clean and maintainable codebase
- Modular app structure
- Fully functional admin panel

---

## ⚙️ Installation & Setup

Clone the repository, create a virtual environment, install dependencies, and run the Django development server:

```bash
git clone https://github.com/kartikMpatel-Git-Hub/Student_Management_System.git
cd Student_Management_System

# Create a virtual environment
python -m venv venv
# Activate it (Windows)
venv\Scripts\activate
# Or for Unix/macOS
source venv/bin/activate

# Install Django
pip install django

# Make migrations and migrate database
python manage.py makemigrations
python manage.py migrate

# Run the development server
python manage.py runserver
```

## **📁 Project Folder Structure**
```bash
Student_Management_System/
├── Question_4/              # Django project settings
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── Student/                 # Student app with models, views, templates
│   ├── migrations/
│   ├── templates/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
├── db.sqlite3               # SQLite database
├── manage.py                # Django CLI
└── .gitignore               # Git ignored files
```

## **👨‍💻 Author**
Kartik Patel

>>>>>>> 55d888d (Initial commit)

Django CRUD Student Management

A simple Student Management System built with Django.
This project demonstrates how to perform CRUD operations (Create, Read, Update, Delete) using Django views and templates.

Features
Add new students with name, age, and email.
View a list of all students.
Update existing student information.
Delete students.
Uses Django templates for frontend (no React or API needed).

Installation
Clone the repository
git clone hhttps://github.com/Prabil155/django-crud-student-management.git
cd CRUD-with-Django

Create a virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

Install dependencies
pip install -r requirements.txt
Apply migrations
python manage.py migrate
Run the server
python manage.py runserver

Open your browser at http://127.0.0.1:8000/students/


Folder Structure
django_crud_app/
│
├── students/
│   ├── templates/
│   │   └── students/       # HTML files for CRUD pages
│   ├── views.py            # Handles CRUD logic
│   ├── models.py           # Student model
│   └── urls.py             # URL routes for student app
│
├── config/
│   └── settings.py         # Django settings
│
├── manage.py
└── requirements.txt


Usage
Navigate to the Students page.
Add a new student using the form.
Edit any student by clicking the "Edit" button.
Delete a student by clicking the "Delete" button.

All changes are stored in the SQLite database (default) unless configured otherwise.

Technologies Used
Python 3.x
Django 5.x
HTML, CSS, Bootstrap (optional)
SQLite (default DB

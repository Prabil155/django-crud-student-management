# Django CRUD Student Management

A simple **Student Management System** built with **Django**.  
This project demonstrates how to perform **CRUD operations** (Create, Read, Update, Delete) using **Django views and templates**.

---

## Features

- Add new students with **name, age, and email**  
- View a list of all students  
- Update existing student information  
- Delete students  
- Uses **Django templates** for frontend (no API needed)

---

## Installation

1. **Clone the repository**  
```bash
git clone https://github.com/your-username/CRUD-with-Django.git
cd CRUD-with-Django

2.Create a virtual enviroment
python -m venv venv
# Linux / Mac
source venv/bin/activate
# Windows
venv\Scripts\activate

3.Inatall dependencies
 pip install -r requirements.txt

4.Apply Migrations
 python manage.py migrate

5.Run the server
 python manage.py runserver

Folder Structure
django_crud_app/
├── students/
│   ├── templates/
│   │   └── students/       # HTML files for CRUD pages
│   ├── views.py            # Handles CRUD logic
│   ├── models.py           # Student model
│   └── urls.py             # URL routes for student app
├── config/
│   └── settings.py         # Django settings
├── manage.py
└── requirements.txt

Usage
Navigate to the Students page
Add a new student using the form
Edit any student by clicking the "Edit" button
Delete a student by clicking the "Delete" button

All changes are stored in the SQLite database (default).

Technologies Used
Python 3.x
Django 5.x
HTML, CSS, Bootstrap (optional)
SQLite (default DB)






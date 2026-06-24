# Little Lemon Restaurant Website

A full-stack restaurant website built with Django as part of the Meta Full Stack Developer Professional Certificate.

## Overview

Little Lemon is a family-owned Mediterranean restaurant that offers traditional recipes with a modern twist. This web application allows visitors to browse the menu, learn about the restaurant, and make table reservations online.

## Features

* Responsive restaurant website
* Home page with promotional content
* About page
* Dynamic menu system powered by Django models
* Individual menu item pages
* Online table reservation form
* Django Admin panel for managing bookings and menu items
* Static asset management (CSS, images, fonts)
* Deployment-ready configuration

## Technologies Used

* Python
* Django
* HTML5
* CSS3
* SQLite
* Git & GitHub
* Render

## Project Structure

littlelemon/
├── littlelemon/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── restaurant/
│   ├── models.py
│   ├── views.py
│   ├── forms.py
│   ├── templates/
│   └── static/
├── manage.py
└── requirements.txt

## Installation

1. Clone the repository

git clone https://github.com/mikeisresilient/little-lemon-website.git

2. Navigate to the project directory

cd little-lemon-website

3. Create and activate a virtual environment
4. 
python -m venv venv

Windows:

venv\Scripts\activate

4. Install dependencies

pip install -r requirements.txt

5. Apply migrations

python manage.py migrate

6. Start the development server

python manage.py runserver

## Admin Access

Create a superuser:

python manage.py createsuperuser

Access the admin dashboard at:

http://127.0.0.1:8000/admin/

## Learning Outcomes

This project demonstrates:

* Django project structure
* URL routing
* Views and templates
* Forms and model integration
* Database management with Django ORM
* Static file handling
* Git version control
* Cloud deployment using Render

## Author

Michael Ege

Full Stack Developer | Tutor | Trader

GitHub: https://github.com/mikeisresilient
View on browser: https://little-lemon-website-vbbb.onrender.com

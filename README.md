# 📝 Django Blog Application

A simple yet functional blog application built with **Django** that supports:
- User Registration & Login
- User Profiles
- Creating, Editing, and Deleting Posts
- Adding, Editing, and Deleting Comments
- Responsive HTML templates with Bootstrap

---

## 📂 Project Structure

myblog_project/
│
├── manage.py
├── db.sqlite3
├── README.md
│
├── myblog_project/ # Main project configuration
│ ├── init.py
│ ├── settings.py
│ ├── urls.py
│ ├── wsgi.py
│ └── asgi.py
│
├── users/ # User authentication & profile management
│ ├── models.py
│ ├── forms.py
│ ├── urls.py
│ ├── views.py
│ ├── templates/
│ └── users/
│ ├── login.html
│ ├── register.html
│ └── profile.html
│
├── posts/ # Blog posts
│ ├── models.py
│ ├── forms.py
│ ├── urls.py
│ ├── views.py
│ ├── templates/
│ └── posts/
│ ├── post_list.html
│ ├── post_detail.html
│ └── post_form.html
│
├── comments/ # Post comments
│ ├── models.py
│ ├── forms.py
│ ├── urls.py
│ ├── views.py
│ ├── templates/
│ └── comments/
│ ├── comment_form.html
│
└── static/ # CSS, JS, Images

yaml
Copy
Edit

---

## 🚀 Installation & Setup

1. **Clone this repository**
```bash
git clone https://github.com/yourusername/myblog_project.git
cd myblog_project
Create and activate a virtual environment

bash
Copy
Edit
python -m venv venv
# Windows
venv\Scripts\activate
# Mac/Linux
source venv/bin/activate
Install dependencies

bash
Copy
Edit
pip install django
Apply migrations

bash
Copy
Edit
python manage.py makemigrations
python manage.py migrate
Create a superuser

bash
Copy
Edit
python manage.py createsuperuser
Follow the prompts to set username, email, and password.

Run the development server

bash
Copy
Edit
python manage.py runserver
Access the app at: http://127.0.0.1:8000/

🛠 Features
User Authentication

Register, Login, Logout

Profile Page

Posts

Create, Edit, Delete posts

List and view post details

Comments

Add, Edit, Delete comments on posts

Responsive Design

Mobile-friendly using Bootstrap


📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

yaml
Copy
Edit

---

If you want, I can also **add badge icons** (Django version, Python version, license, etc.)

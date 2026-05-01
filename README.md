# 📝 Django Blog Web Application

A fully functional **Blog Web Application** built using Django, implementing complete CRUD (Create, Read, Update, Delete) operations with clean architecture, template inheritance, and secure form handling.


## 🚀 Features

* Create, Read, Update, Delete (CRUD) blog posts
* Dynamic URL routing with parameters
* Reusable templates using inheritance
* Secure form handling with CSRF protection
* User feedback using Django messages framework
* Clean and simple user interface


## 🛠️ Tech Stack

* Python
* Django
* HTML5
* CSS3
* SQLite


## 📚 What I Learned

* Setting up Django project and applications
* Creating models and interacting with the database using ORM
* Handling HTTP requests using function-based views
* Configuring URL routing and dynamic parameters
* Rendering dynamic data using templates
* Implementing template inheritance for reusable layouts
* Handling forms using POST method
* Securing forms with CSRF tokens
* Using `get_object_or_404` for error handling
* Implementing Django messages for user feedback
* Using `redirect()` after form submission
* Building full CRUD functionality:

  * Create Post
  * Read/View Posts
  * Update Post
  * Delete Post



## ⚙️ Setup Instructions

1. Clone the repository

git clone https://github.com/vasanthturpati25/Django_Blog_Website_App.git
cd Django_Blog_Website_App


2. Create virtual environment

python -m venv venv


3. Activate virtual environment

venv\Scripts\activate   # Windows  
source venv/bin/activate  # Linux/Mac  

4. Install dependencies

pip install django

5. Run migrations

python manage.py makemigrations
python manage.py migrate


6. Run the development server

python manage.py runserver

7. Open in browser:

http://127.0.0.1:8000/


## 💡 Key Highlights

* Clean and beginner-friendly Django project structure
* Proper separation of concerns (models, views, templates)
* Implementation of reusable UI using template inheritance
* Secure and structured form handling
* Demonstrates core backend development concepts


## 🎯 Why This Project

This project was built to strengthen my understanding of Django fundamentals and backend development concepts such as request handling, database interaction, and template rendering.

It also serves as a foundation for integrating advanced features and DevOps practices in future projects.



## 🎯 Future Improvements

* Add user authentication (Login/Signup)
* Add comments functionality
* Use PostgreSQL instead of SQLite
* Dockerize the application
* Deploy on AWS EC2 with Nginx & Gunicorn
* Implement CI/CD using GitHub Actions



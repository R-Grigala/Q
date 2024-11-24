QuickQuiz

QuickQuiz is a dynamic web application built with Flask, designed for users to register, take quizzes, and earn points. It combines modern web technologies, robust back-end frameworks, and a containerized deployment for a seamless experience.

Features
User Registration & Authentication:
Secure user registration and login functionality using Flask-Login.

Take Quizzes:
Interactive quizzes with a points system to track user performance.

Admin Panel:
    Manage users, quizzes, and results through a robust admin interface using Flask-Admin.

Technology Stack:
    Frontend: JavaScript, Bootstrap 5
    Backend: Flask, SQLite (via SQLAlchemy)
    Testing: Pytest for unit and integration testing
    Deployment: Nginx, uWSGI, and Docker Compose

Installation
Prerequisites
Docker and Docker Compose installed on your system.
Steps
Clone the repository:

    git clone https://github.com/R-Grigala/QuickQuiz.git
    cd QuickQuiz
Build and run the application with Docker Compose:

bash
Copy code
docker-compose up
Access the application:

Frontend: http://localhost
or Frontend: http://127.0.0.1
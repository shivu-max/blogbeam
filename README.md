# 🚀 BlogBeam

BlogBeam is a lightweight and fully functional blog web application built using **Flask**.  
It allows users to log in and manage blog posts with full CRUD (Create, Read, Update, Delete) functionality.

This project demonstrates backend web development fundamentals including routing, authentication, templating, and database integration.

---

## 📌 Features

-  User Authentication (Login / Logout)
-  Create Blog Posts
-  Edit Existing Posts
-  Delete Posts
-  SQLite Database Integration
-  Dynamic Rendering using Jinja2
-  Clean and Organized Project Structure

---

## 🛠️ Tech Stack

- **Backend:** Python, Flask
- **Database:** SQLite
- **ORM:** Flask-SQLAlchemy
- **Templating Engine:** Jinja2
- **Frontend:** HTML5, CSS3

---

## 📂 Project Structure
flask_project/
│
├── blogbeam.py        # Main Flask application
├── requirements.txt   # Project dependencies
├── README.md
├── .gitignore
│
├── templates/         # HTML templates
│   ├── index.html
│   ├── login.html
│   ├── add_post.html
│   ├── layout.html
│   ├── header.html
│   └── dropdown.html
│
└── instance/          # Local configuration (ignored in Git)

##⚙️ Installation & Setup

1. Clone the Repository
git clone https://github.com/shivu-max/projects.git
cd projects

2. Create a Virtual Environment
python -m venv .venv
source .venv/bin/activate     # macOS / Linux
.venv\Scripts\activate        # Windows

3.Install Dependencies
pip install -r requirements.txt

4.Run the Application
python blogbeam.py

Open in browser: 
  1. http://127.0.0.1:5001
  2. http://192.168.1.3:5001

## 🗃️ Database
Database: SQLite
File: app.db
Automatically created on first run (if not present)

##🔐 Authentication
Session-based authentication
Login / Logout functionality
Access control for protected routes
(Future enhancement: password hashing & role-based access control)

##🎯 Learning Objectives
This project demonstrates:
Flask routing & request handling
Working with relational databases
Implementing CRUD operations
Managing user sessions
Structuring a backend web application

##🚀 Future Improvements
Password hashing with werkzeug.security
User registration system
Comment system
Rich text editor for posts
REST API support
PostgreSQL integration
Deployment (Render / Railway / AWS)
Docker containerization

##📦 Requirements
Flask
Flask-SQLAlchemy

📜 License
This project is open-source and available .




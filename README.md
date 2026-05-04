# 🎓 Student Management REST API

A RESTful backend API for managing students, courses, and grades — built with Python, Flask, and Flask-RESTX. Includes Swagger UI documentation and JWT authentication.

---

## 🚀 Features

- 🔐 JWT-based login and registration for Teachers and Students
- 👩‍🏫 Two user roles — **Teacher** and **Student** — with role-based access control
- 📚 CRUD operations for students, courses, and enrollments
- 📊 Grade tracking and GPA calculation
- 📖 Auto-generated **Swagger UI** documentation at `/`
- 💾 SQLite database with SQLAlchemy ORM

---

## 🛠️ Tech Stack

| Layer      | Technology                        |
|------------|-----------------------------------|
| Backend    | Python, Flask, Flask-RESTX        |
| Database   | SQLite, SQLAlchemy ORM            |
| Auth       | JWT (JSON Web Tokens), RBAC       |
| Docs       | Swagger UI (auto-generated)       |

---

## 📂 Project Structure

```
Student-Management-API/
├── runserver.py        # Entry point
├── requirements.txt
└── api/
    ├── auth/           # Login & register routes
    ├── students/       # Student endpoints
    ├── courses/        # Course endpoints
    ├── grade/          # Grade calculator
    ├── models/         # Database models
    ├── decorators/     # Auth decorators
    └── config/         # App configuration
```

---

## ⚙️ How to Run

```bash
# 1. Clone the repository
git clone https://github.com/nirikshan9611/student-management-api.git
cd student-management-api

# 2. Install dependencies
pip install flask flask-restx flask-sqlalchemy flask-jwt-extended

# 3. Run the app
python runserver.py
```

Open your browser and go to: `http://127.0.0.1:5000`  
Swagger docs will load automatically.

---

## 👤 User Roles

| Role    | What they can do                                  |
|---------|---------------------------------------------------|
| Teacher | Add/edit/delete students, courses, assign grades  |
| Student | View their courses, grades, and GPA               |

---

## 👨‍💻 Developed By

**Nirikshan K**  
GitHub: [github.com/nirikshan9611](https://github.com/nirikshan9611)

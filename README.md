# REST APIs Project with Flask and Python

# 🧠 REST APIs with Flask and Python

![REST API with Flask and Python](assets/rest-api-flask-python.png)

This project is a full-featured REST API built using **Flask** and **Python**. It demonstrates how to design scalable and modular APIs with authentication, validation, documentation, and database integration.

---

## 🔧 Features

- ✅ RESTful API architecture
- 🔐 JWT-based user authentication (access + refresh tokens)
- 📘 Auto-generated Swagger (OpenAPI) documentation
- 🧩 Modular code structure for scalability
- 🗃️ SQLAlchemy ORM with PostgreSQL or SQLite
- 📦 Docker support (optional)
- 🔄 CRUD operations
- 📂 JWT token blocklisting (logout functionality)

---

## 📁 Tech Stack

- **Python 3.x**
- **Flask**
- **Flask-JWT-Extended**
- **Flask-SQLAlchemy**
- **Flask-Marshmallow**
- **Flask-RESTful**
- **Flasgger** (for Swagger docs)
- **SQLite / PostgreSQL**

---

## 🚀 Getting Started

### 🔧 Setup

```bash
# Clone the repo
git clone https://github.com/your-username/rest-apis-project.git
cd rest-apis-project

# Create virtual environment

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies

pip install -r requirements.txt

⚙️ Environment Setup

FLASK_APP=app.py
FLASK_ENV=development


⚙️ Database Migrations

# Initialize migration folder
flask db init

# Generate migration script
flask db migrate -m "Initial migration"

# Apply migration
flask db upgrade

🏃 Run the Application
 
 flask run

![REST API Project with Flask and Python](assets/rest-api-flask-python.png)


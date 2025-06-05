# 📘 Django REST API – Base Project Setup with Poetry

This repository contains the initial setup for a RESTful API project using **Django 4** and **Django REST Framework**, configured with **Poetry** for dependency management and virtual environment control.

The project is structured to scale and serve as a backend for modern web or mobile applications.

---

## 🚀 Tech Stack

- **Python 3.12+**
- **Django 4.x**
- **Django REST Framework**
- **Poetry** (dependency and environment manager)
- **SQLite** (for local development)

---

## 📁 Project Structure

bookstore/
├── bookstore/ # Main Django config
│ └── settings.py # DRF enabled
├── api/ # App for API logic
│ ├── models.py
│ ├── views.py
│ ├── tests.py
│ └── migrations/
├── db.sqlite3
├── manage.py
├── poetry.lock
└── pyproject.toml


---

## ⚙️ Key Features

- Project bootstrapped for **REST API development**
- DRF already added to `INSTALLED_APPS`
- Designed for modular and scalable architecture (`api/` app)
- Ready for serializer and endpoint creation
- Dependency isolation with Poetry

---

## 📌 Setup Instructions

### 🔧 Install Poetry (if you haven't)

```bash
curl -sSL https://install.python-poetry.org | python3 -

📦 Install dependencies

poetry install

🏃 Run the server

poetry run python manage.py runserver

🛠️ Next Steps

    Add models and migrations

    Create serializers and viewsets

    Register API routes using DefaultRouter

    Write unit tests for endpoints

✅ Status

🧪 In progress – Base project configured. Development of API logic and endpoints coming next.

    🎓 This project is part of the Full Stack Python Program at EBAC, used to explore Django REST development and modern project structuring with Poetry.

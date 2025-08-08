# 📝 BlogWebApp

A full-featured blog web application built using **Django**. This project demonstrates key concepts like user authentication, CRUD operations, custom templates, and Django’s powerful admin interface.

---

## 🚀 Features

- 🔐 User Registration, Login, Logout
- ✏️ Create, Read, Update, Delete (CRUD) blog posts
- 👤 Author-based content filtering
- 🖼️ Profile management with image uploads
- ⌛ Pagination of blog posts
- 📅 Post timestamps
- 🧰 Django admin panel customization

---

## 🛠️ Tech Stack

- **Backend**: Django 4.x (Python)
- **Frontend**: HTML, Bootstrap 4
- **Database**: SQLite (default Django DB for development)
- **Authentication**: Django's built-in User model
- **Image Handling**: Pillow

---

## 📦 Project Setup

Follow the steps below to set up and run this project locally on your machine:

### 1. Clone the Repository
```bash
git clone https://github.com/Gravity-2010/BlogWebApp.git
cd BlogWebApp
```

### 2. Create and Activate a Virtual Environment
**Windows (PowerShell):**
```bash
python -m venv env
.\env\Scripts\Activate
```

**macOS/Linux:**
```bash
python3 -m venv env
source env/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Apply Migrations
```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Create a Superuser (for accessing the admin panel)
```bash
python manage.py createsuperuser
```
Follow the prompts to set a username, email, and password.

### 6. Run the Development Server
```bash
python manage.py runserver
```

Visit `http://127.0.0.1:8000/` in your browser to access the app.

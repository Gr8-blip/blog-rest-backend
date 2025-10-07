# Blog REST Backend
A Django REST API for managing blog posts with secure user authentication and author-based permissions.

## 🚀 Overview
Blog REST Backend is a fully functional API built using **Django REST Framework (DRF)**.  
It provides endpoints for user registration, authentication, and complete CRUD operations for blog posts.  
Only authors can manage their own posts, keeping things safe and properly permissioned.

## 🧠 Features
- 🔐 User registration and login (JWT authentication)
- ✍️ Create, read, update, and delete blog posts
- 👤 Author-based permissions
- 🧰 Built with Django REST Framework

## 🛠️ Tech Stack
- **Backend:** Django, Django REST Framework  
- **Database:** SQLite (default)  
- **Auth:** JWT / Token Authentication  
- **Language:** Python

---

## ⚙️ Getting Started
First off you could get a quick walkaround of the API here [here](https://blogy-api-53ps.onrender.com/)

OR get it working on your machine 👇👇👇

### 1. Clone the repository
```bash
git clone https://github.com/Gr8-blip/blog-rest-backend.git
cd blog-rest-backend
````

### 2. Run the setup script

Make sure you have **Python 3.9+** and **pip** installed.
Then run the build script to install dependencies, apply migrations, and collect static files:

```bash
bash build.sh
```

### 3. Start the development server

```bash
python manage.py runserver
```

The API should now be running at:

> [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

### 4. Test with Postman or any API client

Use **Postman**, **cURL**, or **Thunder Client (VS Code)** to test endpoints.
You can register a new user, log in, and then use the access token to perform CRUD actions on blog posts.

---

## 🎯 Purpose
I built this project to sharpen my backend development skills with Django REST Framework
and to understand RESTful API design, authentication, and permission systems.
---

> Inspired by a Django REST Framework tutorial. Modified and expanded for personal learning and portfolio use.
